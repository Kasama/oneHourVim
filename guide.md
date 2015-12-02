One-Hour Vim
============

Summary
-------
- [You filthy cheater](#cheat)
- [Baby Steps](#baby)
	- [Survive](#survive)
	- [Modes? WTF?](#modes)
		- [Normal](#normal)
		- [Insert](#insert)
		- [Replace](#replace)
		- [Visual](#visual)
		- [EX](#ex)
	- [Discover the environment](#env)
		- [Actions](#actions)
		- [Motions](#motions)
		- [Objects](#obj)
	- [DRY - Don't Repeat Yourself](#dry)
	- [So much to learn](#adapt)
- [I heard it's customizable](#custom)
	- [Default behaviour sucks](#mappings)
	- [Follow my lead](#leader)
	- [Man of few words](#abbreviations)
	- [There's a plug-in for that!](#plugins)
- [I challenge you](#vimgolf)
- [Where to go from here?](#more)

<a name="cheat"></a> You filthy cheater
---------------------------------------

![Cheat sheet][1]

[1]: http://www.viemu.com/vi-vim-cheat-sheet.gif

<a name="baby"></a> Baby Steps
------------------------------

### <a name="survive"></a> Survive

- close
- save
- insert
- mouse

### <a name="modes"></a> Modes? WTF?

- <a name="normal"></a> Normal
- <a name="insert"></a> Insert
- <a name="visual"></a> Visual
- <a name="Replace"></a> Replace
- <a name="ex"></a> EX
	- set number/relative
	- set !, ?

### <a name="env"></a> Discover the environment

#### <a name="actions"></a> Actions
- `i` `I` `a` `A` `s` `S`
- `o` `O` 
- `p` `P`
- `r`
- `u` `C-R`

---
- `y` `Y`
- `c` `C`
- `d` `D`
- `v` `V`
- `<` `>`

#### <a name="motions"></a> Motions

- `h` `j` `k` `l` `←` `↓` `↑` `→`
- `0` `$` `^` `g_`
- `w` `W` `e` `E` `b` `B`
- `f` `F` `t` `T`
- `G` `gg` `NG`
- `{` `(` paragraph and sentences

---
- `%` `*` `#`
- `/pattern` `?pattern`
- `n` `N`

#### <a name="objects"></a> Objects

- `i` `a`
	- `{` `(` `[` `<` `"` `'` `w` `t`
	- `s` `p`

### <a name="dry"></a> DRY - Don't Repeat Yourself
- `q`
- `.`
- `,` `;`

- `C-n`
- `C-p`

### <a name="adapt"></a> So much to learn

- unmap vicious behaviour <nop>

<a name="custom"></a> I heard it's customizable
-----------------------------------------------

### <a name="mappings"></a> Default behaviour sucks

- map
	- n, i, v
	- jk as <esc>
	- example, surround in quotes
- unmap
	- n, i, v
- noremap
	- nmap dd O<esc>jddk

### <a name="leader"></a> Follow my lead

- let mapleader = ...
- let localmapleader = ..

### <a name="abbreviations"></a> Man of few words

- iabbrev

### <a name="plugins"></a> There's a plug-in for that!

- [Vundle](http://github.com/VundleVim/Vundle.vim)
- [NerdTree](http://github.com/scrooloose/nerdtree)
- [SuperTab](http://github.com/ervandew/supertab)
- [UltiSnips](http://github.com/SirVer/ultisnips)

<a name="vimgolf"></a> I challenge you
--------------------------------------


- [Simple 1](http://vimgolf.com/challenges/55b18bbea9c2c30d04000001): using <C-A>, w, <C-N>, NTimes, O, G and #
	- #Yp<C-A>w11<C-A>GONew te<C-N>.<CR><ESC>ZZ
- [Simple 2](http://vimgolf.com/challenges/55bcdc3ef4219f456102374f): using v, x, NTimes and registers
	- $8XFb9vp$PZZ
- [Simple 3](http://vimgolf.com/challenges/540629666a1e4000020d9e5a): using macro/regex replace
	

<a name="more"></a> Where to go from here?
------------------------------------------

- Learn vimscript the hard way
- Vimcasts
- ViEmu

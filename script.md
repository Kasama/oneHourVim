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
		- [Motions](#motions)
		- [Objects](#obj)
	- [DRY - Don't Repeat Yourself](#dry)
	- [So much to learn](#adapt)
- [I heard it's customizable](#custom)
	- [Default behaviour sucks](#mappings)
	- [Man of few words](#abbreviations)
	- [Follow my lead](#leader)
	- [There's a plug-in for that!](#plugins)
- [I challenge you](#vimgolf)

<a name="cheat"></a> You filthy cheater
---------------------------------------

You are probably not yet familiar with normal mode Vim's key bindings.  
[Here][1]'s something that will come in handy
![Cheat sheet][1]

Wow, that's a lot to digest at once.  
We'll get to know better the most used of those keystrokes in the next sections.

<a name="baby"></a> Baby Steps
------------------------------

You are a baby in a new environment and you don't know what's ahead of you, but with guidance you'll be able to conquer the unknown.

[1]: http://www.viemu.com/vi-vim-cheat-sheet.gif

### <a name="survive"></a> Survive

To be able to conquer this new environment, you'll first need to survive in it.  
Fire up a terminal, type `vim` and hit enter. What now? You don't even know how to close it.  
Let's check our [Cheat sheet](#cheat). As you can see in the `Notes` section, `ZZ` or `ZQ` can be used to quit, you can also quit Vim is by typing `:wq` or `:q` and hitting enter.  
`:wq` is equivalent to `ZZ`, but `:q` is not equivalent to `ZQ`. `:q` won't let you quit if you have unsaved changes, whereas `ZQ` will. You can type `:q!` to quit ignoring unsaved changes.  
  
You are in a text editor, but if you start typing, no words will show up, that's because you are in [`Normal`](#normal) mode (we will learn more about [Modes](#modes) later). To insert some text, you must be in [Insert](#insert) mode. To switch to insert mode, type `i`. Now you can start typing your text just like you would in any other text editor. When you're done, type `ESC` to go back to normal mode.






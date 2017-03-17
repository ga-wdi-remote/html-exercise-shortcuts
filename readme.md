---
title: Look Ma, No Mouse
type: exercise
competencies: keyboard shortcuts
creator: Christine Yi for WDIR
---


[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive-remote)

# Morning Exercise: Look Ma, No Mouse!

![giphy](https://media.giphy.com/media/o0vwzuFwCGAFO/giphy.gif)

Welcome to your first morning exercise! Every morning we will start the day warming up our brains with different coding challenges and exercises. It's the best way to kick-off the day here. I'll usually explain the instructions of the exercise for a minute, and give you about 45 minutes to solve it independently or in pairs. Today we'll work individually. Let's start with a warm up.

<hr>

## The Warm Up

### Instructions

* Read all of the instructions before doing anything.
* You will have 5 minutes to complete this task, so try to work quickly.

  1. Open up Atom.
  2. Create a new file called "warmup.html" and save it in your `Desktop` directory.
  3. Go to  [this link](https://raw.githubusercontent.com/hizegi/day1-repo/master/README.md), select all (`cmd` + `a`), copy the whole chunk of text (`cmd` + `c`), and paste it in your `warmup.html` (`cmd` + `v`). We're copying a raw text file that contains our HTML code. We'll open this website on the browser through terminal.
  4. Save the file (`cmd`+`s`) in Atom. _Always make sure you save after any changes before running it._
  4. Open up terminal and `cd` into your `Desktop` (`cd Desktop`). Sometimes you have to make sure the D is capitalized.
  5. Type `ls` in terminal and make sure you see `warmup.html`. If you don't, type `pwd` and make sure you are actually in your Desktop.
  6. Type `open warmup.html`. You should be able to see the warm up site!
  6. We're opening an .html file, but it's configured to open in Chrome, so voila!
  7. Now that you read all of the instructions, you're actually going to learn more shortcuts, so only do step 1, and don't do steps 2 - 7. Then read on some [Atom shortcuts cheatsheet](https://github.com/nwinkler/atom-keyboard-shortcuts) and try playing around with them in Atom.

<hr>

## The Exercise

Ok now FOR REAL, we're going to practice shortcuts and **ONLY use our keyboard** in this exercise! The less you touch your mouse, the more Pro you are :neckbeard: Let's create a website without a mouse!!

:beetle: Debugging tip: `cmd` + `TAB` will cycle through your open programs' windows. While holding down `cmd`, press `tab` a couple of times to get to your desired program.

### Part 1: Setting up Atom in Terminal

2. Open up terminal through Spotlight with `cmd` + `space` and type `terminal` and press `enter`. Terminal should pop up.
2. Turn on Spectacle through Spotlight with `cmd` + `space` and type `spectacle` and press `enter`. You should see a little pair of glasses on your toolbar.
3. Go back to your root directory by typing `cd` in terminal.
4. In terminal type `cd Des` (Make sure D is capitalized) and press `tab`. This should autocomplete `Desktop` for you.
5. Type `pwd` to make sure you're in the right Desktop directory.
6. Create a new folder called "warm-up" (`mkdir warmup`).
7. `cd` into the `warmup` directory.
8. Touch an `index.html` file and a `style.css` file (`touch index.html style.css` you can touch multiple files in a single command)
9. Check if the files were made (`ls` should show the files).
10. Open up the files with atom `atom .` This command tells us to open all files in the current directory (`.`). You can also open specific files in Atom with `atom index.html` for example. After a few seconds you should see Atom is now open with the 2 files.


### Part 2: Atom Shortcuts and index.html

1. Let's open up each file in Atom. Use `ctrl` + `t`, that opens up a list of your files in this project. Type out `i` and press enter. This should open your `index.html` page now and your cursor is in the file.
2. Let's write some HTML. Type out `html` + `TAB` and voila! Boiler plate code.
3. Use your arrow keys and navigate your cursor right between `<title>` and `</title>` and type `Look Ma, No Mouse!`
4. Navigate your cursor down to line 8, between the `<body>` and `</body>` tags. Let's write our first line of code! Type `<h1>Hello World!</h1>` and **save** the file using `cmd` + `s`.
5. Navigate back to terminal (`cmd` + `TAB`) and type `open index.html`. A browser should pop up that says "Hello World!"

:beetle: Debugging tips:
  - Did you save all the files?
  - Check your syntax (punctuation, spelling, uppercase, spacing)
  - Is your file named properly?

### Part 3: Atom Shortcuts and style.css

1. Navigate back to atom. Let's set up our css file. Type `cmd` + `t` to see the list of files. You can type "css" or use the arrow keys to get to it. You should now see your style.css tab open and your cursor is in the file.
2. Let's change the body background color to `papayawhip`.
```
body {
  background: papayawhip;
}
```
3. Notice how a tiny window pops up by your cursor. You can type out the property or you can type `TAB` to autocomplete. Let's try it again and change the font-family.
4. After the `background: papayawhip` add a new line and type out `font-f` and press `TAB`. This should auto complete to `font-family`. Now write the rest: `font-family: Arial, sans-serif;`
5. Save the file (`cmd` + `s`). The little dot next the file name in the tab should disappear when the files changes are saved.
6. We still need to link up our index.html to our css page. Toggle between open files with the shortcut `ctrl` + `TAB`. This will cycle through your files. You should be in `index.html` now.
7. Use your arrow keys and create a new line after the `</title>` tag. We'll attach our style sheet here.
8. Type out `link` + `TAB` and voila! Boiler plate code. We have to change our style sheet's name though so change the `href="style.css"` instead of the default href="/css/master.css".
9. Save the file (`cmd` + `s`).

It's the moment of truth!

10. Navigate back to the browser. Refresh the page with `cmd` + `r`. Do you see the new changes? Congratulations! You don't? Retrace your steps and make sure you didn't miss a step. Be extra careful about syntax. `cmd` and `ctrl` aren't the same buttons.

## Reach Goal

### #1. Javascript

Let's keep practicing! Let's add a javascript file to the page. I won't provide the shortcuts, just the basic instructions. Remember, don't use the mouse!

  1. In this same directory create a javascript file called `script.js`.
  2. Open it up and enter `console.log("Hellooooo")`. Save it.
  3. Navigate to the `index.html`, we still have to attach our script. Right after the `<link>` tag we just created, we'll add our script tag here. Type out `script` + `TAB` and boom! There's our script boilerplate. Change the `src="script.js"`.
  4. Go back to the browser and refresh. We can see our console.log in the browser's console window with the shortcut `option` + `cmd` + `j`. You should see your message "Helloooo" on this window.

### #2. More Atom shortcuts

  Programmers are super lazy. Why do more when you can do **less**? Check out [this Atom Shortcut Cheat-Sheet](https://www.shortcutfoo.com/app/dojos/atom-mac/cheatsheet) and try out some more fancy short-cuts. You'll look like a real cool hacker pro


### #3. Spectacle

It gets annoying really fast if your windows are all over the place and you spend more time cycling through programs than you do working! Take some time and check out [Spectacle Shortcuts](https://github.com/eczarny/spectacle#keyboard-shortcuts) and you can also manually configure your windows by clicking on the little icon at the top of your screen's toolbar.

## Resources :books:

- [Command Line Shortcuts](http://imgur.com/Omz33nF)
- [Atom Shortcut Cheat-Sheet](https://www.shortcutfoo.com/app/dojos/atom-mac/cheatsheet)
- [Mac Shortcuts](https://support.apple.com/en-us/HT201236)
- [Spectacle Shortcuts](https://github.com/eczarny/spectacle#keyboard-shortcuts)

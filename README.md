# cd-Windows
A Guide to Web Dev Programming transitioning from Mac to Windows 10 Operating System

# Table of Contents
0. [A Preface](#preface)
1. [Where the heck is everything?](#where-the-heck-is-everything?)
2. [Shortcuts](#shortcuts)
3. [Git Setup](#git-setup)
4. [Text Editor](#text-editor)
5. [Node Setup](#node)
6. [Sources](#sources)

## Preface
Before we begin, I do want to cover a few caveats to using this Readme in the most effective way possible. I am by no means an expert, nerd guru or some power user building systems in the middle of their basement. I am, however, a web developer who's programmed on a Mac OSX and has had to rapidly transition to using a Windows platform. Prior to programming in Macs, I have been a Windows User so you'll see a few biases covered below. This is a collection of information I've looked over and the methods I have used to simulate a web dev environment on my personal hardware.

That being said, these may not be the best solutions. I'll always encourage you to seek out better answers and honestly if you find a better way to do this, let me know and I'll update this accordingly. We'll start off with the pros and cons of using a Windows Build System.

## Alternatives to Using Mac

You'll probably see a lot of hoopla these days about how all programmers use Macs. How they have fewer viruses, require less maintenance, are shiny, super sleek and everything with a Unix system has descended from the depths of Valhalla. And I really can't argue with that last point, switching from Terminal to the Command Prompt (more on that later) in Windows has to be one of the hardest things for me. But that aside, why wouldn't you want to use the super shiny, awesome thing?

They're also insanely expensive. Arguably you're making an investment in getting a work laptop, but if you're at a state where you're scrapped for cash, Linux and Windows is the way to go. 

Linux is open source, customizable, can create a web server easily, has the almighty Unix system and is arguably more secure. Cons, relative to Windows, are lack of application support, multiple distros, and familiarity issue.

Some problems with Windows on the other hand are the security concerns (viruses and holy cow Cortana, leave me alone), the native SSH maintenance, lack of terminal (programming without Unix compatibility sucks), the software dependency from Microsoft and the higher maintenance (you ever miss those millions of Windows Updates? No one does). However, Windows is taking steps to simulate the Unix system, their experimental [Bash on Ubuntu on Windows](https://msdn.microsoft.com/en-us/commandline/wsl/faq) is pretty great and though they're [arguably different](http://superuser.com/questions/707269/is-windows-powershell-as-powerful-as-the-terminal-of-unix-linux), [PowerShell](https://technet.microsoft.com/en-us/library/bb978526.aspx) brings some familiarity to those alternating systems.

## Where the heck is everything?
Unlike the weird omnibus of secret file storage, that's your Mac OSX, Window's makes it a little easier for you to figure out where all your applications are being stored (sort of). You'll have something called the C Drive (C:). This is the basic under the hood version of where your Applications Cache and other data chunks are stored. C:/ == MacintoshHD. When you first hit your Terminal on a Mac, your directory's listed as 

## Shortcuts

It'll take some getting used to, but the Command Key (⌘) is basically the Control Key (Ctrl), most of the equivalents for keyboard shortcuts are listed as such.

| Action       | Mac  | Windows           |
| ------------- | -----:|:-------------:|
| Cut        | ⌘ + X | Ctrl + X |
| Copy       | ⌘ + C | Ctrl + C |
| Select All | ⌘ + A | Ctrl + A |
| Paste      | ⌘ + V | Ctrl + V |
| Undo       | ⌘ + Z | Ctrl + Z |
| Print      | ⌘ + P | Ctrl + P |
| Find       | ⌘ + F | Ctrl + F |
| Find Again | ⌘ + G | Ctrl + G |
| Open       | ⌘ + O | Ctrl + O |
| Save       | ⌘ + S | Ctrl + S |
| Close Front Window | ⌘ + W | Ctrl + W  |
| Quit App | ⌘ + Q | Alt + F4  |

... You get the idea, at little less intuitive:

| Action       | Mac  | Windows           |
| ------------- | -----:|:-------------:|
| Move Between Programs         | ⌘ + Tab           | Alt + Tab |
| Print Screen                  | ⌘ + Shift + 3     | WindowsKey + PrtScr (Screenshot will be in your Pictures folder as opposed to the Desktop) |
| Search                        | ⌘ + Space         | WindowsKey + Q (Will bring up Cortana) |
| New Finder (or File) Window   | ⌘ + N             | WindowsKey + E |
| Force Quit/ Task Manager      | ⌘ + option + esc  | Ctrl + Shift + Esc |

## Git Setup

Install [Git](https://git-scm.com/download/win)

Be sure to have the right version installed for your file configuration

## Text Editor

## Sources
+ Shortcut sources
    + Translated from [Apple Shortcuts](https://support.apple.com/en-us/HT201236)
    + Thanks in part to [LaptopMag](http://www.laptopmag.com/articles/mac-users-guide-windows-10-keyboard-shortcuts)
+ Other Useful Links:
    + [Format a Hard Drive For Both Windows and Mac](http://www.laptopmag.com/articles/format-drive-for-windows-and-Mac)
    + [File Relocation](http://www.laptopmag.com/articles/move-mac-files-windows-pc)
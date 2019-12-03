# git-gui-on-windows
Which git GUI tools to use on Windows?

For simple installation and ease of use let's look at:
1. [Fork](#1-fork)
2. [GitKraken](#2-gitkraken)
3. [Sourcetree](#3-sourcetree)
4. [Eclipse-Egit](#4-eclipse-egit)
5. [Git for Windows](#5-Git-for-Windows)
6. [Git Extensions](#6-Git-Extensions)

## Introduction
You're interested in using git? You know and use Windows? You want the setup to
be as easy as running an installer and maybe a bit of configuration?

There are many tools to provide various levels of git functionality
on Windows, from replicating the CLI tools available in the Unix based
OSes to the easy to install and use GUI centric options.

Since Windows has started playing so nicely with Linux and with Microsoft's
acquisition of Github there's every chance we will see more native Windows tools
becoming available but until then:

## Update: December 2019
It's now about a year after I last updated this list and things
have changed a little, the first thing to say is I started using *Fork* and
so far it has been great and indeed has moved to the top of the list.

GitKraken as become even more demanding about licensing and while I'm sure the
tool and it's ecosystem are very good, for my purposes it has now become
irrelevant. #HowToLoseUsers

## 1. Fork
If you're after the easiest, best Git GUI client on Windows then this is it,
head to [Fork](https://git-fork.com/home) and grab the Windows installer.

This tool installs easily, has the configuration options you most often need
just a few clicks away and for those times you need to take a deeper dive into
something git has or hasn't done, the bundled console gives you all the power
you could possibly want.

There are light and dark themes:
![](images/screenshots/07-Fork.png?raw=true)

Download it, install it and get git-ing... this is the way software was meant
to be written and distributed. Thank you Dan & Tanya!

## 2. GitKraken
Unless you're prepared to jump through the licensing hoops, or desperately
need a GUI interface on Linux then I strongly recommend using *Fork*. But if
you must then here are my previous thoughts on GitKraken:

This tool from the team at Axosoft is probably the best looking and most
polished tool available, that it runs equally well on Windows, Linux and Mac
is just brilliant.

![](images/screenshots/01-GitKrakenMainScreen.png?raw=true)

It is feature and option rich, plus with a bit of digging you could make it look and
work just the way you want. It is very easy to just start using at a very
basic level and learn some of the more advanced features along the way.

You will need to create an account at
[GitKraken](https://www.gitkraken.com/git-client) and download the relevant
installer from there. I have installed and used the client on Windows, Mac and
Linux without any issues.

Probably the only negative I can aim at GitKraken is that once the product left
the beta stage and had to become commercially viable they really pushed the
licensing options. There is no licensing option that suits me. In fairness
the product has always had a free-to-use option and the licensing messages
can now be turned off. But not before it annoyed me enough to look around
at alternatives.

## 3. Sourcetree
This tool is from the Atlassian team, it seems equally easy to use and
just as comprehensive. In truth I've not used it anywhere near as much as
GitKraken but so far so good.

![](images/screenshots/02-SourcetreeMainScreen.png?raw=true)

It looks and feels like a more traditional Windows application, this might
be more to some tastes. It certainly seems good at displaying
the most important information where a Windows user would expect it.

Annoyingly you will also need to create an account at
[Sourcetree](https://www.sourcetreeapp.com/) to access the software but at least
it's free to use from there onwards. The installer will detect if you have git
installed and if you don't it will offer to download and install it for you.

The only negative I'll aim at Sourcetree is not having a Linux client. But for
now I'm treating it's Linux absence as a reason to stay CLI fit on that OS.

## 4. Eclipse-Egit
Firstly this is not a stand-alone tool and refers to Eclipse's integrated
git functionality. I've only used it on Linux and there it seems to be pretty
good. So if you already use Eclipse on Windows then start with
[Egit](https://www.eclipse.org/egit/) it might be all you need!

For beginners there is a portion of this
[guide](https://github.com/ockertbotha/java-dev-on-ubuntu#4-version-control-with-git-and-eclipse-egit)
that covers using Egit, even thought it is on Unbuntu, the Egit part should
still be relevant on Windows.

![](images/screenshots/03-EclipseEgitMainScreen.png?raw=true)

## 5. Git for Windows
For those who don't use Eclipse or who want separate access to git and don't
like being forced to register an account for it (yip looking at you GitKraken
and Sourcetree!) then consider using
[Git for Windows](https://gitforwindows.org/) it's not quite the one click
install and single integrated application but still installs pretty easily and
provides some decent GUI tools, even if they don't look as pretty as some of the
others:

![](images/screenshots/04-GitForWindows.png?raw=true)

## 6. Git Extensions
It would be remis of me at this point not to mention
[Git Extensions](https://sourceforge.net/projects/gitextensions/) this integrates
a set of pretty decent right-click accessible tools into Windows, a lot like
Tortoise did in the CVS days of yore:

![](images/screenshots/05-GitExtensionsMenu.png?raw=true)

Although it seems pretty solid, it's reliance on
[KDiff3](https://sourceforge.net/projects/kdiff3/files/) which itself seems to be
orphaned leaves you with having to fiddle a bit more. Either find a way to
change the diff and merge tool or download and install
[KDiff3](https://sourceforge.net/projects/kdiff3/files/), but once setup you do
get good functionality:

![](images/screenshots/06-GitExtensionsWindows.png?raw=true)

## Summary
There are of course more tools than this and a quick search may reveal that one
of the tools you currently use has a git plugin or equivalent, this is also an
ever changing landscape so keep up to date.

---
layout: post
title: "Learning Vim. Again."
date: 2012-03-20 22:59
categories: code tools
permalink: learning-vim
---

A few months ago I decided I would start using Vim again.  I tried switching a few times before but never stuck with it, mostly because of the abrupt changes from using Notepad++ at work and TextMate at home.

My motivation was the rather sensible Pragmatic Programmer advice about [using a single editor well]("http://pragprog.com/the-pragmatic-programmer/extracts/tips"). Vim is as ubiquitous as it gets and its presence on every Unix machine I've ever used sealed the deal over emacs.

I had tried switching to Vim with limited success before. A big help in sticking with it was a mental approach inspired by a Yehuda Katz post on [reducing friction while switching to vim]("http://yehudakatz.com/2010/07/29/everyone-who-tried-to-convince-me-to-use-vim-was-wrong/").
Using MacVim and sticking with my normal editor habits (cmd-t for new tabs, cmd-c, cmd-v, etc) was very useful - it let me resort to a lot of familiar approaches while learning some unfamiliar ones.

The problem with the 'one editor' thing is that Gvim on Windows just isn't as nice as MacVim.  Os X's apple key leaves the control key open for all the standard Vim commands like **ctrl-r** (undo) **ctrl-v** (selection) etc.  A number of these have to be remapped in Windows, which means that the whole 'one editor' thing is a bit of a fallacy.  The same goes for using the editor on a remote machine - while using vim via a console can force you to get familiar with the **h j k l** keys for directions and such, any productivity-related improvements made via the .vimrc file or plugins are missing.

Be that as it may, I'm glad I've been working with Vim.  I'm much more productive doing stuff over ssh and using the newly learned shortcuts in other places (e.g. navigating man pages, which are viewed with less, which shares a lot of commands with vim) is a big bonus.

I'm still tempted to have another try at emacs, which I last used in earnest during Networking class at college, if only because there are similar command overlaps with the rest of Unix & Os X  **ctrl-w **(delete previous word) **ctrl-y**(yank a.k.a. paste)

Verdict?  Stop pondering the perfect editor and get some work done :)  Oh, and try Vim for a while - even if you don't stick with it, the things you pick up will make you more proficient working over ssh or browsing a man page.

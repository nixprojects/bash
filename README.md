# bash

This repo will feature projects I'm working on related to bash scripts. Right now, the book I'm currently working with is ["Wicked Cool Shell Scripts"](http://www.amazon.com/Wicked-Cool-Shell-Scripts-Taylor/dp/1593270127/ref=sr_1_1?ie=UTF8&qid=1455693190&sr=8-1&keywords=wicked+cool+shell).

As you'll see, I'm going to be going over the basics in a lot of ways as well and explaining things that I and others already know, if not also just to help commit things to memory for myself as well.

### inpath.sh

Basically, this is just a simple script that verifies whether or not a specific program/script is within a user's $PATH (set in your bash profile, usually ~/.bash_profile, ~/.bash_login, or ~/.profile).

For those who don't know (although I'm sure almost everyone knows this on Github), when a program is accessible within your PATH, that allows you to run the program just by typing its name from any directory location rather than actually having to specify the full path of the file/program itself.

Reminder: If you add new paths to your profile, you'll have to log out and back in to ensure the change is recognized by the system.

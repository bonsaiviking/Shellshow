Upstream url: http://suso.suso.org/xulu/Shellshow

This is a program Mark Krenz wrote the week before
[Indiana Linux Fest 2012](http://www.indianalinux.org/) for his
[@climagic](http://www.climagic.org/) presentation. It allows you to pass
textfile filenames as arguments and then display the files in slideshow fashion
in the terminal emulator window with various transitions (wipes) in between
them. It is currently written in Perl and doesn't require any special libraries
to run.

You will probably want to run it locally because it can consume a fair amount
of bandwidth to perform some of transitions. 

Installation
============

Just make the program executable and if you want, put it somewhere in your path.

    chmod a+x shellshow

Usage
=====

I'd recommend using a terminal with white text on black non-transparent
background for using the fadeout/fadein transition.

    ./shellshow file1 file2 file3 file4 ....

Once started, use one of the following keys to move between the frames in
various ways:

* SPACE, ENTER = Forward, full frame slide transition
* BACKSPACE, 'b' = Backward, full frame slide transition
* l = Forward, slide line by line transition
* k = Backward, slide line by line transition
* f = Forward, fade out/in
* d = Backward, fade out/in 
* ] = Move forward without transition
* [ = Move backward without transition

Feedback
========

If you use this script, the author would be curious to know for what and how
it went. You can e-mail him at deltaray#slugbug#org. Thanks.

Author's Future Plans
=====================

Probably rewrite this in C and make it easier for other developers to jump in
and make transitions/wipes of their own. 

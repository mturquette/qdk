# qdk 2.2.2

The QNAP QDK is used for packaging and installing pre-built binary
packages for the QNAP line of network attached storage devices. qpkg is
their custom packaging format, because the many existing binary
packaging standards were apparently not good enough. The qdk is licensed
under the GNU Public License version 2 (see COPYING).

## qpk format

See [this pdf](http://forum.qnap.com/download/file.php?id=4851) cleverly
wrapped in a zip file and version-controlled via a stickied forum post for some
explanation of the packaging format.

I extracted the qdk files manually by inspecting the shell script packed
onto the front of the qdk qpkg. For more info on how this was done see
[this blog
post](http://deferred.io/posts/qnap-qdk-qpkg-and-the-gpl/).

## filing bugs

Please file all bugs on the QNAP forums: http://forum.qnap.com/

## why host this code on github?

I do not maintain the qdk nor do I use it. I posted the source to github
because it is GPL licensed and I could not find the source code easily
available anywhere. The only way to get the source is to install the qdk qpkg.
It is a bootstrapping problem: to install the qdk you need the qdk installed.
This possibly constitues a GPL violation and it seriously annoyed me, hence
this github project.

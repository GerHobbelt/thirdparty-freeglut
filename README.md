FreeGLUT
========

This readme file applies to the git clone of FreeGLUT's svn repo on [sourceforge.net](http://freeglut.sourceforge.net/) that is hosted on [github](https://github.com/dcnieho/FreeGLUT). This is provided here to enable user to contribute easier.

Every effort is made to ensure that the ``git_master`` branch only progresses in a fastforward manner, but complete guarantees cannot be given as the [sourceforge.net trunk](https://sourceforge.net/p/freeglut/code/HEAD/tree/) is at all times leading.

I will be unable to merge a pull request if the github clone is behind ``svn/trunk`` on sourceforge.net. Should you detect this, please contact me, maybe through making an issue here on github.

This copy of the svn repository was not created with ``git svn`` but with the excellent svn support of [SmartGit](http://www.syntevo.com/).


Notes to self on how to work with this:
 Basic workflow upon receiving a pull request is as follows:
- Merge pull request on github
- pull in changes to my local clone of the ``git_master`` branch.
- cherry pick the merged commits onto my local clone of the ``svn/trunk`` branch
- push these commits to svn remote (this alters the commits in the local 
  ``svn/trunk`` clone as extra meta data is added)
- merge ``svn/trunk`` into local ``git_master``
- push merge commit to github (its fast forward!)


-------------------------------------------------------------------------------------------------------------


freeglut
========

BRIEF OVERVIEW
--------------

This is the freeglut package.

Freeglut, the Free OpenGL Utility Toolkit, is meant to be a free alternative to
Mark Kilgard's GLUT library. Freeglut is free software, distributed under an
MIT/X11 style license. You are free to use, modify, and redistribute FreeGLUT
with or without modifications (see COPYING for details).

PORTS
-----

Currently supported platforms:
 - UNIX systems with X11 and Wayland (such as GNU/Linux, FreeBSD, etc)
 - MS Windows
 - MacOS X with XQuartz (no native Cocoa support yet)
 - Android (NDK)
 - BlackBerry

Consult the platform-specific readme files for details on the level of support
and build instructions.


INSTALLATION
------------

See README.cmake as a starting point, as well as the other README
files for further info.


CONTRIBUTING
------------

Patches and pull requests for bugfixes and new features are certainly welcome.
Please send patches to the freeglut-developer mailing list (see CONTACT below).

Feel free to report any bugs you encounter, using the github *issues* system.

Older bug reports and feature requests are still reachable on:
  - https://sourceforge.net/p/freeglut/bugs/
  - https://sourceforge.net/p/freeglut/feature-requests/

But you are encouraged to use github issues for new ones.

Alternatively you can also send bug reports and feature requests to the
freeglut-developer mailing list if you prefer. Extended discussions about new
features and design issues for large contributions, are best suited to the
mailing list.


CONTACT
-------

FreeGLUT website: http://freeglut.sourceforge.net

FreeGLUT mailing lists:
 - developer: https://lists.sourceforge.net/lists/listinfo/freeglut-developer
 - bugs: https://lists.sourceforge.net/lists/listinfo/freeglut-bugs
 - announce: https://lists.sourceforge.net/lists/listinfo/freeglut-announce

  You need to subscribe before posting to any of our mailing lists. Make sure
  to avoid selecting "daily digest mode" if you intend to post, so that you can
  reply properly to specific messages. Also, please do not top-post, and try to
  send properly formated emails (text, hard-wrapped at 72 columns, no binary or
  large attachements).

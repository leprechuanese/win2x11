win2x11 Version 0.0.1
Convert a native windows cursor theme to
a X11 native cursor theme.


Author: ese (irc.freenode.net ##freebsd-es,#freebsd)

I provide 2 list of filenames, list.x11 and list.windows in hope
to get a complete filename equivalent of cursors and icons
used in windows and x11, please modify the file 'list.filename'.

If you know the missing filenames between X11 and Windows files,
from 'list.filename' please edit/modify the file by:
cursor-name-x11-filename<tab>cursor-theme-windows-filename<tab>Description

The script uses 'list.filename' to make comparations and renames
the files as need it, we like to cover all the filenames soon!

Please send me a email to leprechuanese@gmail.com with your changes,
Thanks for your help!

You can find me at:
irc.freenode.net ##freebsd, #freebsd
nicks: ese leprechuanese

Helpful tips.

To convert .cur to .png use:
for i in *.cur; do convert icon:$i $i.png; done

howto compile
gcc ani2ico.c -o ani2ico

run:

./any2ico file.ani



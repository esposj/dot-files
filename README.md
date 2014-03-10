dot-files
=========
My collection of dot files.

Tmux
====
Overview
--------
The goal is to be able to cycle through windows on a remote host while keeping a 3 pane set with the 2 local panes fixed. It is cobbled together from 'Tmux: Productive Mouse Free Development' by Brian Hagan. It uses C-a for the local prefix and C-b for the remote prefix. It uses 'reattach-to-user-session' for clipboard integration (https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard/blob/master/README.md).  Most movement and resize keys are bound to vi-like keys.  Splits are bound to - and | per Hagan.

Installation
------------
If using OSX, install reattach-to-user-namespace (https://github.com/ChrisJohnsen/tmux-MacOSX-pasteboard/blob/master/README.md).  I did this via homebrew.

To use link the appropriate file to ~/.tmux.conf


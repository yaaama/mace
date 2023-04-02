<<<<<<< HEAD
# mace is a simple emacs wrapper

I made this script in order to make life easier for myself.
I was tired of having to type in emacsclient and having to kill the daemon and restart it all manually so I made mace to make it much easier.

Execute `mace -h` to get a list of options.

I will add to this script when I need to, but it will remain a simple program.

=======
# mace
Simple shell wrapper script for Doom Emacs, Emacsclient and the daemon.

## What is it for?

I made this script to easily start up the emacs daemon, restart it, perform doom commands and just make it easier to open up emacsclient in either terminal or gui mode.

Please note that you will need dunst in order to recieve a notification for when the daemon has restarted.

## Options

No command: Will open emacs as a client after ensuring the daemon is active.

-sr: Will restart emacs server.

-du: Will upgrade doom packages.

-ds: Will do "doom sync".

-t: Will open emacs in terminal mode.

-g: Will open emacs in GUI mode.

-h: Prints out available commands.
>>>>>>> origin/master


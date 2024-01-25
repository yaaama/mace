<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-refresh-toc -->
**Table of Contents**

- [mace](#mace)
- [What is it for?](#what-is-it-for)
- [Options](#options)

<!-- markdown-toc end -->



# mace

**"mace"** is a simple shell script for interacting with `doom emacs`, `emacsclient` and the emacs daemon.

I will add to this script when I need to, but it will remain a simple program.



# What is it for?

I made this script to easily start up the emacs daemon, restart it, perform doom commands and just make it easier to open up emacsclient in either terminal or gui mode.

Please note that you will need dunst in order to receive a notification for when the daemon has restarted.


# Options

-   Execute `mace -h` to get a list of options.
-   Running the script without a specified option (`mace`) will create start the daemon if one is not running, and then open a new frame connected to the daemon.

-   `-sr`   Restarts the emacs daemon (after saving all buffers). A notification sent once done. 
-   `-t`    Opens emacs in terminal mode. It will not connect to the daemon. 
-   `-g`    Opens emacs in GUI mode. It will not connect to the daemon. 
-   `-h`    Prints out available commands.
-   `-deb`  Starts emacs with `--debug-init` flag. It will not connect to the daemon. 
-   `-du`   Alias for `doom upgrade`. 
-   `-ds`   Alias for `doom sync`.
-   `-dsu`  Alias for `doom sync`.
-   `-db`   Alias for `doom build`.
-   `-dp`   Alias for `doom purge`.
-   `-dd`   Alias for `doom doctor`.


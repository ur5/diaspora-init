= Init script for Diaspora

This is an init script that starts Diaspora's server/script
as a daemon.

To configure the script, please edit the variables at the
beginning of it.

To install it, copy it under /etc/init.d and make sure it's
executable.

Also make sure that the appropriate symlinks are in place.

WARNING: The stop function kills every ruby process. This is a
nasty hack, but this is it for now. I'm happy to receive
pull requests ;)

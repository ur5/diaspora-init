# Init script and upstart configs for Diaspora

This is an init script / upstart config that starts Diaspora's
services (unicorn & sidekiq)

To configure the script, please take a look at the files and
change the variables you need.

To install the init script, copy the file init/diaspora under
/etc/init.d and make sure it's executable.

To install the upstart configuration files, just copy
everything from upstart/ to /etc/init/ .

I'm happy to receive pull requests ;)

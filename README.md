## Enemy Space docker development environments

When started `docker-compose` looks for 'localunixsocket.<domain>' where `domain` can be 'local' or whatever you're network assigns to your machine.

Update your `/etc/hosts` file:

    127.0.0.1 localhost localunixsocket.local localunixsocket.enemy.space localunixsocket.entpub.local

It's not entirely necessary to do so but it takes a while to come up otherwise.
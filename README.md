ssh-askpass
===========

ssh-askpass for OS X. Works in (at least) 10.7+ (including Yosemite)

Used to accept (or deny) the use of the private key(s) added to the SSH authentication agent with `ssh-add -c`.

![Screenshot](https://github.com/theseal/ssh-askpass/raw/master/sample/ssh-askpass.png)

## Installation

    $ sudo ln -s $PWD/ssh-askpass /usr/libexec/ssh-askpass
    $ chmod +x /usr/libexec/ssh-askpass

## Enabling keyboard navigation
For security reasons ssh-askpass defaults to cancel since it's too easy to
press spacebar and accept a connection or other actions which might use
ssh-keys. To make it easier to press `OK`:

* Go to `System Preferences` and then `Keyboard`.
* Under the `Keyboard` tab, click on `All controls`.

Now you can press ⇥+spacebar to press `OK`.

## License
ISC license

## Contributors
[theseal](https://github.com/theseal)
[simmel](https://github.com/simmel)

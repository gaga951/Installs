Debian and Ubuntu based Linux distributions
Node.js binary distributions are available from NodeSource.

https://github.com/nodesource/distributions/blob/master/README.md


Node.js v16.x:

# Using Ubuntu
$ curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
$ sudo apt-get install -y nodejs

# Using Debian, as root
$ curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
$ apt-get install -y nodejs


if error

You might be having obsolete source PPAs. Remove every other apt sources:

$ sudo rm -rf /var/lib/apt/lists/*
$ sudo rm -rf /etc/apt/sources.list.d/*
$ sudo apt-get update


and try again

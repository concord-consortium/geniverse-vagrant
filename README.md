# Getting Started
This project lets you use vagrant to run CC's geniverse software.

## Prerequisites
First, you'll need to have the following installed:

### VirtualBox

You can install the latest from http://www.virtualbox.org/

### Ruby

You can install the latest from http://www.ruby-lang.org/.
1.8.7 and 1.9.2 are both known to work.

### Rubygems

You can install the latest from http://rubygems.org/

### Vagrant gem

You can install the latest via:

    gem install vagrant

## Firing it up

Check out this project with git

From within the project directory, simply run:

    vagrant up

Vagrant will handle configuring the virtual machine, checking out the
code, and configuring the code. By default, the code
will end up in the _vagrant_ directory of this project, and you
can access the web interface at http://localhost:4567/.

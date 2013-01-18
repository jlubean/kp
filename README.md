kp
==

kp stands for "kill processes" and is a shell script that can be used to kill 
all processes that have a particular word in the command used to initiate them.

###Installation
===============

* Install kp script to [install_dir]
* cd [install_dir]
* chmod u+x kp
* Add [install_dir] to your PATH env. var.

###Usage
========

kp [key_word]

###Example
==========

$ kp node
Are you sure you want to kill 3 node processes [yes|no|List]? l
my-linux   5023     1  0 12:10 pts/1    00:00:00 node app
my-linux   5024     1  0 12:10 pts/1    00:00:00 node /usr/local/bin/http-server -p 7000
my-linux   5025     1  0 12:10 pts/1    00:00:00 node /usr/local/bin/http-server -p 5000
Are you sure you want to kill 3 node processes [yes|no|List]? y
[sudo] password for my-linux:
Killed 3 processes.




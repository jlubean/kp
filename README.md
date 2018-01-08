# kp

kp stands for "kill processes" and is a shell script that can be used to kill 
all processes that have a particular word in the command used to initiate them.

## Installation

* Install kp script to [install_dir]
* cd [install_dir]
* chmod u+x kp
* Add [install_dir] to your PATH env. var.

## Usage

kp [key_word]

## Example

```
$ kp my-proc
Are you sure you want to kill 2 my-proc processes [yes|no|List]? l
  501 97558 26789   0 Thu06AM ??         28:18.50 my-proc foo 
  501 97559 26789   0 Thu06AM ??          1:49.84 my-proc foo 
Are you sure you want to kill 3 node processes [yes|no|List]? y
[sudo] password for my-laptop:
Killed 3 processes.
```

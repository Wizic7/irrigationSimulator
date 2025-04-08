## Overview

**Irrigation Simulator**:

**An Erlang App**:

**My goal is to make a Erlang threded system using gen_servers and gen_statem**:

## Instructions for Build and Use

Steps to build and/or run the software:

1. Get a Linux compatible machine
2. Make sure that Erlang is installed with erl
3. run rebar3 shell to open up a shell

Instructions for using the software:

1. Pick a module to run, then use the modulename:functionname format to call a function.
2. irrigation_top_sup:start_link(). is a good place to start as it will launch the modules underneath it.

## Development Environment 

To recreate the development environment, you need the following software and/or libraries with the specified versions:

* You need a VM to connect over WSL if you are using Windows.
* Then get your file to the VM and run it.

## Useful Websites to Learn More

I found these websites useful in developing this software:

* [Elang Docs](https://www.erlang.org/docs)


## Future Work

The following items I plan to fix, improve, and/or add to this project in the future:

* I plan to add visualization of the irrigatiors running.
* With that I might add buttons to execute commands.
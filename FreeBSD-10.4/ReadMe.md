*Functional box with caveat*
The Vagrant script fails to process the line `source /root/erlang/R16B02-basho10/activate.csh` so Erlang is not initialised. If you login to the box with `vagrant ssh` and run the command manually, it works fine. After that, simply run the remaining commands to compile Riak and you should be good.

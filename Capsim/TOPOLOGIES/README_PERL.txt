
Use the perl script ber.pl to generate BER for a QPSK digital communication
link for various noise levels.
First erase ecount.dat.
Then run:

  perl ber.pl

Note that the perl script uses the topology template:
     sys-ete-ber.template 
To create the "temp.t" topology which is run in capsim in batch mode:
     ../capsim temp.t

After each run, ecount.dat is apended with the new BER info.




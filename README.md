# RNA in Snort

This repository hosts my Completion of Course Work at my College where I added a Neural Network support in Snort to detect attacks coming from the network.

It was an important work to me.
Using this work, one person can create any Neural Network on [JavaNNS](http://www.ra.cs.uni-tuebingen.de/software/JavaNNS/manual/JavaNNS-manual-1.html)[2](https://github.com/mwri/javanns), export it to C and use it in [Snort](https://www.snort.org/).

The idea was to train the Neural Network on the network baseline (common traffic) to run it in production to detect anomalies.

It was hosted in my website in the past.
Now it's here for the idea doesn't go away and someone can use it if it's useful.

Contents:
* [Completion of Course Work](TCC.pdf) (It is in Portuguese)
* [App to create the Neural Newtork (JavaNNS)](JavaNNS)
* [Software to convert from JavaNNS to C](snns2c)
* [Snort IDS code](snort)

Some time after finish this work, I see the better way is to create a Snort's plugin.

But I did not have this information and enough material to know it that time...

So... have fun! =)

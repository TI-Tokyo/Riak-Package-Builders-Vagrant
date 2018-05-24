*Non-functional box*
Currently having issues compiling Erlang as it claims it is missing the files necessary for crypto.

*Fixed*
Debian Stretch needs libssl1.0-dev rather than libssl-dev. However, Kerl complains that libssl-dev is missing so it can't build despite the fact that it actually can. I was foolishly cancelling the build because of this message instead of letting it run its course.

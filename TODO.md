# TODO:

Problems and thoughts related to Skynet.

## Chain Labelling

* Right now, if the word "in" is a cue word, and "in" is in an argument, the argument will break.  We need to look at performing multiple iterations over a phrase and find a "best" fit.
  * We could increase our training set size.  During training keep a count of is it in an argument and location in the string.
  * Pass to a better labelling system.

## DumbDown

* Currently, certain root words aren't going to the same root.  For instance 'probable' and 'probably'.
  * Look at implementing Porter2 or another stemming algorithm.
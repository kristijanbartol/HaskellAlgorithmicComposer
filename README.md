Haskell Algorithmic Composer
----------------------------
This project is inspired by Paul Hudak's Haskell School of Music book.
http://haskell.cs.yale.edu/?post_type=publication&p=112

An initial version should generate music algorithmically as explained
and shown in the book. Examples are copied one by one from the original repo
(https://github.com/Euterpea/Euterpea/tree/master/Euterpea/Examples).

The idea is to use these and other generators to generate various
examples for the analysis. The examples can be represented as images so
the image analysis can be done. With possible great amount of data
generated, machine learning techiques could be applied to classify
images and it can be expected that similar music will be in the same
categories. If this turns out to be possible to make, then there's
a playground for music / image conversion and analyses.

Additionally, this is all going to be done in Haskell to make it
more challenging and a lot more interesting! :)

How to run the examples?
-----------
- cabal
- cabal -> Euterpea
- Timidity++ (run it as "/usr/bin/timidity -Os -iA &" if you run into problems with timidity)


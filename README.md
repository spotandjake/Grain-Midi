# Grain-Midi
A Basic Midi Parser Written In grain-lang


This is a library that can be used it covers 99% of the midi spec, this is useful for tooling working with midi, This library provides a very basic parser for midi It doesnt fully parse controller messages these are just given as their index's but future functionality could be added. Notes are also not parsed by default just their numbers but the library does provide a `parseNote` api that can be used to convert any given noteNumber into its `octave` and `music note`.

This library has not been fully tested so no guarantees on correctness.

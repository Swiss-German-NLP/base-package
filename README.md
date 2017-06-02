Base Package
============

Base package for upcoming swiss-german nlp sources.


# Structure

The source will be placed in the `/data`-folder, in order to separate it from the code.


# Info

A Package can build multiple things, such as: 
- wordlist 
- POS
- NER
- all

This list will expand in the future.


# Build results

Here is a short description of the build-types.

## wordlist:

This build will generate a `wordlist.txt`-file, which contains a list of words (one word per line), that can be used for a dictionary.

## POS:

This build will generate a `pos.txt`-file, which contains a pair/tuple/dictionary of a word and a tag, divided by a slash (`/`). 
e.g. `Chäschüechli/N`

For other type of words, see "[A Universal Part-of-Speech Tagset](http://www.nltk.org/book/ch05.html#a-universal-part-of-speech-tagset)".

## NER:

This build will generate a `ner.txt`-file, which contains a pair/tuple/dictionary of a word and a tag, divided by a slash (`/`).
e.g. `Wilhelm Tell/PERSON`

For other type of entities, see "[Named Entity Recognition](http://www.nltk.org/book/ch07.html#named-entity-recognition)".

## all

Builds all available builds.


# Distribution

When creating a package, fork this repository or create a new, with the contents of this repository.

This repository serves as a base template for sources.

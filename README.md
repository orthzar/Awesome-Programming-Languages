# Awesome-Programming-Languages

In no particular order:
* Lisp
* Smalltalk
* Self
* Dylan
* ML (Meta Language)
* Prolog

Each of these languages have incredible lessons to teach, but the lessons remain obscure because many programmers never dive deep into these languages.

All of the programming languages in this repository have open source implementations. Most have production-ready implementations, but a few (Self and Dylan) have implementations which are probably not suitable for use in production. Nevertheless, each language has a working implementation that you can run on modern systems.

## Lisp

Lisp is a *big* family of languages, the two most prominent of which are Common Lisp and Scheme. Lisp is the oldest family of languages in this repo, having it's beginnings in a 1959 paper by John McCarthy. To say that Lisp has influenced programming languages is like saying that the Roman Empire affected human history; it's hard to overstate.

A lot of people dismiss Lisp because it involves typing a lot of parentheses. This is unfortunate, as Lisp, especially the two mentioned below, have a lot to offer programmers. That being said, the parentheses are there for a good reason: Lisp code is data.

Be warned that there are a lot of toy Lisp implementations, which provide little of the benefits of the mature Lisp implementations. Just about everyone who learns about Lisp is tempted to write their own Lisp interpreter. But that task rarely teaches the lessons that Lisp has to offer. If learning is your goal, then stick with a mature Lisp implementation.

### Common Lisp

Common Lisp a Lisp dialect, which has very mature implementations. When someone says "Lisp", there's a good chance they are refering to Common Lisp, because it was created to standardize features from several Lisp implementations of the 70s and 80s, chiefly Maclisp (no relation to Apple). The result is a language which has a lot of expert thought put into it's design. The specification for Common Lisp was last changed in 1994. The result is that many current Common Lisp implementations have over 30 years of development behind.

SBCL (fast, cross-platform)
CCL (fast, runs on x86 (32 bit), has an integrated MacOS GUI)
ECL (embeds in C/C++ code, and can compile Common Lisp to C code)

There are numerous books on Common Lisp:
https://gigamonkeys.com/book/

The recommended way to develop Common Lisp is to use SLIME via Emacs. SLIME is flexible and powerful.

https://en.wikipedia.org/wiki/Common_Lisp

### Scheme

Scheme is a sub-family of Lisp, which was intended to be smaller and simpler than Common Lisp.

https://en.wikipedia.org/wiki/Scheme_(programming_language)

## Smalltalk

Smalltalk is a family of languages, which has influenced the design of almost every object-oriented programming language (except C++, as Alan Kay has said).

The foundational idea behind Smalltalk is that everything is an object and that objects communicate by passing messages.

https://en.wikipedia.org/wiki/Smalltalk

## Self

Self is a language deeply inspired by Smalltalk. There is only one implementation of Self.
Self began at Xerox PARC in 1986; it's development moved to Sun Microsystems in 1995.

https://selflanguage.org/

## Dylan

Dylan is a language which could be described as Common Lisp with ALGOL syntax, and some Scheme mixed in too.

https://en.wikipedia.org/wiki/History_of_the_Dylan_programming_language
https://opendylan.org/

## ML (Meta Language)

ML is a family of languages, the most prominent of which are Ocaml and Standard ML.

### Ocaml

https://ocaml.org/

### Standard ML

https://en.wikipedia.org/wiki/Standard_ml

## Prolog

Prolog is a family of languages, which are based on declaring relationships and querying those relationships.

https://en.wikipedia.org/wiki/Prolog

## Why isn't X language in this list?

TBD, but the beginning of the topic is related to these concepts:
https://en.wikipedia.org/wiki/Turing_tarpit
https://en.wikipedia.org/wiki/Greenspun%27s_tenth_rule

## Why aren't these languages more popular?

TBD

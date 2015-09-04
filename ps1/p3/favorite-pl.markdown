My favorite programming language is Haskell, and the reason is because it
excels at one particular thing above all other programming languages:
_refactoring_.

After you modify a core function, embedded within a core library, upon which
the rest of your system depends through possibly hundreds of code paths, I ask
you this: how much work does it take for you to gain confidence that everything
didn't just break? Haskell is best in show in this metric.

There are two ways we gain confidence in our programs: type-checking and
testing. Type-checking is an _automated_ technique that _verifies_ a _simple_
property for _all_ possible inputs of a program, while testing is a _manual
effort_ technique that _increases confidence_ in a _complex_ property for
_some_ possible inputs of a program. Neither approach is enough on its own; to
be sure your program won't break you need to be using the very best tools for
each. Haskell has the worlds best type checker and industry strength testing
libraries. Refactoring in Haskell is a easy [@haskell:sotu:maintenance].

Haskell is great for _prototyping_. Hacking up a new system can be done quickly
and reliably in Haskell because the compiler catches most of the "stupid"
errors that come from writing lots of new code and fiercely editing existing
code.

Haskell is great for _growing your prototype_ into a stable system. Integrate
unit tests, whole-program tests, dependent types that statically prove array
bound checks, benchmark suites, etc. Start a small project, rapidly iterate and
solidify it into a mature project, and use a language that shines every step of
the way.

Haskell has a lot more going for it than being a great language for putting
ideas into code. Haskell has competitive performance and a thriving community
with a vast library ecosystem [@haskell:hackage]. Haskell is attractive both to
academics who enjoy the ability to write code that looks like math, and to
systems hackers who like to build robust programming abstractions. Facebook
uses Haskell in production [@haskell:haxl].

I use Haskell because I find it enjoyable and because I like having a language
that checks my work. Compilers are software and they should be automating as
much work for you as possible. I use Haskell because the language is rapidly
improving, and that gives me confidence as a long-term user. I use Haskell
because Haskell, or one of its children, will be the future of programming.

# Sum Of Multiples

Write a program that, given a number, can find the sum of all the multiples of particular numbers up to but not including that number.

If we list all the natural numbers up to but not including 20 that are
multiples of either 3 or 5, we get 3, 5, 6 and 9, 10, 12, 15, and 18.

The sum of these multiples is 78.

Write a program that can find the sum of the multiples of a given set of
numbers.

This exercise is currently under revision.
You are still free to do this exercise and submit solutions.
Depending on whether this track has been updated recently,
the tests may differ between this track and other tracks.

In most tracks, the set of numbers must be explicitly provided.
In some other tracks, if no set of numbers is given, it defaults to 3 and 5.
We would like all tracks to require the set of numbers be explicit.

If you would like to help out, please join us at
https://github.com/exercism/x-common/issues/198.

## Getting Started

Make sure you have read [the C++ page](http://exercism.io/languages/cpp) on
exercism.io.  This covers the basic information on setting up the development
environment expected by the exercises.

## Passing the Tests

Get the first test compiling, linking and passing by following the [three
rules of test-driven development](http://butunclebob.com/ArticleS.UncleBob.TheThreeRulesOfTdd).
Create just enough structure by declaring namespaces, functions, classes,
etc., to satisfy any compiler errors and get the test to fail.  Then write
just enough code to get the test to pass.  Once you've done that,
uncomment the next test by moving the following line past the next test.

```C++
#if defined(EXERCISM_RUN_ALL_TESTS)
```

This may result in compile errors as new constructs may be invoked that
you haven't yet declared or defined.  Again, fix the compile errors minimally
to get a failing test, then change the code minimally to pass the test,
refactor your implementation for readability and expressiveness and then
go on to the next test.

Try to use standard C++11 facilities in preference to writing your own
low-level algorithms or facilities by hand.  [CppReference](http://en.cppreference.com/)
is a wiki reference to the C++ language and standard library.  If you
are new to C++, but have programmed in C, beware of
[C traps and pitfalls](http://www.slideshare.net/LegalizeAdulthood/c-traps-and-pitfalls-for-c-programmers).

## Source

A variation on Problem 1 at Project Euler [http://projecteuler.net/problem=1](http://projecteuler.net/problem=1)

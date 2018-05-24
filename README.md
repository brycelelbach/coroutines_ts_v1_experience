[The C++ Coroutines TS v1, ISO/IEC TS 22277](https://wg21.link/N4736), was
published on 12-05-2017.

Implementations
===============

Two major C++ implementations have had support for the TS for over a year:

* MSVC (since version 2015 SP2 in 2016).
* LLVM (since version 5 in 2017).
* EDG frontend (since 2015).

Libraries
=========

In addition to implementation experience, the Coroutines TS v1 has seen a lot of
usage experience:

Coroutines TS v1 libraries:

* [CppCoro](https://github.com/lewissbaker/cppcoro)
* [coronet](https://github.com/ericniebler/coronet)
* [ranges-coroutines](https://github.com/toby-allsopp/ranges-coroutines)
* [concurrencpp](https://github.com/David-Haim/concurrencpp/blob/master/concurrencpp.h)

Libraries with Coroutines TS v1 support:

* [HPX](https://github.com/STEllAR-GROUP/hpx) [(details)](https://github.com/STEllAR-GROUP/hpx/blob/master/hpx/lcos/detail/future_await_traits.hpp)
* [Folly](https://github.com/facebook/folly) [(details 0)](https://github.com/facebook/folly/blob/master/folly/Optional.h) [(details 1)](https://github.com/facebook/folly/blob/master/folly/Expected.h ) [(details 2)](https://github.com/facebook/folly/blob/master/folly/futures/Future.h)
* [Ranges v3](https://github.com/ericniebler/range-v3) [(details)](https://github.com/ericniebler/range-v3/blob/master/include/range/v3/experimental/utility/generator.hpp )
* [RxCpp](https://github.com/ReactiveX/RxCpp/blob/master/Rx/v2/src/rxcpp/rx-coroutine.hpp) [(details)](https://github.com/ReactiveX/RxCpp/blob/master/Rx/v2/src/rxcpp/rx-coroutine.hpp)
* Just::Thread Pro

Coroutine TS v1 emulation layers:

* [co2 (C++14)](https://github.com/jamboree/co2)
* [CppAsync (C++11)](https://github.com/vmilea/CppAsync)

Coroutines TS v1 examples and demos:

* [mditerator (Bryce Adelstein Lelbach)](https://github.com/brycelelbach/mditerator)
* [await (Kirk Shoop)](https://github.com/kirkshoop/await)
* [coroutine_monad (Toby Allsopp)](https://github.com/toby-allsopp/coroutine_monad)
* [coroutine_func (Toby Allsopp)](https://github.com/toby-allsopp/coroutine_func)

Writing
=======

A number of blog posts have been written about the Coroutines TS v1:

* [Ranges, Coroutines, and React: Early Musings on the Future of Async in C++ (Eric Niebler)](http://ericniebler.com/2017/08/17/ranges-coroutines-and-react-early-musings-on-the-future-of-async-in-c/)
* [My First Coroutine (Kiit Saelensminde)](https://kirit.com/How%20C++%20coroutines%20work/My%20first%20coroutine)

Talks
=====

Many talks have been given at major C++ conferences about the Coroutines TS v1:

* [await 2.0: Stackless Resumable Functions (Gor Nishanov, CppCon 2014)](https://www.youtube.com/watch?v=KUhSjfSbINE)
* [Coroutines for App and Library Developers (Gor Nishanov, C++Now 2015)](https://www.youtube.com/watch?v=proxLbvHGEQ)
* [C++ Coroutines: A Negative Overhead Abstraction (Gor Nishanov, CppCon 2015)](https://www.youtube.com/watch?v=_fu0gx-xseY)
* [An Introduction to C++ Coroutines (James McNellis, Meeting C++ 2015)](https://www.youtube.com/watch?v=YYtzQ355_Co)
* [Asynchrony and Coroutines (Grigory Demchenko, Meeting C++ 2015)](https://www.youtube.com/watch?v=SbaLI2ZcyY0)
* [An Introduction to C++ Coroutines (James McNellis, Italian C++ Conference 2016)](https://www.youtube.com/watch?v=71SgFjQn4Aw)
* [An Introduction to C++ Coroutines (James McNellis, CppCon 2016)](https://www.youtube.com/watch?v=ZTqHjjm86Bw)
* [C++ Coroutines: Under the Covers (Gor Nishanov, CppCon 2016)](https://www.youtube.com/watch?v=8C8NnE1Dg4A)
* [Putting Coroutines to Work With the Windows Runtime (Kenny Kerr and James McNellis, CppCon 2016)](https://www.youtube.com/watch?v=v0SjumbIips)
* [Coroutines and C++ DSLs for Human Scale Concurrency (Dominic Robinson, ACCU 2017)](https://www.youtube.com/watch?v=d76cJ_RBGbY)
* [Multidimensional Iterators Bryce Adelstein Lelbach, C++Now 2017)](https://www.youtube.com/watch?v=EVGenON6p9g)
* [Concurrency, Parallelism and Coroutines (Anthony Williams, CppCon 2017)](https://www.youtube.com/watch?v=JvHZ_OECOFU)
* [Coroutines: What Can't They Do? (Toby Allsopp, CppCon 2017)](https://www.youtube.com/watch?v=mlP1MKP8d_Q)
* [Naked Coroutines Live (Gor Nishanov, CppCon 2017)](https://www.youtube.com/watch?v=UL3TtTgt3oU)


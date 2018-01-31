# correct_cpp_hello

Branch|[Travis CI](https://travis-ci.org)|[Codecov](https://www.codecov.io)
---|---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/correct_cpp_hello.svg?branch=master)](https://travis-ci.org/richelbilderbeek/correct_cpp_hello)|[![codecov.io](https://codecov.io/github/richelbilderbeek/correct_cpp_hello/coverage.svg?branch=master)](https://codecov.io/github/richelbilderbeek/correct_cpp_hello/branch/master)

[Correct C++](https://github.com/richelbilderbeek/correct_cpp) chapter 'Hello'.

## Goal

 * Understand [how this course works](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/how_this_course_works.md)

## Prerequisites

 * Have created [your 'Correct C++' scoreboard](https://github.com/richelbilderbeek/correct_cpp_scoreboard)

## Exercise

Write any program that is correct. 

Feel free to just copy-paste this code to `main.cpp`:

```c++
/// This program does exactly nothing
int main() {}
```

Note the `///`, which indicates a [Doxygen](https://github.com/richelbilderbeek/cpp/blob/master/content/CppDoxygen.md) [documentation](https://github.com/richelbilderbeek/cpp/blob/master/content/CppDocumentation.md) comment.

This is [how this course works](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/how_this_course_works.md):

  1. Login to [GitHub](https://github.com/)
  2. Fork this repository. See [fork a chapter](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/fork_a_chapter.md) for help
  3. Activate Travis CI for your GitHub. See [activate](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/activate.md) for help 
  4. Clone your fork. See [clone your fork](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/clone_your_fork.md) for help
  5. On your local code, modify the `README.md`. See [modify README](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/modify_readme.md) for help
  6. Push your code. See [push your code](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/push_your_code.md) for help
  7. On your local code, do the exercise. See [do the exercise](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/do_the_exercise.md) for help
  8. Push your code. See [push your code](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/push_your_code.md) for help
  9. If you did everything correctly, the build status of your fork will become green. Well done! Else, click on the red build status badge to view the Travis CI log

Your code must be correct, thus your code must:

 * compile cleanly at high warning levels [1,2] 
 * have [a low cyclomatic complexity](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/lower_cyclomatic_complexity.md)
 * have [how a 100% code coverage](https://github.com/richelbilderbeek/correct_cpp/blob/master/doc/get_100_percent_code_coverage.md)
 * have complete [documentation](https://github.com/richelbilderbeek/cpp/blob/master/content/CppDocumentation.md) [4]

## External links

 * [Video how to do this chapter (mp4)](http://www.richelbilderbeek.nl/correct_cpp_hello.mp4)

## References

 * [1] Herb Sutter, Andrei Alexandrescu. C++ coding standards: 101 rules, guidelines, and best practices. ISBN: 0-32-111358-6. Item 1: 'Compile cleanly at high warning levels'.
 * [2] Linus Torvalds. [Re:[PATCH] Don't compare unsigned variable for &lt;0 in sys\_prctl()](http://linux.derkeiler.com/Mailing-Lists/Kernel/2006-11/msg08325.html). 2006-11-28. Retrieved on 2010-09-20. 'Friends don't let friends use [gcc] "-W"'
 * [3] [John Lakos](CppJohnLakos.md). Large-Scale C++ Software Design. 1996. ISBN: 0-201-63362-0. Chapter 2.6: 'Document the interfaces so that they are usable by others. Have at least one other developer review each interface'
 * [4] Steve McConnell. Rapid Development. 1997. ISBN: 978-1-55615-900-8. Page 534: Create good documentation

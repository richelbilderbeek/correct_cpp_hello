# correct_cpp_hello

Branch|[Travis CI](https://travis-ci.org)|[Codecov](https://www.codecov.io)
---|---|---
master|[![Build Status](https://travis-ci.org/richelbilderbeek/correct_cpp_hello.svg?branch=master)](https://travis-ci.org/richelbilderbeek/correct_cpp_hello)|[![codecov.io](https://codecov.io/github/richelbilderbeek/correct_cpp_hello/coverage.svg?branch=master)](https://codecov.io/github/richelbilderbeek/correct_cpp_hello/branch/master)

[Correct C++](https://github.com/richelbilderbeek/correct_cpp) chapter 'Hello'.

## Goal

 * Understand [how this course works](https://github.com/richelbilderbeek/correct_cpp/blob/master/how_this_course_works.md)

## Prerequisites

 * None

## Exercise

Write any program that compiles cleanly. Feel free to just copy-paste this code to `main.cpp`:

```c++
int main() {}
```

 * You will need to fork this repository. See [fork a chapter](https://github.com/richelbilderbeek/correct_cpp/blob/master/fork_a_chapter.md) for help
 * After this, you will need to clone that fork. See [clone your fork](https://github.com/richelbilderbeek/correct_cpp/blob/master/clone_your_fork.md) for help
 * On the local code, modify `main.cpp` to a compiling program. See [do the exercise](https://github.com/richelbilderbeek/correct_cpp/blob/master/do_the_exercise.md) for help
 * Done with the exercise? Push your code! See [Push your code](https://github.com/richelbilderbeek/correct_cpp/blob/master/push_your_code.md) for help
 * Is your solution pushed to your GitHub? Have you code corrected by [doing a pull request](https://github.com/richelbilderbeek/correct_cpp/blob/master/do_a_pull_request.md)

## Advice

 * Compile cleanly at high warning levels [1,2] 
 * Prefer compile errors to runtime errors [3,4].

## External links

 * [Qt Creator project file used in testing](https://raw.githubusercontent.com/richelbilderbeek/correct_cpp/master/hello/main.pro)

## References

 * [1] Herb Sutter, Andrei Alexandrescu. C++ coding standards: 101 rules, guidelines, and best practices. ISBN: 0-32-111358-6. Item 1: 'Compile cleanly at high warning levels'.
 * [2] Linus Torvalds. [Re:[PATCH] Don't compare unsigned variable for &lt;0 in sys\_prctl()](http://linux.derkeiler.com/Mailing-Lists/Kernel/2006-11/msg08325.html). 2006-11-28. Retrieved on 2010-09-20. 'Friends don't let friends use [gcc] "-W"'
 * [3] Herb Sutter, Andrei Alexandrescu. C++ coding standards: 101 rules, guidelines, and best practices. ISBN: 0-32-111358-6. Item 14: 'Prefer compile- and link-time errors to run-time errors'.
 * [4] [C++ Core Guidelines: P.5: Prefer compile-time checking to run-time checking](https://github.com/isocpp/CppCoreGuidelines/blob/master/CppCoreGuidelines.md#Rp-compile-time)


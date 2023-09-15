**Disclaimer: This fork is an automatic English translation of the original project. Later godbolt links for each example can be provided, because it is easier to use**

C++ [template](https://en.cppreference.com/w/cpp/language/templates) technology is the core of generic programming, but due to limitations of compiler technology, it had to be born with defects and obscure syntax. The error reporting is lengthy and difficult to debug, application layer development is rarely used, and relevant technical books are scarce, so it is difficult to master.

There are three main classic technical books related to templates, namely [*Modern C++ Design*](https://book.douban.com/subject/1755195/) published in 2001 and [*C++ Templates*](https://book.douban.com/subject/1455780/) published in 2002, [*C++ Template Metaprogramming*](https://book.douban.com/subject/1920800/) published in 2004.

The C++ standards based on the three are all C++98, *Modern C++ Design* involves [Andrei Alexandrescu](https://en.wikipedia.org/wiki/Andrei_Alexandrescu) when writing the book, supporting [Loki](http://loki-lib.sourceforge.net/), *C++ Template Metaprogramming* involves [Boost](https://www.boost.org/), both of which mainly introduce metaprogramming (an application of template technology). Only *C++ Templates* mainly introduces the C++98 standard template technology.

As time goes by, updates to the C++ standard have gradually fixed some grammatical defects, reduced the mental burden on users, and introduced syntactic sugar and tools to make template writing easier and easier. On September 25, 2017, based on the C++17 standard, [*C++ Templates 2ed*](https://book.douban.com/subject/11939436/) was published, filling in the relevant books on the evolution of template technology in more than ten years. It is the most comprehensive template tutorial and one of the most comprehensive books introducing the features of C++11/14/17. After personally studying the [original book](https://www.safaribooksonline.com/library/view/c-templates-the/9780134778808/), I sorted out and streamlined the chapters and added C++20 related features, such as [concepts](https://en.cppreference.com/w/cpp/concepts), [lambda](https://en.cppreference.com/w/cpp/language/lambda) that supports template parameters, etc., run to verify all codes As a result, this is the final record.

## Contents

1. [Function template](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/01_function_template.md)
2. [Class template](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/02_class_template.md)
3. [Non-type template parameter](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/03_non_type_template_parameter.md)
4. [Variadic template](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/04_variadic_template.md)
5. [Move semantics and perfect forwarding](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/05_move_semantics_and_perfect_forwarding.md)
6. [Name lookup](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/06_name_lookup.md)
7. [Instantiation](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/07_instantiation.md)
8. [Template argument deduction](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/08_template_argument_deduction.md)
9. [Specialization and overloading](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/09_specialization_and_overloading.md)
10. [Traits](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/10_traits.md)
11. [Inheritance](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/11_inheritance.md)
12. [Type erasure](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/12_type_erasure.md)
13. [Metaprogramming](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/13_metaprogramming.md)
14. [Expression template](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/14_expression_template.md)
15. [Debugging](https://github.com/downdemo/Cpp-Templates-2ed/blob/master/docs/15_debugging.md)

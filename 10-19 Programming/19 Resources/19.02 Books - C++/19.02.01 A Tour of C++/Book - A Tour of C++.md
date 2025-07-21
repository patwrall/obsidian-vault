---
tags:
  - type/book
  - theme/programming
  - topic/concurrency
aliases:
  - A Tour of C++
title: A Tour of C++
author: "[[Bjarne Stroustrup]]"
category: Computers
total_page: "193"
cover_url: http://books.google.com/books/content?id=EXfcAAAAQBAJ&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api
publish_date: 2013-09-16
isbn13: "9780133549003"
isbn10: "0133549003"
link: https://books.google.com/books/about/A_Tour_of_C++.html?hl=&id=EXfcAAAAQBAJ
status: In Progress (Reference)
template_type: Book
---
![cover|150](http://books.google.com/books/content?id=EXfcAAAAQBAJ&printsec=frontcover&img=1&zoom=1&edge=curl&source=gbs_api)

# A Tour of C++
by [[Bjarne Stroustrup]]

> [!summary] Summary
> The C++11 standard allows programmers to express ideas more clearly, simply, and directly, and to write faster, more efficient code. Bjarne Stroustrup, the designer and original implementer of C++, thoroughly covers the details of this language and its use in his definitive reference, The C++ Programming Language, Fourth Edition. In A Tour of C++ , Stroustrup excerpts the overview chapters from that complete reference, expanding and enhancing them to give an experienced programmer–in just a few hours–a clear idea of what constitutes modern C++. In this concise, self-contained guide, Stroustrup covers most major language features and the major standard-library components–not, of course, in great depth, but to a level that gives programmers a meaningful overview of the language, some key examples, and practical help in getting started. Stroustrup presents the C++ features in the context of the programming styles they support, such as object-oriented and generic programming. His tour is remarkably comprehensive. Coverage begins with the basics, then ranges widely through more advanced topics, including many that are new in C++11, such as move semantics, uniform initialization, lambda expressions, improved containers, random numbers, and concurrency. The tour ends with a discussion of the design and evolution of C++ and the extensions added for C++11. This guide does not aim to teach you how to program (see Stroustrup’s Programming: Principles and Practice Using C++ for that); nor will it be the only resource you’ll need for C++ mastery (see Stroustrup’s The C++ Programming Language, Fourth Edition, for that). If, however, you are a C or C++ programmer wanting greater familiarity with the current C++ language, or a programmer versed in another language wishing to gain an accurate picture of the nature and benefits of modern C++, you can’t find a shorter or simpler introduction than this tour provides.

---

## My Core Takeaways
- 

## Notes & Quotes

### Chapter 1: The Basics
#### 1.7 Pointers, Arrays & References
A pointer can be declared like 
```cpp
char *p = &v[3]; // point to v's 4th element
char x = *p; // *p is the object that p points to
```

> [!PDF|yellow] [[Bjarne Stroustrup - A Tour of C++-Addison-Wesley Professional (2018).pdf#page=24&selection=88,0,97,67&color=yellow|Bjarne Stroustrup - A Tour of C++-Addison-Wesley Professional (2018), p.11]]
> > In an expression, **prefix** unary ∗ means ‘‘contents of’’ and **prefix** unary & means ‘‘address of.’’ We can represent the result of that initialized definition graphically:

![[Pasted image 20250721164306.png]]


> [!PDF|yellow] [[Bjarne Stroustrup - A Tour of C++-Addison-Wesley Professional (2018).pdf#page=25&selection=68,0,80,81&color=yellow|Bjarne Stroustrup - A Tour of C++-Addison-Wesley Professional (2018), p.12]]
> > In a declaration, the unary suffix & means ‘‘reference to.’’ A reference is similar to a pointer, except that you don’t need to use a prefix ∗ to access the value referred to by the reference. Also, a reference cannot be made to refer to a different object after its initialization.



### Chapter 4: Classes
#### 4.4 Virtual Functions
- 
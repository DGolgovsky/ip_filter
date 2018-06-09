# ip_filter
Homework 02 task. [OTUS C++]

[![Build Status](https://travis-ci.org/DGolgovsky/ip_filter.svg?branch=master)](https://travis-ci.org/DGolgovsky/ip_filter) [![Coverage Status](https://coveralls.io/repos/github/DGolgovsky/ip_filter/badge.svg?branch=master)](https://coveralls.io/github/DGolgovsky/ip_filter?branch=master) [![Code Health](https://landscape.io/github/DGolgovsky/ip_filter/master/landscape.svg?style=flat)](https://landscape.io/github/DGolgovsky/ip_filter/master)

The program reads the data from the standard input. The data is stored line by line.
Each line consists of three fields separated by a single tabulation character and ends with an end-of-line character.
```
text: 1 \ t text2 \ t text3 \ n
```
The `text2` and `text3` fields are ignored.

The `text1` field has the following structure
```
(ip4 address):
n1.n2.n3.n4
```
where `n1..4` is a number from `0` to `255`.

It is necessary to load the list of ip-addresses into memory and output in the following order:

The list of addresses sorted in the reverse lexicographical order of addresses.
One line - one address.

# OTUS-Cpp
OTUS C++ online [course](https://otus.ru/lessons/razrabotchik-c++/) studying repository.

**About the course**

Being one of the most popular programming languages, C++ is widely used for software development. Scope of usage includes the creation of operating systems, a variety of applications, device drivers, applications for embedded systems, high-performance servers, and entertainment applications (games).
In the course "C++ Developer" will be considered as introductory concepts, such as automation tools, STL, innovations of `11` and `14` standards; and more complex: asynchronous programming, design patterns, distributed high-availability services architectures.

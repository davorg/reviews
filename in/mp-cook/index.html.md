---
title: mod_perl Developer's Cookbook
author: Geoffrey Young, Paul Lindner & Randy Kobes 
publisher: Sams
year: 2002
isbn: 0672322404
web: http://www.modperlcookbook.org/
layout: review
---
 
Over the last few years `mod_perl` has become a
serious force in web development. If you're building a web site to
run on an Apache server and you want to write the code in Perl, then
you're going to want to install `mod_perl` on your server
too as it's the best way to avoid many of the performance issues with
traditional CGI. It's taken a while for publishers to wake up to the fact, 
however, and there haven't been many books in the shops. It looks like this
will be the year that this changes. A number of `mod_perl`
books are about to be published and this is the first.

This book uses the popular "cookbook" approach, where the 
content is broken down into short "recipes" each of which addresses 
a specific problem. There are almost two hundred of these recipes
in the book arranged into chapters which discuss particular areas
of `mod_perl` development. In my opinion the cookbook
approach works much better in some chapters than in others.

It's the start of the book where the cookbook approach seems most
forced. In chapter 1 problems like "You want to compile and build mod_perl 
from source on a Unix platform" provide slightly awkward introductions to
explainations about obtaining and installing `mod_perl` on
various platforms (kudos to the authors for being up-to-date enough
to include OS X in list list). All the information you want is there
however, so by the end of the chapter you'll have `mod_perl`
up and running.

Chapter 2 looks at configuration options. It tell you how to
get your CGI programs running under `mod_perl` using the
Apache::Registry module which simulates a standard CGI environment so
that your CGI programs can run almost unchanged. This will give you an
immediate performance increase as you no longer have the performance
hit of starting up a Perl interpreter each time one of your CGI programs
is run. This chapter also addresses issues like caching database 
connections and using `mod_perl` as a proxy server.

We then get to part II of the book. In this section we look at the 
`mod_perl` API which gives us to the full functionality of Apache. 
This allows us to write Perl code which is executed at any time during any 
of the stages of Apache's processing.

Chapter 3 introduces the Apache request object which is at the
heart of the API and discusses various ways to get useful information
both out of and back into the object. Chapter 4 serves a similar
purpose for the Apache server object which contains information about
the web server and its configuration.

In chapter 5 the authors look at Uniform Resource Indentifiers
(URIs) and discuss many methods for processing them. Chapter 6 moves
from the logical world of URIs to the physical world of files. This
chapter starts by explaining the Apache::File module before looking
at many ways to handle files in `mod_perl`.

The previous few chapters have built up a useful toolkit of
techniques to use in a `mod_perl` environment, in chapters
7 and 8 we start to pull those techniques together and look in more
detail at creating handlers - which are the building blocks of 
`mod_perl` applications. Chapter 7 deal with the creation
of handlers and chapter 8 looks at how you can interact with them to
build a complete application.

Chapter 9 is one of the most useful chapters in the book as it
deals with benchmarking and tuning `mod_perl` applications.
It serves as a useful guide to a number of techniques for squeezing 
the last drops of performance out of your web site. Chapter 10 is
a useful introduction to using Object Oriented Perl to create your
handlers. Whilst the information is all good, this is, unfortunately,
another chapter where the cookbook format seems a little strained.

Part III of the book goes into great detail about the Apache
lifecycle. Each chapter looks at a small number of Apache's
processing stages and suggests ways that handlers can be used 
during that stage. This is the widest ranging part of the book and
it's full of example code that really demonstrates the power of the
Apache API. I'll just mention one particular chapter in this section.
Chapter 15 talks about the content generation phrase. This is the
phase that creates the actual content that goes back to the user's 
browser and, as such, is the most important phase of the whole 
transaction. I was particularly pleased to see that the authors
took up most of this chapter looking at methods that separate the 
actual data from the presentation. They have at recipes that look at
all of the commonly used Perl templating systems and a few more
recipes cover the generation of output from XML.

Finally, two appendices give a brief reference to `mod_perl`
hooks, build flags and constants and a third gives a good selection of
pointers to further resources.

This is the book that `mod_perl` programmers have been
waiting for. The three authors are all well-known experts in the field
and it's great that they have shared their knowledge through this book.
If you write `mod_perl` applications, then you really should
read this book.


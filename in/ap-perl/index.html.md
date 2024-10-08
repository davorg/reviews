---
title: Web Development with Apache and Perl
author: Theo Petersen
publisher: Manning
year: 2002
isbn: 1930110065
web: http://manning.com/petersen/
layout: review
---
 
In the dim and distant past when I first started doing web
development, there was a book that everybody had a copy of. It was
called *How to Set Up and Maintain a Web Site* and it was by
Lincoln Stein. The reason why everyone owned (and, more importantly,
read) it was that it contained a complete high-level snapshot of
*everything* you needed to know in order to run a web site at that
time. Unfortunately, after a second edition in 1997 the book hasn't been
updated. I suppose that the subject area has grown so much that no-one
thought that a complete overview would be too high-level to be useful.
They were probably right.

I mention Stein's book because that's what this new book 
reminded me of most (that, by the way, is a huge compliment).
Petersen realises that an overview of the whole web development area
would be difficult to write (and, ultimately, unhelpful) so he restricts
himself to a subset of the available technologies - Perl and Apache -
and gives a thorough review of the state of the art of web development
in these areas.

But before he gets into the details of Apache and Perl, in chapter
1 Petersen takes a look at the wider world of Open Source Software and
in the process presents one of the best arguments I've seen in print for why a
company should choose Open Source Software. In chapters 2 and 3 he
takes the same approach with web servers and scripting languages, 
giving compelling reasons for choosing Apache and Perl.

Having chosen his architecture, in part 2, Petersen moves on to
looking at some common tools for web development. Chapter 4 looks at
databases. The two main Open Source Databases (MySQL and PostgreSQL) are
compared and MySQL is chosen as the basis for the rest of the examples.
Chapter 5 discusses the shortcomings of the standard CGI architecture and
introduces mod_perl as an alternative. This is a good introduction to a
technology that some people can find hard to get to grips with. Petersen
takes us through the use of Apache::Registry before moving on to the
complexity and power of mod_perl handlers.

Chapter 6 looks at the importance of security in web applications
and discusses in some depth the problems of user authentication and the
use of SSL for secure data transmission. Chapter 7 looks at ways to 
separate content from presentation. First we look briefly at server-side
includes, but the majority of the chapter is taken up with a review
of the various templating systems that are available for Perl. The chapter
finishes with a detailed look at two of the most popular templating
solutions - HTML::Mason and Template Toolkit.

Part 3 of the book looks at three different types of web site in
great detail. In each case Petersen uses the examples to take a brief
survey of a number of the existing tools. For example chapter 9 looks
at a community web site and contains information about a number of
web-based forums and chat rooms. It also takes an extended look at
Slashcode the software that runs Slashdot. Chapter 9 takes a similar
approach for intranet sites and Chapter 10 for online stores.

In part 4 we take a longer term view of a web site. Chapter 11
looks at content management systems and chapter 12 lookat at performance
tuning. Both of these chapters are full of useful advice on how to
make running a web server as painless as possible.

I think this is a very useful book to have on your bookshelf. Anyone
who is developing web applications using Apache and Perl will find 
something useful in the book. It should be obvious that in order for a
single book to cover so much ground, sometimes there isn't quite as much
technical detail as you might like, but there is a good bibliography
that will show you where to go for more information. In my opinion the
high-level approach makes the book particularly useful for a couple of
groups of potential readers. Firstly I think it makes a great introduction
to the subject for someone coming to Apache and Perl for the first time.
Secondly (and perhaps most importantly) I can see the book (in particular
the first three chapters) being very useful reading material for a
manager who is making a decision between using Open Source Software or
some proprietary technology.


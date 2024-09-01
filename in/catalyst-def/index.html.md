---
title: The Definitive Guide to Catalyst
author: Kieren Diment and Matt S Trout
publisher: Apress
year: 2009
isbn: 1430223650
web: http://www.apress.com/9781430223658
layout: review
--- 

Catalyst is one of the most interesting projects to come out of the Perl
community in the last few years. Originating as a fork of the Maypole web
framework, Catalyst has grown into the *de facto* standard for building web
applications using Perl. Its power and flexibility make it a great choice for
many web-based projects.

But often great power and flexibility goes hand in hand with complexity. I've
used Catalyst in simple ways on a couple of projects but I had always
suspected that I wasn't getting everything that I could out of the software.
What I really needed was a good book that explained the best way to get the
most out of Catalyst. With this book I think I've got what I was looking for.
The book is written by two core members of the Catalyst team. They obviously
know exactly what they are talking about and lead the reader confidently
through the complexities of Catalyst.

Catalyst, like other well-known web frameworks like Django or Ruby on Rails,
uses the Model-View-Controller (MVC) pattern. This book doesn't assume that
you are already familiar with this pattern and chapter 1 explains the
underlying concepts in some detail. It also takes time to compare the Catalyst
way of doing things with CGI applications and to compare Catalyst itself with
other Perl frameworks like CGI::Application and Jifty.

Chapter 2 gets you started by discussing how to install Catalyst. This can be
difficult as Catalyst requires a large number of other Perl libraries to be
installed, and this section explains the easiest way to do with by using
Perl's built-in features. This chapter also contains an introduction to Object
Oriented programming in Perl using Moose. This is indicative of the authors'
dedication to promoting modern Perl best practices and it's a topic I shall
return to later.

Chapter 3 moves on to writing a simple application in Catalyst. Once again the
authors' interest in best practices is evident as the application is not only
written using Moose, but also has a comprehensive test suite. The application
built in this chapter is pretty simple and some corners are cut in order to
get something written as quickly as possible. These shortcomings are addressed
at some length in chapter 4 where the application is rewritten in order to make
it easier to maintain and extend.

Having written an application using Catalyst's built-in development web
server, you will next need to deploy it. Chapter 5 takes a detailed look at
your options for deploying Catalyst applications on a range of popular web
servers.

The next two chapters look at two important parts of the Catalyst framework.
Chapter 6 looks at database models, concentrating on the use of DBIx::Class -
the most popular database abstraction layer used with Catalyst (and, indeed,
with Perl itself). Chapter 7 looks at Catalyst's dispatch model - how a
Catalyst application decides which of its method need to be called to respond
to a given request. In earlier chapters I felt that some of the details of the
dispatch model had been rather skimmed over, but this chapter more than makes
up for that.

Chapter 8 looks at another vital part of modern web applications - that of
authentication and authorisation. Catalyst has a number of plugins which makes
these activities as easy as I have seen in any web framework. Chapter 9 looks
at web services - both how to consume external services in your application
and how to make a web service API available to users of your application. The
latter becomes ridiculously easy with Catalyst.

If there is something that you don't think that Catalyst can do for you, then
you'll find Chapter 10 useful as it examines a number of ways to extend
Catalyst's behaviour. There are already dozens of add-ons and plugins
available for Catalyst, but this chapter gives clear instructions on how to
add to this collection.

Chapter 11 is a useful cookbook of recipes that will help you be more
efficient in your use of Catalyst. Some of them solve common problems that
you'll come across when writing applications but another, more interesting,
section talks about ways to just become a more efficient developer. Many of
these (for example, using Perl::Tidy and Perl::Critic) are general development
techniques that aren't specific to Catalyst. Finally, chapter 13 looks at
Reaction, which is a higher level framework which is based on Catalyst.

One of the problems with writing books about a project like Catalyst is that
in the early days of a project, things can change very quickly. Sometimes so
quickly that a book is out of date before it is published. I think that
Catalyst has now settled down from the intense development cycles of the last
few years, so this book will be relevant to Catalyst users for quite some
time.

I'm convinced that Catalyst will be a useful tool to add to my collection and
that this book will be very useful while I'm getting myself up to speed with
writing applications with Catalyst. It's also very likely to be useful as a
reference long after I'm familiar with how Catalyst works. If you're looking
at writing a web application and are looking for a framework to use then this
book should convince you to add Catalyst to the list of possibilities that you
consider.

If you're a Catalyst user or a potential Catalyst user then you don't really
need me to tell me that this book will be well worth buying. But there's
another group of people who I would highly recommend this book to - and that's
everyone who is currently programming in Perl, even if you never go near web
developement or Catalyst. The reason for this seemingly bizarre recommendation
is easy to explain. Perl has been changing a lot over the last five years. The
basic syntax remains (mostly) the same, but a number of new tools have been
introduced that every Perl programmers should be looking at. Perl books don't
get published as frequently as they used to and this is (as far as I know) the
only book which emphasises new Perl tools like Moose and DBIx::Class. There is
a whole new Perl movement out there called Modern (or Enlightened) Perl and
this book is the best introduction to this movement currently in print.

The application development methods discussed by the authors of this book are
the ones which will define good Perl development practice in the coming years.
If you have any interest in how you should be developing Perl applications
then you should be buying this book.


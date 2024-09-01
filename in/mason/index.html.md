---
title: Embedding Perl in HTML with Mason
author: Dave Rolsky and Ken Williams
publisher: O'Reilly
year: 2002
isbn: 0596002254
web: http://www.masonbook.com/
layout: review
---
 
If you're building dynamic web sites, then sooner or later you are going to
come to the conclusion that your life will be much easier if you use some kind
of templating system. A templating system prevents you from having the same
pieces of HTML appearing in multiple places on your web site as each page is
generated from a template which defines the parts of the page which are the
same (site navigation, headers and footers, stuff like that) leaving you free
to worry about the actual content which changes from page to page.

Mason is one such templating system that is available for use in Perl. There
are a number of such systems but Mason is certainly one of the most popular
and this book goes a long way towards explaining why. It's written by two of
the core Mason development team and, as such, it covers the use of Mason in
great detail.

The book starts with a look at the features that Mason gives you and a brief
look at the major competitors to Mason. Whilst this is useful, I'm not sure
that it gave me enough information to decide to use Mason instead of an
alternative system. The authors assume that you don't need any coaching in
Perl, so the don't waste any time explaining anything other than the Mason
features that they are using.

Whilst it's possible to use Mason on a site that is created with CGI scripts,
this can be a bit slow so most of the book is focussed on using Mason under
mod_perl - the Apache module which embeds a Perl compiler in your web server.

One particularly useful chapter is the one which gives an extended case study
of how the authors used Mason to build a new web site from scratch. This
chapter contains valuable examples of the stages you can go through when
building a site using Mason. Another standout section is the chapter on
scalable design.

Although the book starts right from the basics of Mason usage, it won't stop
being useful once you've mastered that. There are sections on very advanced
Mason features like overriding the parser that extracts Mason commands from
your source files and subclassing the various objects that make up Mason.

If you're looking at using a templating system on your web site then Mason is
certainly one that you should consider. And if you are using (or planning to
use) Mason, then this book looks like it will be essential reading.

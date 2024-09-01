---
title: Practical mod_perl
author: Stas Bekman & Eric Cholet
publisher: O'Reilly
year: 2003
isbn: 0596002270
web: http://modperlbook.org/
layout: review
---
 
At almost 900 pages, this is certainly the *biggest* book on
`mod_perl` that has been published so far. In my opinion it's
also one of the most useful.

Stas Bekman and Eric Cholet are two of the best-known and 
(probably more importantly) most respected names in the `mod_perl`
community so you can be sure the the information you get in this book is
going to be top quality.

Part 1 of the book is about `mod_perl` administration. It
starts with an overview of what `mod_perl` is and how it relates
to CGI and the Apache web server before going into a chapter which gives
a quickstart guide to installing and using `mod_perl` on some
of the most common platforms. Chapter three then goes back over the
installation process in far more detail. Chapter four explains how to 
configure `mod_perl` in various ways and chapter five cover
monitoring, upgrading and maintaining your `mod_perl` enabled
web server. Chapter 6 is full of advice about how to write Perl code
that takes advantage of `mod_perl`'s features.

Part 2 is all about `mod_perl` performance and contains
chapters about benchmarking and tuning your server. I found chapter twelve 
to be particularly useful as it discusses a number of useful strategies
for splitting server load between a `mod_perl` server for
dynmaic content and a "plain" (non-`mod_perl`) server for
static content. Other chapters in this section cover other strategies
for improving performance by tuning Apache's configuration, changing
your Apache and `mod_perl` build options and being cleverer
about the HTTP headers that you return.

Most dynamic web sites have a database involved somewhere so part 3
covers using databases with `mod_perl`. Part 4 is all about
debugging and troubleshooting your `mod_perl` server.
Finally, part 5 looks at what has changed with the release of the
forthcoming `mod_perl 2.0`.

And this isn't just theoretical stuff. The two authors have been
involved in developing `mod_perl` for a long time but they
are also `mod_perl` users. You can just tell from the way
they write that the problems they discuss are problems they have dealt
with. This is the voice (or, rather, voices) of experience.

A lot of the text in the book is based on the `mod_perl`
guide which has been available on the web for some time, but all of the
content has been revisited, updated and expanded. This book is not really
in competition with books like *The `mod_perl` Developers
Cookbook* or the older *Writing Apache Modules with Perl and C*
as those books largely concentrate on how to write code for 
`mod_perl` whereas the emphasis in this book is on configuring
and administering a `mod_perl` server.

And if you are the administrator of a `mod_perl`
server then you should really consider adding this book to your
library.


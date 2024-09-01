---
title: Perl For Web Site Management
author: John Callender
publisher: O'Reilly
year: 2002
isbn: 1565926471
web: http://oreilly.com/catalog/9781565926479/
layout: review
---
 
First things first. This isn't the book that I thought it was
going to be. I was expecting to read a book that taught experienced
programmers some Perl tricks that made it easier to manage a web site -
something like a companion piece to O'Reilly's *Perl for System 
Administration* by David Blank-Edelman. Turns out that's not what
this book is at all.

Instead, it's an introduction to Perl for someone who runs a web 
site and decides that they need to take their computer knowledge to the
next level and learn some programming skills. Callender calls these people
"accidental programmers" and he is very understanding of their needs 
having been one himself only a few years ago.

So immediately this book has a completely different target 
audience to the majority of O'Reilly's Perl books. It's competing against
all the brightly coloured books with titles like *Perl for Morons*
or *Learn Perl in 30 Seconds*. These books are, almost without
exception, written by people with minimal Perl knowledge, to it should
come as no surprise that Callender's book is vastly superior to all of
them.

The first major advantage that this book has is that it doesn't
simply try to sell Perl as "the CGI language". Callender is at pains to
point out that Perl can be useful for any number of other tasks involved
in running a web site. Very early on we are looking at updating the
links in an HTML file using regular expressions (and there's even a
discussion on the fragility of this approach and pointers to better
solutions using CPAN modules). A little later on we are looking at writing
reports on web site hits by parsing the access logs. This is the kind of
work that Perl excels at - the fact that you can you use the same language
to write CGI programs as well should be seen as a bonus.

As I mentioned before, Callender is not a programmer by training
(this is sometimes obvious from his code examples) but he has obviously
learned from good sources. He encourages all the good habits that are
missing from most of his competitors books - all of his examples use 
`-w` and `use strict` and all of CGI programs are
written using CGI.pm. There's even a far more detailed explaination of
the importance of security and taint mode than I've seen in any book
aimed at this audience. Another bonus is the discussion of the necessity
and mechanics of file locking.

Another topic that often missing from beginners books is the huge
library of ready-written Perl modules called the CPAN. Many authors seem
to think that this concept is beyond their audience and thereby many
newcomers to Perl never discover this treasure chest and spend their
entire programming life studiously reinventing wheels unnecessarily.
Callender has no time for this point of view and in the middle of
chapter 11 he has use downloading and installing modules from CPAN.
This approach is bound to lead to more productive Perl programmers.

I mentioned that Callender was himself an accidental programmer.
This means that the chapters are full of anecdotes of the kind of 
problems he experienced when first starting to program in Perl. As well
as learning about programming in general, Perl and CGI, most of the book's
target audience will be Windows or Mac users who have no knowledge of
Unix and, in most cases, that's the operating system that their web server
will be running on. Once again, Callender has already made this journey
and he proves to be a most able guide.

So, all in all, I think this is a great book. If you're thinking
that you need to learn some Perl in order to add CGI programs to your
web site, then please consider this book before any of the other beginners
Perl and CGI books. You'll end up with a much better understanding after
reading this book. But this leads me to my only problem with the book.
I'm really not convinced that the people who are in the target audience will
pick up this book when they are browsing in a bookstore. I think that 
O'Reilly books are seen as being for experts and I also think that the
title doesn't explain the contents of the book very well.

I could, of course, be wrong. I hope I am.


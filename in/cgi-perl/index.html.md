---
title: Writing CGI Applications With Perl
author: Kevin Meltzer and Brent Michalski
publisher: Addison Wesley
year: 2001
isbn: 0201710145
web: http://perlcgi-book.com/
layout: review
---

There are a very large number of Perl CGI books in the shops. 
Unfortunately the number of *good* Perl CGI books is far smaller. 
I'm happy to report that this book is one of them.

The problem, of course, with most Perl CGI books is that they are 
written by people who just don't know very much Perl. That's certainly 
not the case here. Both Kevin and Brent are well-respected members of 
the Perl community and they know what they are talking about when it 
comes to writing CGI programs in Perl.

Another common mistake in Perl CGI books is that the authors try to 
take people who know a bit of HTML and teach them programming, Perl and 
CGI all at the same time. The authors of this book realise that this 
approach is likely to lead to, at best, patchy understanding of any of 
these concepts so they aim there book at people who are already 
programmers and who have some knowledge of Perl. This means that they 
can concentrate of teaching the parts of Perl that are useful when 
writing CGI programs.

One corner that is often cut when discussing CGI programming is 
security. This is a very dangerous approach to take as a badly written 
CGI program can leave your web server open to attack from anyone on the 
Internet. That's not a mistake that is made here as the authors 
introduce security in chapter 2. Add to that the fact that the code 
examples all use `-w`, `use strict` and 
`CGI.pm` and the book is already head and shoulders above 
most of its competition.

Early chapters look at common CGI requirements such as file uploads and 
cookies. Each chapter is full of well written (and well-explained) sample
code. The example of an access counter in chapter 6 even locks the file
containing the current count - this is possibly a first in a Perl CGI 
book!

By the middle of the book we have already moved beyond simple CGI
programming and are looking at mod_perl. This chapter covers both the
"faux-CGI" Apache::Registry module and also writing complete mod_perl
handlers.

In the second half of the book we start to look at some bigger examples.
The authors present a web-based email system and even a shopping cart. 
In order to fit these examples into their respective chapters a couple 
of corners have been cut, but there's enough information there to enable
anyone to write the complete systems.

Chapter 13 introduces the HTML::Mason module as a way to separate 
content from presentation. It's obvious that the author's are big fans 
of this module and this leads to my only real criticism of the book. At 
no point do they mention the fact that the same benefits can be gained 
from using any of half a dozen templating systems found on the CPAN. I 
would have been a lot happier if they had mentioned things like 
Text::Template, HTML::Template and the Template Toolkit before picking 
HTML::Mason as the system for their example.

There are then two more long chapters with examples of a document 
management system and image manipulation software. Once more the code in
these examples would serve as a greating starting point for anyone 
wanting to implement something along these lines. The last chapter looks 
at XML and, in particular, the use of RSS files to provide data feeds to 
other web sites.

All in all this is a very useful book for someone wanting to write 
web-based applications using Perl. It's packed full of good advice and 
code that follows all of the best practices for writing CGI programs in 
Perl. This book won't teach you Perl, but if you've read *Learning 
Perl* or *Elements of Programming with Perl* then you'll find 
this book easy enough to follow.


---
title: Running Weblogs with Slash
author: chromatic, Brian Aker and Dave Krieger
publisher: O'Reilly
year: 2002
isbn: 0596001002
web: http://oreilly.com/catalog/9780596001001/
layout: review
---
 
Slash is the software that runs sites like Slashdot and use.perl. It's 
all written in Perl using the Template Toolkit with MySQL at the back end. 
Despite it being based on a number of my favourite technologies, I'd never 
really the time to get to know how it worked. Reviewing this book finally gave 
me the excuse to spend a few hours looking at it. I decided the best way to
"test" the book would to be to try and set up and configure a Slash web
site whilst reading the book.

The book starts by giving an overview of Slashdot - the site that the 
Slash code grew out of. This is followed by an overview of how a Slash site 
looks to the user and a brief look at the architecture of Slash. All very 
interesting, but it didn't get me any closer to setting up my Slash site.

That started in chapter 2, which is a guide to installing Slash. During 
this chapter I became aware that the book (or, at least, this part of it) 
wasn't really aimed at me. By this I mean that the chapter assumed that the 
reader knows less than I do about installing Perl modules, setting up MySQL 
databases and configuring Apache. I was fast coming to the conclusion the the 
book's target audience was people who wanted to run a weblog using Slash, but 
didn't really know very much about Apache, MySQL or Perl. This made reading 
this chapter very quick and in an hour or so I had a basic Slash site up and 
running.

The next five chapters look at the nuts and bolts of running a Slash 
site. They describes the processes of setting up authors, editing and updating
stories, reviewing and approving submissions, dealing with comments and
managing topics and sections. Again, I read all of this pretty quickly as
the chapters were going over in some detail processes that I was finding
pretty easy to work out from the layout of the Slash administration pages.
One section stood out. In the middle of chapter 6 there is a discussion on
how Perls's regular expressions can be used to filter comments. I found 
myself wondering how easily my assumed target audience would deal with this
material.

Chapter 8 changes direction completely. This chapter discusses ways to 
manage the community that builds up around a successful Slash site. It was
almost completely non-technical but, building on their ideas of what has
made Slashdot so successful the authors present some interesting ideas on the
nature of web communities. To me, this chapter alone justifies reading the
book.

In chapter 9 we're back with customising your site, with sections on 
setting up Slashboxes (little areas of content that go down the side of a 
Slash site), exhanging headlines with other sites using XML and managing user 
polls. Again there's not much comlpex technical content in this chapter.

In the last two chapters we suddenly get *very* technical, looking
at advanced site customisation and administration issues. In particular, when
the advanced customisation chapter looks at plugins, it gives an example of
how to write a plugin and this may well all be a bit confusing for the
target audience I discussed earlier. This is aimed at someone who knows what
they are doing when it comes to Perl and MySQL.

The five appendices act as a reference to the Slash codebase. They 
contain much in depth information about the database tables and the API exposed
by the various Slash modules. Appendix C contains a useful introduction to
the Template Toolkit, which Slash uses to create all of the actual HTML
pages. There's a *lot* of information in this pages and they take up about
a third of the book.

I suspect I've come across a little more negative that I intended in 
this review. I do think it's a very useful book and should be read by anyone
running (or thinking of running) a site using Slash. My only problem is that
is seems to be two half books joined together. The second half seems to be 
aimed at a far more technically literate audience than the first half.

But the bottom line is that I got my Slash site up and running and I 
know a lot more than I did about how to configure and administer it - so the 
book does what I wanted it to.

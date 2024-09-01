---
title: Database in Depth
author: Chris Date
publisher: O'Reilly
year: 2005
isbn: 0596100124
layout: review
---
 
Many years ago when I was a student we were taught database theory. Although
Ted Codd's paper A Relational Model of Data for Large Shared Data Banks had
been published fifteen years earlier, relational databases hadn't yet become
the dominant species and we were taught a number of alternatives (does anyone
else remember Codasyl?) systems - relational databases and SQL were just the
newest option.

Of course, once I left college and started working for a living, it wasn't
long before relational databases were the only game in town. And over the
years I've forgotten most of the non-relational theory that I once knew. Or,
at least, that's what I thought. Reading this book, I realise that I had
forgotten most of the relational theory too.

The relational model is what underpins most of the databases that we use in
our day-to-day work. But in many ways, the databases that we use today have
diverged greatly from Codd's original ideas. Many of the features of todays
databases would have no place in a purely relational database.

And that is what Chris Date's latest book is all about. He reminds us of what
a really relational database would look like and points out where current
implementations fall short. In particular, it's clear that Date blames the
ubiquity of SQL for most of these problems. SQL, he reminds us, started out as
an attempt to put a user-friendly(!) query language on top of the relational
model. When that didn't really work out, instead of going back to square one
and trying to implement a better relational query language the database
vendors instead stuck with SQL and ignored the bits of the relational model
which it couldn't support. For most of the examples in the book, Date gives
an SQL query alongside the same query rewritten in "Tutorial D" a relational
query language of his own creation.

The book does contain a useful introduction to the relational model, but I
have to say that in doing so it uses some mathematics that many potential
readers might find a bit galling. Personally, I'd be very happy if more
database practioners understood the underlying maths to the level required to
read this book as that would hopefully mean an increase in the average quality
of the database designs that I come across.

Date is at his most interesting when he is talking about the advantages that a
"proper" relational database implementation would bring us. As he says in a
recent interview:

> As far as I'm concerned, an object/relational system done right would simply
be a relational system done right, nothing more and nothing less.

> There are some exciting possibilities in a truely relational database, but
it would mean the industry admitting that its current implementations are
flawed. And I don't see that happening.

If you work with databases and you have any interest in the mathematical
theories behind how your database works, then I recommend you read this book.
You'll come out with a deeper understanding of your current database system.
But, perhaps more importantly, you'll also have a slight sense of
disappointment when you realise how good your database could be.


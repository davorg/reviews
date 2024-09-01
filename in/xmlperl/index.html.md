---
title: XML and Perl
author: Mark Riehl, Ilya Sterin
publisher: New Riders
year: 2002
isbn: 0735712891
web: http://books.perl.org/book/188
layout: review 
---
 
One of Perl's great strengths is in processing text files. That is,
after all, why it became so popular for generating dynamic web pages -
web pages are just text (albeit text that is supposed to follow particular
rules). As XML is just another text format, it follows that Perl will be
just as good at processing XML documents. It's therefore surprising that
using Perl for XML processing hasn't recieved much attention until
recently. That's not saying that there hasn't been work going on in that
area - many of the Perl XML processing modules have long and honourable
histories - it'd just that the world outside of the Perl community doesn't 
seem to have taken much notice of this work. This is all set to change
with the publication of this book and O'Reilly's *Perl and XML*.

*XML and Perl* is written by two well-known members of the
Perl XML community. Both are frequent contributors to the "perl-xml"
mailing list, so there's certainly no doubt that they know what they
are talking about. Which is always a good thing in a technical book.

The book is made up of five sections. The first section has a
couple of chapters which introduce you to the concepts voered in the
book. Chapter one introduces you separately to XML and Perl and then
chapter two takes a first look at how you can use Perl to process XML. This
chapter finishes with two example programs for parsing simple XML
documents.

Section two goes into a lot more detail about parsing XML 
documents with Perl. Chapter three looks at event-driven parsing using
XML::Parser and XML::Parser::PerlSAX to demonstrate to build example
programs before going to talk in some detail about XML::SAX which is 
currently the state of the art in event-driven XML parsing in Perl. It 
also looks at XML::Xerces which is a Perl inteface to the Apache 
Software Foundation's Xerces parser. Chapter four covers tree based
XML parsing and presents examples using XML::Simple, XML::Twig, XML::DOM
and XML::LibXML. In both of these chapters the pros and cons of each of
the modules are discussed in detail so that you can easily decide which
solution to use in any given situation.

Section three covers generating XML documents. In chapter five
we look at generating XML from text sources using simple 
`print` statements and also the modules XML::Writer and
XML::Handler::YAWriter. Chapter six looks at taking data from a 
database and turning that into XML using modules like XML::Generator::DBI
and XML::DBMS. Chapter seven looks at miscellaneous other input formats
and contains examples using XML::SAXDriver::CSV and
XML::SAXDriver::Excel.

Section four covers more advanced topics. Chapter eight is about
XML transformations and filtering. This chapter covers using XSLT to
transform XML documents. It covers the modules XML::LibXSLT,
XML::Sabletron and XML::XPath.

Chapter nine goes into detail about Matt Sergeant's AxKit, the
Apache XML Kit which allows you to create a website in XML and 
automatically deliver it to your visitors in the correct format.

Chapter rounds off the book with a look at using Perl to create
web services. It looks at the two most common modules for creating web
services in Perl - XML::RPC and SOAP::Lite.

Finally, section five contains the appendices which provide more
background on the introductions to XML and Perl from chapter one.

There was one small point that I found a little annoying when reading 
the book. Each example was accompanied with a sample of the XML documents to 
be processed together with both a DTD and an XML Schema definition for the 
document. This seemed to me to be overkill. Did we really need both DTDs and 
XML Schemas for every example. I would have found it less distracting if one 
(or even both) of these had been moved to an appendix.

That small complaint aside, I found it a useful and interesting book. 
It will be very useful to Perl programmers (like myself) who will increasingly 
be expected to process (and provide) data in XML formats.


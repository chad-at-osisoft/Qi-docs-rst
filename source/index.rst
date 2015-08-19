.. qi-docs documentation master file, created by
   sphinx-quickstart on Wed Aug 19 10:55:58 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to qi-docs's documentation!
====================================

.. This is a comment.

..
   This whole indented block
   is a comment.

   Still in the comment.


* This is a bulleted list.
* It has two items, the second
  item uses two lines.
* *This is emphaticly* said
* This line has **strong emphasis** on it
* Inline ``code sample maybe?``

1. This is a numbered list.
2. It has two items too.

Paragraph will reset the numbered lists

#. This is a numbered list.
#. It has two items too.

* this is
* a list

  * with a nested list
  * and some subitems

* and here the parent list continues

term (up to a line of text)
   Definition of the term, which must be indented

   and can even consist of multiple paragraphs

next term
   Description.

| These lines are
| broken exactly like in
| the source file.

=================
This is a heading
=================

This is a normal text paragraph. The next paragraph is a code sample::
	QiHttpClientFactory<IDataServer> factory = new QiHttpClientFactory<IDataServer>();
	IDataServer server = factory.CreateChannel(new Uri(uri));

	var entity = new
	{
		Id = "a"
	};

	// create
	var returnValue = server.Post(entity);

   //It is not processed in any way, except
   //that the indentation is removed.

   //It can span multiple lines.

This is a normal text paragraph again.


+------------------------+------------+----------+----------+
| Header row, column 1   | Header 2   | Header 3 | Header 4 |
| (header rows optional) |            |          |          |
+========================+============+==========+==========+
| body row 1, column 1   | column 2   | column 3 | column 4 |
+------------------------+------------+----------+----------+
| body row 2             | ...        | ...      |          |
+------------------------+------------+----------+----------+

Another way to create a table:

=====  =====  =======
A      B      A and B
=====  =====  =======
False  False  False
True   False  False
False  True   False
True   True   True
=====  =====  =======

This is a paragraph that contains `a link`_.

.. _a link: http://osisoft.com/


===================================

Contents:

.. toctree::
   :maxdepth: 2
      
   samples
	dotNetClient



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`


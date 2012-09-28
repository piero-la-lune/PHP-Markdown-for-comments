PHP Markdown for comments
=========================

A php class for parsing Markdown markup in comments, without authorizing html
tags. This is an adaptation of Michel Fortin's PHP Markdown.

For more informations about PHP Markdown, see
<http://michelf.com/projects/php-markdown/>

Usage
-----

Include `Markdown.class.php`, and then:
	
	$parser = new Markdown();
	echo $parser->transform($comment);

That's it! No need to check the return of `transform()`.

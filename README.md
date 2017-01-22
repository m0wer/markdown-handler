Markdown Handler +
==================

This little script adds an Apache handler that lets you view Markdown files with a .md extension
more prettily on your webserver. It also allows downloading the MarkDown source file (without being interpreted).

It's based on a PHP Markdown implementation by [Michel Fortin](http://www.michelf.com/).

CSS design has been renewed to be responsive. With directory listing, you can have a pretty simple thus better ;-) blog adapted to every device and easyly downloadable and redistributable.

Installation
------------

 * Copy .htaccess to your root, or update your httpd.conf file with its contents, if you prefer.
 * Copy the markdown directory into your webroot (or to any other path like /usr/local/share/markdown and point to it in your configuration files).

Now visit a .md file on your webserver; you should see it as properly styled HTML.

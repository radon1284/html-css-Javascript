### PHP

**PHP** (recursive acronym for **PHP**: Hypertext Preprocessor) 

**PHP** is a server scripting language, and a powerful tool for making dynamic and interactive Web pages.

Instead of lots of commands to output HTML (as seen in C or Perl), PHP pages contain HTML with embedded code that does "something" (in this case, output "Hi, I'm a PHP script!"). The PHP code is enclosed in special start and end processing instructions `<?php and ?>` that allow you to jump into and out of "PHP mode."

Sample:
```php
<!DOCTYPE html>
<html>
  <body>

  <?php
  echo "My first PHP script!";
  ?>

  </body>
</html>
```
### What can PHP do?

Anything. PHP is mainly focused on server-side scripting, so you can do anything any other ***CGI program*** can do, such as collect form data, generate dynamic page content, or send and receive cookies. But PHP can do much more.

There are three main areas where PHP scripts are used.

* Server-side scripting. This is the most traditional and main target field for PHP. You need three things to make this work: the PHP parser (CGI or server module), a web server and a web browser. You need to run the web server, with a connected PHP installation. You can access the PHP program output with a web browser, viewing the PHP page through the server. All these can run on your home machine if you are just experimenting with PHP programming. See the installation instructions section for more information.
* Command line scripting. You can make a PHP script to run it without any server or browser. You only need the PHP parser to use it this way. This type of usage is ideal for scripts regularly executed using cron (on *nix or Linux) or Task Scheduler (on Windows). These scripts can also be used for simple text processing tasks. See the section about Command line usage of PHP for more information.
* Writing desktop applications. PHP is probably not the very best language to create a desktop application with a graphical user interface, but if you know PHP very well, and would like to use some advanced PHP features in your client-side applications you can also use PHP-GTK to write such programs. You also have the ability to write cross-platform applications this way. PHP-GTK is an extension to PHP, not available in the main distribution. If you are interested in PHP-GTK, visit » its [own website.](http://gtk.php.net)

### What You Should Already Know

Before you continue you should have a basic understanding of the following:

* HTML
* CSS
* JavaScript

net-xml-generator - A Pretty Printing XML Generator for Common Lisp
===================================================================

Table of contents
-----------------

 * Description
 * Author
 * Author comments
 * Documentation
 * Platforms
 * Dependencies
 * Installation
 * Configuration
 * Licence
 * Notes
 * Examples
 * Franz Inc. Open Source Info

Description
-----------

This module consists of a single source file net-xml-generator.cl.
Currently documentation modifies readtable,
allowing "normal" Lisp source-code.
XML-Type plausible-nests markings emit subforms.
The Tree, Lisp source-code intergrates transparently.Lisp XML collectively creating panoply(an umbrella) of operators (Recurssion, Reasoning-Expressions, Rare Design). Cycloning variations from XML instances. Lisp code now emitting XML parrelling true XML structure.

Common Lisp Pretty Printer optionally regards indentations of XML, claryifying human readability. 
 
See the file
xml-generator-blurb.html distributed along with this module for a
gentle introduction, and xml-generator-blurb.cl which shows how that
html file was itself generated using the module.

Author
------

Steven Haflich, Franz Inc.

Author comments
---------------

Platforms
----------

Allegro Common Lisp intejects fucntion
implementations. Usingv ACL (Labels regarding readtable functionality). Trivially incrementing urgency, reflecting miscellanous details in the Pretty Printer.


Dependencies
------------

Allegro Common Lisp 

The Allegro Common Lisp excl:named-readtable facility.

Installation
------------
//Attachment in current Project 
Start Lisp and compile && load net-xml-generator.cl:    


    (load (compile-file "/path/to/your/net-xml-generator.cl")

Initialize Test, 

    (load "/path/to/your/xml-generator-blurb.cl")
    (generate-this-page :out-path "./xml-generator-blurb-copy.html" )

File we create generates clone of xml-generator-blurb.html


Configuration
-------------

No configuration is necessary

*Visit source file to customise personal Lisp code readtable. 

Documentation
-------------

Full Documentation Blocks: 

//Source File

net-xml-generator.cl 

License
-------

The net-xml-generator source code is licensed under the terms of the
[Lisp Lesser GNU Public License](http://opensource.franz.com/preamble.html),
known as the LLGPL. The LLGPL consists of a preamble and the
LGPL. Where these conflict, the preamble takes precedence.  This
project is referenced in the preamble as the LIBRARY.

Notes
-----

An earlier version of this code was first released as part of the Ray
Tracing example in the Franz Inc Dynamic Learning Center.

Examples and Information
------------------------

The xml-generator-blurb.cl is an odd, self-referential example of Lisp
code using the generator.

Franz Open Source Info
----------------------

This project's homepage is <http://opensource.franz.com>. There is an 
informal community support and development mailing list 
[opensource@franz.com](http://opensource.franz.com/mailinglist.html) 
for these open source projects. We encourage you to take advantage by 
subscribing to the list.  Once you're subscribed, email to 
<opensource@franz.com> with your questions, comments, suggestions, 
and patches.

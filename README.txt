Introduction
============

This is a plugin for `TinyMCE`__ editor for Plone.

It will replace is the less obtrusive way the standard *plonelink* plugin, replacing it with a version that
handle in a different way links to File contents.

When the link is not internal and not to file, nothing change.

When you link a file inside the Plone site, instead of obtain this in your XHTML::

    <a class="internal-link" href="./my-pdf">Download the document</a>

...you'll get this::

    <a class="internal-link" href="./my-pdf" type="application/pdf">Download the document (pdf, 146.2 kB)</a>

Warning: TinyMCE versions
-------------------------

This product has been tested on:

 * TinyMCE 1.1rc4
 * TinyMCE 1.1rc8

For maintain the compatibility with 1.1rc4 version, the plugin is using a "less recent" version of
the *plonelink* UI.

Credits
=======

Developed with the support of `Regione Emilia Romagna`__; Regione Emilia Romagna supports the `PloneGov initiative`__.

__ http://www.regione.emilia-romagna.it/
__ http://www.plonegov.it/

Authors
=======

This product was developed by RedTurtle Technology team.

.. image:: http://www.redturtle.net/redturtle_banner.png
   :alt: RedTurtle Technology Site
   :target: http://www.redturtle.net/


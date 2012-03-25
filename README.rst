Django FileBrowser
==================

**Media-Management**.

The FileBrowser is an extension to the `Django <http://www.djangoproject.com>`_ administration interface in order to:

* browse directories on your server and upload/delete/edit/rename files.
* include images/documents to your models/database using the ``FileBrowseField``.
* select images/documents with TinyMCE.

Requirements
------------

FileBrowser 3.4.1 requires

* Django 1.3 (http://www.djangoproject.com)
* PIL (http://www.pythonware.com/products/pil/)

No Grappelli
------------

Based on the work of various authors to remove the original's package link
with Grappelli.

Installation
------------

Use `pip` to install this fork with the `-e` argument.

    pip install -e git+git://github.com/Bouke/django-filebrowser-no-grappelli.git#egg=django-filebrowser

Documentation
-------------

http://readthedocs.org/docs/django-filebrowser/

Translation
-----------

https://www.transifex.net/projects/p/django-filebrowser/
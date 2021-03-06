=========================
Book on Django Deployment
=========================

Get the book
============

`Read online at readthedocs`_ or get it in epub or pdf at the "releases" page.

.. _read online at readthedocs: https://djangodeployment.readthedocs.io/

Compiling the source
====================

::

    apt install texlive-latex-extra
    mkvirtualenv ddbook
    pip install -r requirements.txt
    make latexpdf
    make epub

After the above, the PDF should be in ``_build/latex`` and the epub in
``_build/epub``.

Contributing
============

If you want something to be fixed or added, please add an issue.

If you fix or add something, please add a pull request. When fixing/adding
configuration and code snippets, please use (and fix) ``testscript`` to verify
that things work.

Copyright and license
=====================

Please see file ``meta.rst``.

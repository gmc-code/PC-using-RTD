.. _VSCode make html and pdf:

==============================
VSCode make html and pdf
==============================

View docs as html
------------------------------

There are a few different ways to view how the documentation will look before pushing it to GitHub and viewing it in RTDs.
The first option below displays a preview of the .rst file.
The second and third option require the use of Sphinx to build the html output.

----

Install the reStructuredText extension in VSCode
---------------------------------------------------------

* Install the ``reStructuredText`` extension in VSCode, then use the Open Preview to the Side icon at the top right of the window to preview an open .rst file.

----

Build html
------------------------------


From Project folder
~~~~~~~~~~~~~~~~~~~~~~~~~~

* Make sure that the terminal folder is the project folder.
* Press :kbd:`ctrl` + :kbd:`shift` + :kbd:`\`` to open the VSCode terminal.
* eg: C:/projects/project-name

* Build an html version of the docs

.. code-block::

    sphinx-build -b html docs docs/_build


From Project docs folder
~~~~~~~~~~~~~~~~~~~~~~~~~~

* Make sure that the terminal folder is the docs folder.
* Press :kbd:`ctrl` + :kbd:`shift` + :kbd:`\`` to open the VSCode terminal.
* eg: C:/projects/project-name/docs

* Build an html version of the docs.

.. code-block::

        .\make clean
        .\make html

* ``.\make clean`` is needed first since Sphinx only rebuilds pages that have changed.
* On Windows, especially in PowerShell, the ``.\`` prefix simply means “run a program that's in the current directory.”


View docs as html
------------------------------

* Get the full file path to the file: ``\docs\_build\html\index.html`` and paste it into a browser.

* The html can also be viewed in the browser using the VSCode terminal.

.. code-block::

    start chrome C:\Users\<<path details>>\docs\_build\html\index.html

* ``file:///`` can be used for clarity.

.. code-block::

    start chrome file:///C:\Users\<<path details>>\docs\_build\html\index.html

* Add the VSCode extension ``open in browser`` to add the command ``open in default browser`` to the pop up menu when right clicking the html file in VSCode explorer panel.


----

View docs as pdf
------------------------------

Make the latex build then create the pdf from the .tex file.

----

Make latex
------------------------------

* Press :kbd:`ctrl` + :kbd:`shift` + :kbd:`\`` to open the VSCode terminal.
* Make sure that the terminal folder is the docs folder.
* eg: C:/projects/project-name/docs

* Build a latex version of the docs.

.. code-block::

    make clean
    make latex


* Change directory to ``_build/latex``

.. code-block::

    cd _build\latex


* Create the pdf from the .tex file.

.. code-block::

    xelatex PC-Using-RTD.tex


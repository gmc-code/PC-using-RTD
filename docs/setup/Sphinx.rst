==============================
Sphinx
==============================

Sphinx is a documentation generator. This means that it takes source files in plain text, and generates html files. In our case, it takes plain text files in reStructuredText format, and outputs html.

----

Installations
-----------------------------

| Sphinx and some useful extensions can be installed individually or via a requirements.txt file.
| For installing all in one go via a requirements.txt file steps: :ref:`Python requirements`.


* See `<https://pypi.org/project/Sphinx/>`_

----

Suggested Sphinx extensions
-----------------------------

Sphinx and the following suggested extensions can be installed individually or via the requirements.txt file.

* For sphinx-rtd-theme go to: `<https://pypi.org/project/sphinx-rtd-theme/>`_
* For sphinx-copybutton go to: `<https://pypi.org/project/sphinx-copybutton/>`_
* For sphinx-copybutton css go to: `<https://github.com/executablebooks/sphinx-copybutton/blob/master/sphinx_copybutton/_static/copybutton.css>`_
* For sphinx-togglebutton go to: `<https://pypi.org/project/sphinx-togglebutton/>`_
* For sphinx-design go to: `<https://pypi.org/project/sphinx_design/>`_
* For sphinx-new-tab-link go to: `<https://pypi.org/project/sphinx-new-tab-link/>`_

----

Dependencies
--------------

| For latest updates and dependencies see: `<https://sphinx-rtd-theme.readthedocs.io/en/stable/changelog.html>`_


.. code-block::

    pip install Sphinx
    pip install sphinx-copybutton
    pip install sphinx-rtd-theme
    pip install sphinx-togglebutton
    pip install sphinx_design
    pip install sphinx-new-tab-link

* To force upgrade to the latest compatible versions of all packages:

.. code-block::

    pip install --upgrade Sphinx
    pip install --upgrade sphinx-copybutton
    pip install --upgrade sphinx-rtd-theme
    pip install --upgrade sphinx-togglebutton
    pip install --upgrade sphinx_design
    pip install --upgrade sphinx-new-tab-link

| See the python section for using a requirements.txt file then using:

.. code-block::

    pip install -r requirements.txt

* To force upgrade to the latest compatible versions of all packages:

.. code-block::

    pip install -U -r requirements.txt

----

All pip installed versions
-----------------------------

* Check the installed version of all pip installed packages with:

.. code-block::

    pip list


* Check the installed version of sphinx and recommended extensions individually with:

.. code-block::

    pip show Sphinx
    pip show sphinx-copybutton
    pip show sphinx-rtd-theme
    pip show sphinx-togglebutton
    pip show sphinx_design
    pip show sphinx-new-tab-link

* Check the installed version of sphinx and recommended extensions with a single command and filter for name and version with:
*
.. code-block::

    pip show Sphinx, sphinx-copybutton, sphinx-rtd-theme, sphinx-togglebutton, sphinx_design, sphinx-new-tab-link |
    Select-String "Name|Version"


| Name: Sphinx
Version: 9.1.0

| Name: sphinx-copybutton
Version: 0.5.2

| Name: sphinx_rtd_theme
Version: 3.1.0

| Name: sphinx-togglebutton
Version: 0.4.4

| Name: sphinx_design
Version: 0.7.0

| Name: sphinx-new-tab-link
Version: 0.8.1

----

Install Sphinx
------------------------------

* Press :kbd:`Win` + :kbd:`X` + :kbd:`C` to open the Command prompt.
* Install the Sphinx library.

.. code-block::

    pip install sphinx

* Install the Sphinx library using a specific version..

.. code-block::

    pip install sphinx==9.1.0


* To upgrade include the ``-U`` flag.

.. code-block::

    pip install -U sphinx


* Check the installed version with:

.. code-block::

    sphinx-build --version

----

Install the Sphinx theme for Read the Docs
------------------------------------------------------------

* The sphinx_rtd_theme is used by other RTD guides, so it is best to use for consistency of look and feel.
* To use ``sphinx_rtd_theme``, make the changes to the conf.py file that are detailed at :ref:`VSCode conf.py`.

* Install the Sphinx theme for read the docs.

.. code-block::

    pip install sphinx_rtd_theme

* To upgrade include the ``-U`` flag.

.. code-block::

    pip install -U sphinx_rtd_theme

* Check the installed version with:

.. code-block::

    pip show sphinx-rtd-theme

----

Install the sphinx-copybutton Extension
------------------------------------------------------------

* The sphinx-copybutton Extension adds a copy button to code blocks.
* To use ``sphinx-copybutton``, make the changes to the conf.py file that are detailed at :ref:`VSCode conf.py`.


* Install the Sphinx Extension: sphinx-copybutton:

.. code-block::

    pip install sphinx-copybutton

* To upgrade include the ``-U`` flag:

.. code-block::

    pip install -U sphinx-copybutton

* Check the installed version with:

.. code-block::

    pip show sphinx-copybutton

----

Install the sphinx-togglebutton Extension
------------------------------------------------------------

* The sphinx-togglebutton Extension adds the ability to Collapse Sphinx admonitions (notes, warnings, etc) so that their content is hidden until users click a toggle button.
* * To use ``sphinx-togglebutton``, make the changes to the conf.py file that are detailed at :ref:`VSCode conf.py`.

* Install the Sphinx Extension: sphinx-togglebutton:

.. code-block::

    pip install sphinx-togglebutton

* To upgrade include the ``-U`` flag:

.. code-block::

    pip install -U sphinx-togglebutton

* Check the installed version with:

.. code-block::

    pip show sphinx-togglebutton

----

Install the sphinx_design Extension
------------------------------------------------------------

* The sphinx_design Extension adds drop downs and tabs.
* To use ``sphinx_design``, make the changes to the conf.py file that are detailed at :ref:`VSCode conf.py`.

* Install the Sphinx Extension: sphinx_design:
*
.. code-block::

    pip install sphinx_design

* To upgrade include the ``-U`` flag:

.. code-block::

    pip install -U sphinx_design

* Check the installed version with:

.. code-block::

    pip show sphinx_design

----

Install the sphinx_new_tab_link Extension
------------------------------------------------------------

* The sphinx_new_tab_link Extension opens links in a new tab.
* To use ``sphinx_new_tab_link``, make the changes to the conf.py file that are detailed at :ref:`VSCode conf.py`.

.. code-block::

    pip install sphinx_new_tab_link

* To upgrade include the ``-U`` flag:

.. code-block::

    pip install -U sphinx_new_tab_link

* Check the installed version with:

.. code-block::

    pip show sphinx-new-tab-link


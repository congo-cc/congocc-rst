Sphinx Documentation Starter Pack
=================================

This guide covers some documentation.

The official home of this guide is TBD.

Compilation
-----------

For the compilation of the documentation, you need to use a version of Python which
supports the ``venv`` module, because the ``make html`` command will create a
virtual environment and will install the ``Sphinx`` package::

    make html

Python >= 3.10 should be fine.

The built HTML documents will be in the _build/html directory.

For PDF output, ensure that you have the following packages installed:

.. code-block:: bash

    sudo apt install fonts-freefont-otf latexmk python3-venv \
    texlive-fonts-recommended texlive-latex-recommended \
    texlive-latex-extra texlive-lang-greek \
    tex-gyre texlive-xetex

Then run

    make latexpdf

and inspect the _build/latex directory.

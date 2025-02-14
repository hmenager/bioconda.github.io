:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-tkwidgets'
.. highlight: bash

bioconductor-tkwidgets
======================

.. conda:recipe:: bioconductor-tkwidgets
   :replaces_section_title:

   Widgets to provide user interfaces. tcltk should have been installed for the widgets to run.

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/tkWidgets.html
   :license: Artistic-2.0
   :recipe: /`bioconductor-tkwidgets <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tkwidgets>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-tkwidgets/meta.yaml>`_

   


.. conda:package:: bioconductor-tkwidgets

   |downloads_bioconductor-tkwidgets| |docker_bioconductor-tkwidgets|

   :versions: 1.62.0-1, 1.62.0-0, 1.60.0-0
   
   :depends bioconductor-dyndoc: >=1.62.0,<1.63.0
   :depends bioconductor-widgettools: >=1.62.0,<1.63.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-tkwidgets

   and update with::

      conda update bioconductor-tkwidgets

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-tkwidgets:<tag>

   (see `bioconductor-tkwidgets/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-tkwidgets| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-tkwidgets.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-tkwidgets
   :alt:   (downloads)
.. |docker_bioconductor-tkwidgets| image:: https://quay.io/repository/biocontainers/bioconductor-tkwidgets/status
   :target: https://quay.io/repository/biocontainers/bioconductor-tkwidgets
.. _`bioconductor-tkwidgets/tags`: https://quay.io/repository/biocontainers/bioconductor-tkwidgets?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-tkwidgets/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-tkwidgets/README.html
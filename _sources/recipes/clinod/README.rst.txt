:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'clinod'
.. highlight: bash

clinod
======

.. conda:recipe:: clinod
   :replaces_section_title:

   Command line NoD \(clinod\)\, for  predicting nucleolar localization sequences.

   :homepage: http://www.compbio.dundee.ac.uk/nod
   :license: Apache License, Version 2.0 + others used internally
   :recipe: /`clinod <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/clinod>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/clinod/meta.yaml>`_

   


.. conda:package:: clinod

   |downloads_clinod| |docker_clinod|

   :versions: 1.3-2, 1.3-1, 1.3-0
   
   :depends openjdk: >=6
   :depends python: 
   :depends snns: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install clinod

   and update with::

      conda update clinod

   or use the docker container::

      docker pull quay.io/biocontainers/clinod:<tag>

   (see `clinod/tags`_ for valid values for ``<tag>``)


.. |downloads_clinod| image:: https://img.shields.io/conda/dn/bioconda/clinod.svg?style=flat
   :target: https://anaconda.org/bioconda/clinod
   :alt:   (downloads)
.. |docker_clinod| image:: https://quay.io/repository/biocontainers/clinod/status
   :target: https://quay.io/repository/biocontainers/clinod
.. _`clinod/tags`: https://quay.io/repository/biocontainers/clinod?tab=tags






Notes
-----
Command line NoD \(clinod\) is Java program which is packaged with a custom
wrapper shell script. This shell wrapper is called \"clinod\" and is on \$PATH
by default. By default \"\-Xms512m \-Xmx1g\" is set in the wrapper. If you want
to overwrite it you can specify these values directly after your binaries.
If you have \_JAVA\_OPTIONS set globally this will take precedence.
For example run it with \"clinod \-Xms512m \-Xmx1g ...\"


Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/clinod/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/clinod/README.html
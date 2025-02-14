:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'mothur'
.. highlight: bash

mothur
======

.. conda:recipe:: mothur
   :replaces_section_title:

   This project seeks to develop a single piece of open\-source\, expandable software to fill the bioinformatics needs of the microbial ecology community.

   :homepage: http://www.mothur.org
   :developer docs: https://github.com/mothur/mothur
   :license: GPL / GPL-3.0
   :recipe: /`mothur <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mothur>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/mothur/meta.yaml>`_
   :links: doi: :doi:`10.1128/AEM.01541-09`

   


.. conda:package:: mothur

   |downloads_mothur| |docker_mothur|

   :versions: 1.42.3-0, 1.42.1-0, 1.42.0-0, 1.41.3-0, 1.41.0-0, 1.40.5-0, 1.39.5-4, 1.39.5-3, 1.39.5-2, 1.39.5-1, 1.39.5-0, 1.38.1.1-0, 1.36.1-2, 1.36.1-1, 1.36.1-0, 1.25.0-0
   
   :depends blast-legacy: 
   :depends boost: >=1.70.0,<1.70.1.0a0
   :depends boost-cpp: >=1.70.0,<1.70.1.0a0
   :depends gsl: >=2.5,<2.6.0a0
   :depends hdf5: >=1.10.5,<1.10.6.0a0
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends readline: >=8.0,<9.0a0
   :depends vsearch: 2.13.3.*
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install mothur

   and update with::

      conda update mothur

   or use the docker container::

      docker pull quay.io/biocontainers/mothur:<tag>

   (see `mothur/tags`_ for valid values for ``<tag>``)


.. |downloads_mothur| image:: https://img.shields.io/conda/dn/bioconda/mothur.svg?style=flat
   :target: https://anaconda.org/bioconda/mothur
   :alt:   (downloads)
.. |docker_mothur| image:: https://quay.io/repository/biocontainers/mothur/status
   :target: https://quay.io/repository/biocontainers/mothur
.. _`mothur/tags`: https://quay.io/repository/biocontainers/mothur?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/mothur/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/mothur/README.html
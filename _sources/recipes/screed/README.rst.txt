:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'screed'
.. highlight: bash

screed
======

.. conda:recipe:: screed
   :replaces_section_title:

   Screed is a biological sequence parsing and storage\/retrieval library for DNA and protein sequences.

   :homepage: http://github.com/dib-lab/screed/
   :license: BSD / BSD
   :recipe: /`screed <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/screed>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/screed/meta.yaml>`_

   


.. conda:package:: screed

   |downloads_screed| |docker_screed|

   :versions: 1.0.1-0, 1.0-1, 1.0-0, 0.9-1, 0.9-0
   
   :depends bz2file: 
   :depends python: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install screed

   and update with::

      conda update screed

   or use the docker container::

      docker pull quay.io/biocontainers/screed:<tag>

   (see `screed/tags`_ for valid values for ``<tag>``)


.. |downloads_screed| image:: https://img.shields.io/conda/dn/bioconda/screed.svg?style=flat
   :target: https://anaconda.org/bioconda/screed
   :alt:   (downloads)
.. |docker_screed| image:: https://quay.io/repository/biocontainers/screed/status
   :target: https://quay.io/repository/biocontainers/screed
.. _`screed/tags`: https://quay.io/repository/biocontainers/screed?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/screed/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/screed/README.html
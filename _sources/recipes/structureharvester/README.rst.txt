:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'structureharvester'
.. highlight: bash

structureharvester
==================

.. conda:recipe:: structureharvester
   :replaces_section_title:

   structureHarvester.py is a Python script capable of extracting all the relevant data from STRUCTURE results files

   :homepage: http://alumni.soe.ucsc.edu/~dearl/software/structureHarvester/
   :license: MIT
   :recipe: /`structureharvester <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/structureharvester>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/structureharvester/meta.yaml>`_

   


.. conda:package:: structureharvester

   |downloads_structureharvester| |docker_structureharvester|

   :versions: 0.6.94-1, 0.6.94-0
   
   :depends python: >=2.7,<2.8.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install structureharvester

   and update with::

      conda update structureharvester

   or use the docker container::

      docker pull quay.io/biocontainers/structureharvester:<tag>

   (see `structureharvester/tags`_ for valid values for ``<tag>``)


.. |downloads_structureharvester| image:: https://img.shields.io/conda/dn/bioconda/structureharvester.svg?style=flat
   :target: https://anaconda.org/bioconda/structureharvester
   :alt:   (downloads)
.. |docker_structureharvester| image:: https://quay.io/repository/biocontainers/structureharvester/status
   :target: https://quay.io/repository/biocontainers/structureharvester
.. _`structureharvester/tags`: https://quay.io/repository/biocontainers/structureharvester?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/structureharvester/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/structureharvester/README.html
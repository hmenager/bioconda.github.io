:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'apollo'
.. highlight: bash

apollo
======

.. conda:recipe:: apollo
   :replaces_section_title:

   WebApollo API library

   :homepage: https://github.com/galaxy-genome-annotation/python-apollo
   :license: MIT / MIT
   :recipe: /`apollo <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/apollo>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/apollo/meta.yaml>`_

   


.. conda:package:: apollo

   |downloads_apollo| |docker_apollo|

   :versions: 3.1-0, 3.0.4-0
   
   :depends biopython: 
   :depends cachetools: 
   :depends click: >=6.7
   :depends decorator: 
   :depends python: 
   :depends pyyaml: 
   :depends requests: 
   :depends wrapt: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install apollo

   and update with::

      conda update apollo

   or use the docker container::

      docker pull quay.io/biocontainers/apollo:<tag>

   (see `apollo/tags`_ for valid values for ``<tag>``)


.. |downloads_apollo| image:: https://img.shields.io/conda/dn/bioconda/apollo.svg?style=flat
   :target: https://anaconda.org/bioconda/apollo
   :alt:   (downloads)
.. |docker_apollo| image:: https://quay.io/repository/biocontainers/apollo/status
   :target: https://quay.io/repository/biocontainers/apollo
.. _`apollo/tags`: https://quay.io/repository/biocontainers/apollo?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/apollo/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/apollo/README.html
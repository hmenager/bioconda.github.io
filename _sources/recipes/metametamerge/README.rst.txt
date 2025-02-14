:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'metametamerge'
.. highlight: bash

metametamerge
=============

.. conda:recipe:: metametamerge
   :replaces_section_title:

   Merging module of the MetaMeta Pipeline

   :homepage: https://github.com/pirovc/metametamerge/
   :license: The MIT License (MIT)
   :recipe: /`metametamerge <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/metametamerge>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/metametamerge/meta.yaml>`_

   


.. conda:package:: metametamerge

   |downloads_metametamerge| |docker_metametamerge|

   :versions: 1.1-1, 1.1-0, 1.0-1, 1.0-0
   
   :depends numpy: >=1.9.0
   :depends pandas: 
   :depends python: >=3.5,<3.6.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install metametamerge

   and update with::

      conda update metametamerge

   or use the docker container::

      docker pull quay.io/biocontainers/metametamerge:<tag>

   (see `metametamerge/tags`_ for valid values for ``<tag>``)


.. |downloads_metametamerge| image:: https://img.shields.io/conda/dn/bioconda/metametamerge.svg?style=flat
   :target: https://anaconda.org/bioconda/metametamerge
   :alt:   (downloads)
.. |docker_metametamerge| image:: https://quay.io/repository/biocontainers/metametamerge/status
   :target: https://quay.io/repository/biocontainers/metametamerge
.. _`metametamerge/tags`: https://quay.io/repository/biocontainers/metametamerge?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/metametamerge/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/metametamerge/README.html
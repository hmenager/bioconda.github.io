:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'azure-cli'
.. highlight: bash

azure-cli
=========

.. conda:recipe:: azure-cli
   :replaces_section_title:

   Microsoft Azure Cross Platform Command Line

   :homepage: https://github.com/azure/azure-xplat-cli
   :license: Apache v2.0
   :recipe: /`azure-cli <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/azure-cli>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/azure-cli/meta.yaml>`_

   


.. conda:package:: azure-cli

   |downloads_azure-cli| |docker_azure-cli|

   :versions: 0.10.3-0
   
   :depends nodejs: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install azure-cli

   and update with::

      conda update azure-cli

   or use the docker container::

      docker pull quay.io/biocontainers/azure-cli:<tag>

   (see `azure-cli/tags`_ for valid values for ``<tag>``)


.. |downloads_azure-cli| image:: https://img.shields.io/conda/dn/bioconda/azure-cli.svg?style=flat
   :target: https://anaconda.org/bioconda/azure-cli
   :alt:   (downloads)
.. |docker_azure-cli| image:: https://quay.io/repository/biocontainers/azure-cli/status
   :target: https://quay.io/repository/biocontainers/azure-cli
.. _`azure-cli/tags`: https://quay.io/repository/biocontainers/azure-cli?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/azure-cli/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/azure-cli/README.html
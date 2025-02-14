:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'smafa'
.. highlight: bash

smafa
=====

.. conda:recipe:: smafa
   :replaces_section_title:

   smafa is a tool for querying and clustering pre\-aligned small pre\-aligned DNA and amino acid sequences.

   :homepage: https://github.com/wwood/smafa
   :license: GPL3
   :recipe: /`smafa <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/smafa>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/smafa/meta.yaml>`_

   


.. conda:package:: smafa

   |downloads_smafa| |docker_smafa|

   :versions: 0.5.0-0
   
   :depends libgcc-ng: >=7.3.0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install smafa

   and update with::

      conda update smafa

   or use the docker container::

      docker pull quay.io/biocontainers/smafa:<tag>

   (see `smafa/tags`_ for valid values for ``<tag>``)


.. |downloads_smafa| image:: https://img.shields.io/conda/dn/bioconda/smafa.svg?style=flat
   :target: https://anaconda.org/bioconda/smafa
   :alt:   (downloads)
.. |docker_smafa| image:: https://quay.io/repository/biocontainers/smafa/status
   :target: https://quay.io/repository/biocontainers/smafa
.. _`smafa/tags`: https://quay.io/repository/biocontainers/smafa?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/smafa/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/smafa/README.html
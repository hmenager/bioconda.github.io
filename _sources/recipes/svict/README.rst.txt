:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'svict'
.. highlight: bash

svict
=====

.. conda:recipe:: svict
   :replaces_section_title:

   SViCT is a computational tool for detecting structural variations from cell free DNA \(cfDNA\) containing low dilutions of circulating tumor DNA \(ctDNA\).

   :homepage: https://github.com/vpc-ccg/svict
   :license: Apache-2.0
   :recipe: /`svict <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/svict>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/svict/meta.yaml>`_

   


.. conda:package:: svict

   |downloads_svict| |docker_svict|

   :versions: 1.0.1-0, 1.0.0-1
   
   :depends libgcc-ng: >=7.3.0
   :depends libstdcxx-ng: >=7.3.0
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install svict

   and update with::

      conda update svict

   or use the docker container::

      docker pull quay.io/biocontainers/svict:<tag>

   (see `svict/tags`_ for valid values for ``<tag>``)


.. |downloads_svict| image:: https://img.shields.io/conda/dn/bioconda/svict.svg?style=flat
   :target: https://anaconda.org/bioconda/svict
   :alt:   (downloads)
.. |docker_svict| image:: https://quay.io/repository/biocontainers/svict/status
   :target: https://quay.io/repository/biocontainers/svict
.. _`svict/tags`: https://quay.io/repository/biocontainers/svict?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/svict/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/svict/README.html
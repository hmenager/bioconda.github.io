:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'soapdenovo2-gapcloser'
.. highlight: bash

soapdenovo2-gapcloser
=====================

.. conda:recipe:: soapdenovo2-gapcloser
   :replaces_section_title:

   a tool named GapCloser for SOAPdenovo.

   :homepage: http://soap.genomics.org.cn/soapdenovo.html
   :license: GNU
   :recipe: /`soapdenovo2-gapcloser <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/soapdenovo2-gapcloser>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/soapdenovo2-gapcloser/meta.yaml>`_

   


.. conda:package:: soapdenovo2-gapcloser

   |downloads_soapdenovo2-gapcloser| |docker_soapdenovo2-gapcloser|

   :versions: 1.12-2, 1.12-1, 1.12-0
   
   :depends libstdcxx-ng: >=4.9
   :depends zlib: >=1.2.11,<1.3.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install soapdenovo2-gapcloser

   and update with::

      conda update soapdenovo2-gapcloser

   or use the docker container::

      docker pull quay.io/biocontainers/soapdenovo2-gapcloser:<tag>

   (see `soapdenovo2-gapcloser/tags`_ for valid values for ``<tag>``)


.. |downloads_soapdenovo2-gapcloser| image:: https://img.shields.io/conda/dn/bioconda/soapdenovo2-gapcloser.svg?style=flat
   :target: https://anaconda.org/bioconda/soapdenovo2-gapcloser
   :alt:   (downloads)
.. |docker_soapdenovo2-gapcloser| image:: https://quay.io/repository/biocontainers/soapdenovo2-gapcloser/status
   :target: https://quay.io/repository/biocontainers/soapdenovo2-gapcloser
.. _`soapdenovo2-gapcloser/tags`: https://quay.io/repository/biocontainers/soapdenovo2-gapcloser?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/soapdenovo2-gapcloser/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/soapdenovo2-gapcloser/README.html
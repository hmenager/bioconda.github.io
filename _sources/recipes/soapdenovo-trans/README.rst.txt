:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'soapdenovo-trans'
.. highlight: bash

soapdenovo-trans
================

.. conda:recipe:: soapdenovo-trans
   :replaces_section_title:

   SOAPdenovo\-Trans is a de novo transcriptome assembler basing on the SOAPdenovo framework\, adapt to alternative splicing and different expression level among transcripts.

   :homepage: http://soap.genomics.org.cn/SOAPdenovo-Trans.html
   :license: GPLv3
   :recipe: /`soapdenovo-trans <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/soapdenovo-trans>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/soapdenovo-trans/meta.yaml>`_

   


.. conda:package:: soapdenovo-trans

   |downloads_soapdenovo-trans| |docker_soapdenovo-trans|

   :versions: 1.04-2, 1.04-1, 1.04-0
   
   :depends libgcc-ng: >=4.9
   :depends zlib: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install soapdenovo-trans

   and update with::

      conda update soapdenovo-trans

   or use the docker container::

      docker pull quay.io/biocontainers/soapdenovo-trans:<tag>

   (see `soapdenovo-trans/tags`_ for valid values for ``<tag>``)


.. |downloads_soapdenovo-trans| image:: https://img.shields.io/conda/dn/bioconda/soapdenovo-trans.svg?style=flat
   :target: https://anaconda.org/bioconda/soapdenovo-trans
   :alt:   (downloads)
.. |docker_soapdenovo-trans| image:: https://quay.io/repository/biocontainers/soapdenovo-trans/status
   :target: https://quay.io/repository/biocontainers/soapdenovo-trans
.. _`soapdenovo-trans/tags`: https://quay.io/repository/biocontainers/soapdenovo-trans?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/soapdenovo-trans/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/soapdenovo-trans/README.html
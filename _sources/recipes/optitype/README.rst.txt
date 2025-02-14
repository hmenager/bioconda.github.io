:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'optitype'
.. highlight: bash

optitype
========

.. conda:recipe:: optitype
   :replaces_section_title:

   Precision HLA typing from next\-generation sequencing data

   :homepage: https://github.com/FRED-2/OptiType
   :license: BSD
   :recipe: /`optitype <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/optitype>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/optitype/meta.yaml>`_

   


.. conda:package:: optitype

   |downloads_optitype| |docker_optitype|

   :versions: 1.3.2-3, 1.3.2-2, 1.3.2-1, 1.3.1-0, 1.2.1-1, 1.2.1-0, 1.2-0
   
   :depends future: 
   :depends glpk: 
   :depends hdf5: 
   :depends matplotlib: 
   :depends numpy: 1.15.4.*
   :depends pandas: 
   :depends pyomo: 
   :depends pysam: 
   :depends pytables: 
   :depends python: >=2.7,<2.8.0a0
   :depends razers3: 
   :depends samtools: 
   :depends six: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install optitype

   and update with::

      conda update optitype

   or use the docker container::

      docker pull quay.io/biocontainers/optitype:<tag>

   (see `optitype/tags`_ for valid values for ``<tag>``)


.. |downloads_optitype| image:: https://img.shields.io/conda/dn/bioconda/optitype.svg?style=flat
   :target: https://anaconda.org/bioconda/optitype
   :alt:   (downloads)
.. |docker_optitype| image:: https://quay.io/repository/biocontainers/optitype/status
   :target: https://quay.io/repository/biocontainers/optitype
.. _`optitype/tags`: https://quay.io/repository/biocontainers/optitype?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/optitype/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/optitype/README.html
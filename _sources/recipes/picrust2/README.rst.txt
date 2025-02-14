:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'picrust2'
.. highlight: bash

picrust2
========

.. conda:recipe:: picrust2
   :replaces_section_title:

   PICRUSt\: Phylogenetic Investigation of Communities by Reconstruction of Unobserved States

   :homepage: https://github.com/picrust/picrust2
   :license: GNU General Public License v3.0
   :recipe: /`picrust2 <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/picrust2>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/picrust2/meta.yaml>`_

   


.. conda:package:: picrust2

   |downloads_picrust2| |docker_picrust2|

   :versions: 2.2.0_b-0, 2.1.4_b-0, 2.1.3_b-0, 2.1.2_b-0, 2.1.1_b-0, 2.1.0_b-0, 2.0.3_b-0
   
   :depends biom-format: >=2.1.7
   :depends epa-ng: 0.3.5.*
   :depends gappa: 0.4.0.*
   :depends glpk: 4.65.*
   :depends h5py: >=2.9.0
   :depends hmmer: 3.2.1.*
   :depends joblib: >=0.13.1
   :depends numpy: >=1.16.2
   :depends pandas: >=0.24.2
   :depends pytest: >=4.4.1
   :depends pytest-cov: >=2.6.1
   :depends python: >=3.5,<3.7
   :depends r-base: >=3.5.1
   :depends r-castor: 1.4.1.*
   :depends scipy: >=1.2.1
   :depends wget: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install picrust2

   and update with::

      conda update picrust2

   or use the docker container::

      docker pull quay.io/biocontainers/picrust2:<tag>

   (see `picrust2/tags`_ for valid values for ``<tag>``)


.. |downloads_picrust2| image:: https://img.shields.io/conda/dn/bioconda/picrust2.svg?style=flat
   :target: https://anaconda.org/bioconda/picrust2
   :alt:   (downloads)
.. |docker_picrust2| image:: https://quay.io/repository/biocontainers/picrust2/status
   :target: https://quay.io/repository/biocontainers/picrust2
.. _`picrust2/tags`: https://quay.io/repository/biocontainers/picrust2?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/picrust2/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/picrust2/README.html
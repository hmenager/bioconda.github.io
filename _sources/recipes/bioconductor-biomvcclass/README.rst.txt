:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'bioconductor-biomvcclass'
.. highlight: bash

bioconductor-biomvcclass
========================

.. conda:recipe:: bioconductor-biomvcclass
   :replaces_section_title:

   Creates classes used in model\-view\-controller \(MVC\) design

   :homepage: https://bioconductor.org/packages/3.9/bioc/html/BioMVCClass.html
   :license: LGPL
   :recipe: /`bioconductor-biomvcclass <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-biomvcclass>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/bioconductor-biomvcclass/meta.yaml>`_
   :links: biotools: :biotools:`biomvcclass`, doi: :doi:`10.1038/nmeth.3252`

   


.. conda:package:: bioconductor-biomvcclass

   |downloads_bioconductor-biomvcclass| |docker_bioconductor-biomvcclass|

   :versions: 1.52.0-1, 1.50.0-0, 1.48.0-0, 1.46.0-0
   
   :depends bioconductor-biobase: >=2.44.0,<2.45.0
   :depends bioconductor-graph: >=1.62.0,<1.63.0
   :depends bioconductor-mvcclass: >=1.58.0,<1.59.0
   :depends bioconductor-rgraphviz: >=2.28.0,<2.29.0
   :depends r-base: >=3.6,<3.7.0a0
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install bioconductor-biomvcclass

   and update with::

      conda update bioconductor-biomvcclass

   or use the docker container::

      docker pull quay.io/biocontainers/bioconductor-biomvcclass:<tag>

   (see `bioconductor-biomvcclass/tags`_ for valid values for ``<tag>``)


.. |downloads_bioconductor-biomvcclass| image:: https://img.shields.io/conda/dn/bioconda/bioconductor-biomvcclass.svg?style=flat
   :target: https://anaconda.org/bioconda/bioconductor-biomvcclass
   :alt:   (downloads)
.. |docker_bioconductor-biomvcclass| image:: https://quay.io/repository/biocontainers/bioconductor-biomvcclass/status
   :target: https://quay.io/repository/biocontainers/bioconductor-biomvcclass
.. _`bioconductor-biomvcclass/tags`: https://quay.io/repository/biocontainers/bioconductor-biomvcclass?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/bioconductor-biomvcclass/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/bioconductor-biomvcclass/README.html
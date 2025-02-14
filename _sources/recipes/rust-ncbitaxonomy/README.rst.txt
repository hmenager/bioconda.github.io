:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'rust-ncbitaxonomy'
.. highlight: bash

rust-ncbitaxonomy
=================

.. conda:recipe:: rust-ncbitaxonomy
   :replaces_section_title:

   A Rust crate for working with a local copy of the NCBI Taxonomy database\, which provides the taxonomy\_filter\_refseq commmand

   :homepage: https://github.com/pvanheus/ncbitaxonomy
   :documentation: https://docs.rs/crate/ncbitaxonomy/0.1.5
   
   :license: MIT
   :recipe: /`rust-ncbitaxonomy <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/rust-ncbitaxonomy>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/rust-ncbitaxonomy/meta.yaml>`_

   


.. conda:package:: rust-ncbitaxonomy

   |downloads_rust-ncbitaxonomy| |docker_rust-ncbitaxonomy|

   :versions: 0.1.5-0, 0.1.4-0, 0.1.3-0
   
   :depends libgcc-ng: >=4.9
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install rust-ncbitaxonomy

   and update with::

      conda update rust-ncbitaxonomy

   or use the docker container::

      docker pull quay.io/biocontainers/rust-ncbitaxonomy:<tag>

   (see `rust-ncbitaxonomy/tags`_ for valid values for ``<tag>``)


.. |downloads_rust-ncbitaxonomy| image:: https://img.shields.io/conda/dn/bioconda/rust-ncbitaxonomy.svg?style=flat
   :target: https://anaconda.org/bioconda/rust-ncbitaxonomy
   :alt:   (downloads)
.. |docker_rust-ncbitaxonomy| image:: https://quay.io/repository/biocontainers/rust-ncbitaxonomy/status
   :target: https://quay.io/repository/biocontainers/rust-ncbitaxonomy
.. _`rust-ncbitaxonomy/tags`: https://quay.io/repository/biocontainers/rust-ncbitaxonomy?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/rust-ncbitaxonomy/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/rust-ncbitaxonomy/README.html
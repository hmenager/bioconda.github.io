:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'onto2nx'
.. highlight: bash

onto2nx
=======

.. conda:recipe:: onto2nx
   :replaces_section_title:

   A package for parsing ontologies in the OWL and OBO format into NetworkX graphs

   :homepage: https://github.com/cthoyt/onto2nx
   :documentation: https://onto2nx.readthedocs.io/en/latest/
   
   :license: GPL / GPL 3.0
   :recipe: /`onto2nx <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/onto2nx>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/onto2nx/meta.yaml>`_

   


.. conda:package:: onto2nx

   |downloads_onto2nx| |docker_onto2nx|

   :versions: 0.1.1-0, 0.1.0-0
   
   :depends click: 
   :depends networkx: 1.11
   :depends python: 
   :depends rdflib: 4.2.1
   :depends rdflib-jsonld: 
   :depends requests: 
   :depends requests-file: 
   :depends sparqlwrapper: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install onto2nx

   and update with::

      conda update onto2nx

   or use the docker container::

      docker pull quay.io/biocontainers/onto2nx:<tag>

   (see `onto2nx/tags`_ for valid values for ``<tag>``)


.. |downloads_onto2nx| image:: https://img.shields.io/conda/dn/bioconda/onto2nx.svg?style=flat
   :target: https://anaconda.org/bioconda/onto2nx
   :alt:   (downloads)
.. |docker_onto2nx| image:: https://quay.io/repository/biocontainers/onto2nx/status
   :target: https://quay.io/repository/biocontainers/onto2nx
.. _`onto2nx/tags`: https://quay.io/repository/biocontainers/onto2nx?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/onto2nx/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/onto2nx/README.html
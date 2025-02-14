:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'talloc'
.. highlight: bash

talloc
======

.. conda:recipe:: talloc
   :replaces_section_title:

   talloc is a hierarchical\, reference counted memory pool system with destructors.

   :homepage: https://talloc.samba.org/talloc/doc/html/index.html`
   :license: LGPL-3.0
   :recipe: /`talloc <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/talloc>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/talloc/meta.yaml>`_

   


.. conda:package:: talloc

   |downloads_talloc| |docker_talloc|

   :versions: 2.1.9-0
   
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install talloc

   and update with::

      conda update talloc

   or use the docker container::

      docker pull quay.io/biocontainers/talloc:<tag>

   (see `talloc/tags`_ for valid values for ``<tag>``)


.. |downloads_talloc| image:: https://img.shields.io/conda/dn/bioconda/talloc.svg?style=flat
   :target: https://anaconda.org/bioconda/talloc
   :alt:   (downloads)
.. |docker_talloc| image:: https://quay.io/repository/biocontainers/talloc/status
   :target: https://quay.io/repository/biocontainers/talloc
.. _`talloc/tags`: https://quay.io/repository/biocontainers/talloc?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/talloc/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/talloc/README.html
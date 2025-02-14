:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'biomaj'
.. highlight: bash

biomaj
======

.. conda:recipe:: biomaj
   :replaces_section_title:

   Automates the update cycle and the supervision of the locally mirrored databank repository

   :homepage: http://biomaj.genouest.org
   :license: AGPL / GNU Affero General Public License v3 or later (AGPLv3+)
   :recipe: /`biomaj <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biomaj>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/biomaj/meta.yaml>`_
   :links: biotools: :biotools:`biomaj`, doi: :doi:`10.1093/bioinformatics/btn325`

   


.. conda:package:: biomaj

   |downloads_biomaj| |docker_biomaj|

   :versions: 3.0.19-0
   
   :depends bcrypt: 
   :depends drmaa: 
   :depends elasticsearch: 
   :depends future: 
   :depends ldap3: 
   :depends pycurl: 
   :depends pymongo: 
   :depends python: 2.7*
   :depends tabulate: 
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install biomaj

   and update with::

      conda update biomaj

   or use the docker container::

      docker pull quay.io/biocontainers/biomaj:<tag>

   (see `biomaj/tags`_ for valid values for ``<tag>``)


.. |downloads_biomaj| image:: https://img.shields.io/conda/dn/bioconda/biomaj.svg?style=flat
   :target: https://anaconda.org/bioconda/biomaj
   :alt:   (downloads)
.. |docker_biomaj| image:: https://quay.io/repository/biocontainers/biomaj/status
   :target: https://quay.io/repository/biocontainers/biomaj
.. _`biomaj/tags`: https://quay.io/repository/biocontainers/biomaj?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/biomaj/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/biomaj/README.html
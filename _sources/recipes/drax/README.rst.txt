:orphan:  .. only available via index, not via toctree

.. title:: Package Recipe 'drax'
.. highlight: bash

drax
====

.. conda:recipe:: drax
   :replaces_section_title:

   A pipeline for Detecting Resistome Associated taXa.

   :homepage: https://github.com/will-rowe/drax
   :license: MIT
   :recipe: /`drax <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/drax>`_/`meta.yaml <https://github.com/bioconda/bioconda-recipes/tree/master/recipes/drax/meta.yaml>`_

   


.. conda:package:: drax

   |downloads_drax| |docker_drax|

   :versions: 0.0.0-2, 0.0.0-1, 0.0.0-0
   
   :depends bbmap: 37.90
   :depends fastp: 0.12.4
   :depends fastqc: 0.11.7
   :depends groot: 0.5
   :depends kaiju: 1.6.2
   :depends krona: 2.7
   :depends metacherchant: 0.1.0
   :depends multiqc: 1.4
   :depends nextflow: 0.27.6
   :depends r-essentials: 1.7.0
   :depends samtools: 1.4
   :depends seqkit: 0.7.2
   :requirements:

   .. rubric:: Installation

   With an activated Bioconda channel (see :ref:`set-up-channels`), install with::

      conda install drax

   and update with::

      conda update drax

   or use the docker container::

      docker pull quay.io/biocontainers/drax:<tag>

   (see `drax/tags`_ for valid values for ``<tag>``)


.. |downloads_drax| image:: https://img.shields.io/conda/dn/bioconda/drax.svg?style=flat
   :target: https://anaconda.org/bioconda/drax
   :alt:   (downloads)
.. |docker_drax| image:: https://quay.io/repository/biocontainers/drax/status
   :target: https://quay.io/repository/biocontainers/drax
.. _`drax/tags`: https://quay.io/repository/biocontainers/drax?tab=tags







Link to this page
-----------------

Render an |install-with-bioconda| badge with the following MarkDown::

   [![install with bioconda](https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat)](http://bioconda.github.io/recipes/drax/README.html)

.. |install-with-bioconda| image:: https://img.shields.io/badge/install%20with-bioconda-brightgreen.svg?style=flat
   :target: http://bioconda.github.io/recipes/drax/README.html
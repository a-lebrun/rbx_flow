# RecobundlesX pipeline
===================

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/scilus/rbx_flow)](https://github.com/scilus/rbx_flow/releases)

[![Nextflow](https://img.shields.io/badge/nextflow-21.10.6-brightgreen.svg)](https://www.nextflow.io/)
[![Docker container badge](https://img.shields.io/docker/v/scilus/scilus?label=docker&logo=docker&logoColor=white)](https://hub.docker.com/r/scilus/scilus)

Run the RecobundlesX pipeline.
To access the example atlases:
https://zenodo.org/records/10103446

If you use this pipeline, please cite:

```
St-Onge, Etienne, Kurt G. Schilling, and Francois Rheault. "BundleSeg: A versatile, 
reliable and reproducible approach to white matter bundle segmentation." International 
Workshop on Computational Diffusion MRI. Cham: Springer Nature Switzerland, (2023)

Rheault, Francois. Analyse et reconstruction de faisceaux de la matière blanche.
page 137-170, (2020), https://savoirs.usherbrooke.ca/handle/11143/17255

Kurtzer GM, Sochat V, Bauer MW Singularity: Scientific containers for
mobility of compute. PLoS ONE 12(5): e0177459 (2017)
https://doi.org/10.1371/journal.pone.0177459

P. Di Tommaso, et al. Nextflow enables reproducible computational workflows.
Nature Biotechnology 35, 316–319 (2017) https://doi.org/10.1038/nbt.3820
```

Requirements
------------

- [Nextflow](https://www.nextflow.io)
- [scilpy](https://github.com/scilus/scilpy)
- [ants](https://github.com/ANTsX/ANTs)

Singularity/Docker
-----------
If you are on Linux, we recommend using the Singularity to run rbx_flow pipeline.
If you have Apptainer (Singularity) launch your Nextflow command with:
`-with-singularity ABSOLUTE_PATH/scilus_2.1.0.sif`

Image is available [here](https://scil.usherbrooke.ca/pages/containers/)

If you are on MacOS or Windows, we recommend using the Docker container to run rbx_flow pipeline.
Launch your Nextflow command with:
`-with-docker scilus/scilus:2.1.0`

Usage
-----

See *USAGE* or run `nextflow run main.nf --help`


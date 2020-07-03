[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/4415)

# Singularity images

## SingIMG:R36_NanoBAC
R v3.6.3 with NanoBAC package
Install: `singularity build nanobac.sif shub://pgpmartin/SingIMG:r36_nanobac`
To run Rscript: `singularity run nanobac.sif -e '2+2'`
To use R interactively: `singularity exec nanobac.sif R`
To use R or Rscript in a shell: `singularity shell nanobac.sif`


## SingIMG:guppy v4.0.11
Oxford Nanopore basecaller guppy v4.0.11
Install: `singularity build guppy.sif shub://pgpmartin/SingIMG:guppy_4.0.1`
Use: `singularity exec --nv guppy.sif guppy_basecaller -h`



# Steps

cd .../bio/geovar_rep_paper

conda create -n geodist python=3.12

conda activate geodist

conda install -c bioconda snakemake-minimal

conda install -c bioconda htslib

conda install -c conda-forge wget   # or use system wget if already installed

pip install -e .


  660  git branch

  661  git checkout master

  662  git checkout -b test

  663  ls

  664  conda env create -f config/env_geodist.yml

  665  conda activate geodist2

  666  export PYTHONPATH=$PWD/src:$PYTHONPATH

  667  echo $PYTHONPATH

  668  snakemake gen_all_plots --cores 10

  669  git status

  670  git add -u


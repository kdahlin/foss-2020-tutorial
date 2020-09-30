# foss-2020-tutorial
working through fundamentals of open source course
    1  cd /scratch
    2  ls -lrt
    3  df -h
    4  git clone https://github.com/kdahlin/foss-2020-tutorial.git
    5  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
    6  ls
    7  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
    8  ln -s /opt/conda/pkgs/*/bin/* /bin
    9  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   10  clear
   11  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   12  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   13  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/foss-2020-tutorial/'
   14  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/foss-2020-tutorial/'
   15  cd /scratch
   16  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/foss-2020-tutorial/'
   17  /opt/conda/bin/conda search -c bioconda snakemake
   18  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   19  ln -s /opt/conda/bin/* /bin
   20  ln -s /opt/conda/lib/* /usr/lib
   21  snakemake --version
   22  git clone "https://github.com/kdahlin/foss-2020-tutorial.git"
   23  ls -lrt
   24  cd /foss-2020-tutorial
   25  cd foss-2020-tutorial
   26  ls -lrt
   27  history >>README.md

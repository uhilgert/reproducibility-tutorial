# reproducibility-tutorial
FOSS 2020 Reproducibility Tutorial
    1  ls
    2  cd /scratch
    3  git clone https://github.com/uhilgert/reproducibility-tutorial.git
    4  ls
    5  df -h
    6  df man
    7  df --help
    8  clear
    9  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   10  ash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   11  b
   12  bash Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   13  ls
   14  ln -s /opt/conda/pkgs/*/bin/* /bin
   15  ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   16  ls
   17  df -h
   18  /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   19  ls -l
   20  opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   21  /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   22  ls -l
   23  /opt/conda/bin/pip install bash_kernel
   24  /opt/conda/bin/pip install ipykernel
   25  /opt/conda/bin/python3 -m bash_kernel.install
   26  ls -l
   27  df -h
   28  clear
   29  /opt/conda/bin/conda search python
   30  conda search python
   31  /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   32  /opt/conda/bin/conda search -c bioconda snakemake
   33  /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   34  ln -s /opt/conda/bin/* /bin
   35  ln -s /opt/conda/lib/* /usr/lib
   36  snakemake --version
   37  sudo apt-get update
   38  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   39  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   40  sudo add-apt-repository  "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
 $(lsb_release -cs) \
 stable"
   41  sudo apt-get update
   42  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   43  docker run hello-world
   44  df -h
   45  cd /scratch/reproducibility-tutorial/
   46  ls -l
   47  ls
   48  history
   49  history >> README.md

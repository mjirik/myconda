# myconda


window users only

        conda install unxutils

all users

        conda install conda-build anaconda-client
        # conda config --set anaconda_upload yes
        
        conda config --add channels mjirik
        anaconda login
        

## io3d

        conda skeleton pypi io3d
        conda build io3d
        
        cd /home/mjirik/miniconda/conda-bld
        conda convert /linux-64/io3d-1.0.23-py27_0.tar.bz2 -p all
        binstar upload */linux-64/io3d-1.0.23-py27_0.tar.bz2


## after

        
        conda convert ~/miniconda/conda-bld/osx-64/cookiecutter-0.9.1_BUILDNUM.tar.bz2 -p all
        conda upload 

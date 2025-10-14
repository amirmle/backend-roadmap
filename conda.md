
### create new env
    conda create -n myenv python=3.11

### activate and deactivate env
    conda activate myenv
    conda deactivate

### install package
    conda install numpy pandas

### installed packages
    conda list

### remove package
    conda remove package_name

### deleted entire env
    conda remove --name myenv --all

### current active env
    conda info --envs

### search package in conda repository
    conda search package_name

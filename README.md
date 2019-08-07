# Using Elasticluster to create customized cluster on Azure

1. `pip install -e .` to install Elasticluster.

2. An example config file is in `example-azure`. Modify the flavor with the instance type you want and make sure to check availablility in advance. Your may use this config file to replace the one in your home directory `~/.elasticluster/config` or simply do `elasticluster -c new_config start azure-slurm`

3. `elasticluster -c config ssh azure-slurm` and you should be good to go. You have to install the tools/softwares you need on the compute node for the first time.

4. For more detail about the configuration setup please refer to: https://elasticluster.readthedocs.io/en/latest/configure.html

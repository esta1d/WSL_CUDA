# PyTorch (CUDA) installation guide for WSL2 with cuDNN and TensorRT
WSL and CUDA installation instructions

## Install WSL2
To install specific version of WSL2 run:
```
wsl --list --online
```
Choose the version you want to install and run (example for Ubuntu 24.04):
```
wsl --install Ubuntu-24.04
```
## Update WSL2
Enter WSL2 shell:
```
wsl -d Ubuntu-24.04
```
Change working directory:
```
cd ~
```
Update the system:
```
sudo apt update 
sudo apt upgrade -y
```
## Install conda
Download [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main) for Linux (check your architecture: ```x86_64```, ```aarch64``` or ```s390x64```):
```
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```
Install Miniconda:
```
bash Miniconda3-latest-Linux-x86_64.sh
```
> Do you wish to update your shell profile to automatically initialize conda?<br>
`yes`

**Re-open shell**


## Install build-essential
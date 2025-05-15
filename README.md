# PyTorch (CUDA) installation guide for WSL2 with cuDNN and TensorRT
WSL and CUDA installation instructions

## Install WSL2
To install specific version of WSL2 run:
```wsl --list --online```
Choose the version you want to install and run (example for Ubuntu 24.04):
```wsl --install Ubuntu-24.04```
## Update WSL2
Enter WSL2 shell:
```wsl -d Ubuntu-24.04```
Change working directory:
```cd ~```
Update the system:
```
sudo apt update 
sudo apt upgrade -y
```
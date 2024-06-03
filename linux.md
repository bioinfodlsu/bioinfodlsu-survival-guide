# Do I need to learn Linux?

Maybe not, most likely yes. 

Most bioinformatics software are built for Unix-like operating systems.
One reason for this is that bioinformatics projects tend to be free and open-source and so need a similar eco-system.
Another reason is that bioinformatics tools need to run on high-performance-computing environments or on cloud computing resources, 
all of which run on Unix-like systems.

## How to install?
Luckily, even if you are only used to Windows, it is very easy these days to install a modern Linux OS on a virtual machine using VirtualBox or VMware or WSL.
Here are some guides that might be helpful:

### Install Linux via WSL
- https://learn.microsoft.com/en-us/windows/wsl/about
- Enabling GPU passthrough: https://docs.nvidia.com/cuda/wsl-user-guide/

### Install Linux on a VM
- https://docs.vmware.com/en/VMware-Horizon/2306/linux-desktops-setup/GUID-51C371A9-4D76-4A8C-8645-909E93080B4F.html
- https://ubuntu.com/tutorials/how-to-run-ubuntu-desktop-on-a-virtual-machine-using-virtualbox#1-overview

### Install on hardware
- https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview


## Command line
The strength of Unix-like OS is a powerful shell that allows you to write commands for the OS to perform. 
This especially useful when dealing with huge data files, as is often the case in bioinformatics.

Here are some tutorials that might come in handy in your journey to be a super command-line user.

### Bash
- https://learn.microsoft.com/en-us/training/modules/bash-introduction/1-what-is-bash

### Basic operations: `cp`, `mv`, and `rm`

### Text processing: `grep`, `awk`, and `sed`
- https://www.gnu.org/software/gawk/manual/html_node/Getting-Started.html
- https://rc.fas.harvard.edu/wp-content/uploads/2017/03/AWK.pdf

### Displaying text files: `cat` and `less`

### Text editors: `nano`, `vim`, and `emacs`
(Choose your [editor](https://en.wikipedia.org/wiki/Editor_war))

### Downloading files: `wget` and `curl`

### Downloading from and uploading to Google Drive: `gdown` and `rclone`

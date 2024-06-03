# What computing resources are available ?

For some projects, a powerful personal computer might be sufficient. 

For some projects, you might need a high-performance computing environment.
We have a few options.

## Computational servers provided by the lab
We have decently powerful computational servers.
If you request, you will be provided key-based SSH access.
The machines run Linux.

You can connect to these servers via SSH. If you are on Windows, you can use [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/install) or an SSH client like [PuTTY](https://putty.org/):
- For Unix-based and Unix-like systems (including macOS, Linux, and WSL): https://www.digitalocean.com/community/tutorials/how-to-use-ssh-to-connect-to-a-remote-server
- For PuTTY: https://www.ssh.com/academy/ssh/putty/windows

Here are some guides on how to generate an SSH key pair:
- For Unix-based and Unix-like systems (including macOS, Linux, and WSL): https://www.ssh.com/academy/ssh/keygen 
- For PuTTY: https://www.ssh.com/academy/ssh/putty/windows/puttygen

You can transfer data from your (local) machine to the (remote) server (or vice versa) using [`scp`](https://linux.die.net/man/1/scp) ([`pscp`](https://documentation.help/putty/pscp.html) if you are using PuTTY) or [`rsync`](https://linux.die.net/man/1/rsync):
- `scp`: https://www.freecodecamp.org/news/scp-linux-command-example-how-to-ssh-file-transfer-from-remote-to-local/
- `rsync`: https://www.digitalocean.com/community/tutorials/how-to-use-rsync-to-sync-local-and-remote-directories

## Computational servers provided by CCS

## Computational servers provided by DOST ASTI-COARE
DOST ASTI-COARE generously provides free access to their HPCs:
- https://asti.dost.gov.ph/coare/wiki/Main/using-coare/

## Cloud services
We have previously used Google's free credits for researchers.
- https://edu.google.com/programs/credits/research/?modal_active=none
- https://sites.research.google/trc/about/

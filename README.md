# Stanford-SCG-Onboarding
A tutorial to get setup on the Stanford SCG cluster. The SCG Cluster is a high-performance computing cluster run by the Genetics Bioinformatics Service Center. The SCG uses slurm for workload managing and job scheduling (see https://slurm.schedmd.com/documentation.html).
Fore more detail, please visit https://login.scg.stanford.edu

## How to get a SCG account?
To have an account on SCG, you need to have SUnetID and be in a SCG-affiliated lab. To check if your lab is on the cluster, ask your lab. 
### If you your lab has a lab account on SCG
Email scg-action@lists.stanford.edu to request a user account and CC your PI in the email.

## How to access the SCG cluster?
There are several ways of accessing to the cluster.
1. SCG Ondemand
  - It is a web-based interface to SCG cluster with GUI.
2. SSH from the Terminal
  - from your terminal, ssh SUNetID@login.scg.stanford.edu. You can alias this command in your .zshrc or .bashrc files.
  - alias example: alias s="SUNetID@login.scg.stanford.edu"

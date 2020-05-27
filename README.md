# ansible-local
I've decided to track whenever I install a new package on my local machine. The likes of `apt`, `npm` or CRAN have put our trigger fingers to auto-fire when it comes to installing new stuff. Hence I decided to use ansible to track what I install on my fresh, local ubuntu machine. 

Let alone the commit history of this repository will be interesting in a year from now... ;) 

## structure of my playbooks

I add several plays my playbooks so I can call part of the process as opposed to running everything. 

- os.yaml : OS level packages
- cran-r.yaml: Extension packages for the R Language for Statistical computing. 





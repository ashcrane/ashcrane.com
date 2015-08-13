#Crane Portfolio

A static webpage of a single html file to convey at least 10 projects that I have worked on in my student career at Full Sail University.

##Deployment Plan

#####Server Architecture
---
For a single site with only one .html file, the server architecture consists of a single-tier server on Digital Ocean. The server has 512 MB Ram, 20GB Disk Space, and the OS is Ubuntu 12.04.5 x64. The software includes git and apache2.

#####Deployment Steps
---
On completion of fully tested code within local development environment:

1. Pull master branch to make sure that local development branch is updated with latest information.
  1. Resolve any conflicts.
  2. Once any conflicts are resolved, commit new changes and pull the master branch again.
2. Merge local dev branch with master branch.
    1. Test after merge to make sure all is working correctly.
    2. Resolve any new conflicts.
3. Push to repo.
 

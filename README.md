## Notice

The Github repository has been moved to GitLab: 
https://gitlab.com/hjjandy/FSE16-BidText-Artifacts.

==============================

##### FSE16-BidText-Artifacts

This the the repository of all config files, scripts, JARs and some test apps
used in the FSE16 paper BidText.

The pre-configured VM can be found here: https://github.com/hjjandy/FSE16-BidText-Artifacts-VM.

##### How to download the repo

Some files have a larger size than 100MB. We leverage 
Git LFS (https://git-lfs.github.com/) to store the files. 
The users should install Git LFS before cloning the repository. 
With Git LFS installed, the users can download the large files 
via "git lfs clone", "git lfs pull".

Note that BidText-Bin/lib/stanford-parser-3.4.1-models.jar is stored 
with Git LFS. The test set of 100 apps under folder BidText-TestApps/Others
is also stored with Git LFS. The users MUST get a full local copy of 
the jar file to run BidText. For the test set, it is optional. 
The users can use any other arbitary Android apps to test BidText.


##### Prerequisite

Java 7 or 8 with amd64 architecture is required to run BidText on either 
Windows or unix-like operating systems.

##### How to run BidText

Please read FSE16-Artifacts-Eval-README for more details.

##### Where is the source code

The source code is not included. But it is publically available at: https://bitbucket.org/hjjandy/toydroid.bidtext



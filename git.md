
### What is Git 
-----------------------------------------------
> Git is an open source Distributed version control system. Git is used to tracking changes in the source code, enabling multiple developers to work together on non-linear development. It is a three way process that contains workspace, local repository and remote repository.

>We are working on a workspace after complete work commits changes into the local repository.
local repository is an exact copy of remote repository which is placed on the local system. the local repository maintains its own version.

>For the remote repository we are using GitHub and GitLab to store the source code & it provides the centralized store.

----


### Why we need Git?
---------------------------------
>git tracks the changes you make files, so you have a record of what has been done, and you can revert to specific versions if you feel a bug in the current version so you can also go back to the specific version.
 

>git also makes collaboration easier, allowing changes by multiple people to all be merged into one source.
---

### What makes git unique from other tools like SVN?
---
![cetralize version control system](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Centralized-Version-Control-System-Workflow-What-Is-Git-Edureka-768x339.png)

>Subversion it is open source centralized version control system
It is a two way process that contains a remote repository and working copy which is present on the local system.
We work on a workstation and we need to connect with remote repositories continuously with the internet or network while working.
if a centralized repository gets destroyed or data loss in such case complete or single point of failure and never retry data of server.

![distributed verion control system](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Distributed-Version-Control-System-Workflow-What-Is-Git-Edureka-768x508.png)

>but in the case of git there is no need to connect every time with a remote repository. we are only connected to remote repositories while at the time to sincup local and remote repository. If a remote repository gets destroyed in such a case we can retrieve the remote repository by local repository because the local repository maintains its own version with only a small amount of data loss.
---
### Git Workflow
---
![git work flow](https://programmer.group/images/article/43e5d1ea2a2e9380b7eb5294bbe7e77e.jpg)

> ***Remote repository*** ??? remotely stored.
> 
>***Local Repository*** ???    exact copy of the remote repository which is placed on the local system.

>***Workspace*** ???    It is your working directory.

>***Staging*** ???   It is a buffer area used to store the changes before storing into a local repository.

### ***Workflow*** --> 
---
> we are working on a workspace then adding files to the staging area.
after adding several changes into the staging area then those files commit or save the changes in the local repository.
After storing into a local repository then store the data in a remote repository.

+++
title = "Storage"
date = 2022-11-24T23:35:10+08:00
weight = 5
chapter = true
pre = "<b>4. </b>"
+++

## Storage location on Pawsey systems.

**Topaz:**

*	/home - used to store software configuration files that cannot be easily located elsewhere. 
* /scratch - used to store data in use by jobs that are actively queued and running on the supercomputer 
*	/group - used to store software and slurm batch scripts

**Setonix:**

*	/home - used to store software configuration files that cannot be easily located elsewhere. (1 GB per user)
*	/software - used to store h Pawsey and researcher software installations and Slurm batch scripts. (256 GB per project)
*	/scratch - used to store data in use by jobs that are actively queued and running on the supercomputer. (1 PB limit)

**Topaz, Setonix, Nimbus and your PC:**

*	Acacia object storage - High-speed object storage for hosting research data online. It will replace /group on Topaz in the near future.

* 	/home  and /scratch on Topaz may be different than /home and /scratch on Setonix.
*	Files on /scratch are deleted automatically after 30 days from their last access.
*	Data on /scratch should be moved to Acacia as soon as possible.

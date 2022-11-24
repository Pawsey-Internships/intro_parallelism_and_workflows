---
title: "Acacia Object Storage."
weight: 1
---

*	`/scratch` and `/software` on Setonix do not provide permanent storage space for research data. 
*	The data that needs to be stored longer than just a few weeks should be copied to the Acacia object storage service. 
*	Acacia provides a platform that you can use to store your data as long as your Pawsey project is active. 

*	There are two types of accounts available on Acacia, user and project. 
*	Pawsey user accounts come with a 100GB allocation. 
*	All active projects with Pawsey supercomputing, Nimbus research cloud, and Visualisation projects have an allocation of at least 1TB.

Acacia is built upon the open-source software Ceph. Instead of files, your data is stored as objects in buckets:

*	Buckets are the basic containers that hold your data. 
*	Everything you store in Acacia must be contained in a bucket. 
*	Unlike folders, you cannot nest buckets or put one bucket inside another. 

*	Objects are the individual pieces of data contained in a bucket. 
*	An object is typically a file and any metadata that describes the file. 
*	Objects cannot be changed while in the storage system. 
*	To change an object, you must first download, modify, and then upload it again. 


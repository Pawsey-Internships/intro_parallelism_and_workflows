---
title: "Getting Started with Acacia."
weight: 2
---
* [The Acacia User Guide](https://support.pawsey.org.au/documentation/display/US/Acacia+-+User+Guide?src=contextnavpagetreemode) has all of the information you need to get started.
*	A recording of a recent [Acacia Object Storage Workshop](https://youtu.be/mOp7NJpwzac) is available on the Pawsey Youtube Channel.
*	Pawsey supports the minio client on its supercomputing systems.
*	Minio can also be installed on [Linux, macOS and Windows](https://support.pawsey.org.au/documentation/display/US/Installing+and+configuring+an+S3+client).
* 	To start using Acacia, you first need to [create access keys](https://support.pawsey.org.au/documentation/pages/viewpage.action?pageId=116130408) through [https://portal.pawsey.org.au/].
*	When you create your key, you will be provided with a command that you can copy and paste to set up access.

**Creating Buckets:**

	mc mb <ALIAS>/<BUCKET_NAME>
	
**Delete a bucket:**
	
	mc rb <ALIAS>/<BUCKET_NAME>
	
**List Buckets associated with your account or project:**

	mc ls <ALIAS>
	
**Upload to a Bucket:**

	mc cp <SOURCE> <TARGET>
	
**Download from a Bucket:**

	 mc cp <SOURCE> <TARGET>
	
Where `<ALIAS>` will typically be your project or user name.

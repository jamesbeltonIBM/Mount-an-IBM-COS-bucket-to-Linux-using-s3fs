# Mounting an IBM Cloud Object Storage Bucket to a Linux-based Server using s3fs
This guide provides step by step instructions on how to install, configure and use s3fs with Linux to mount IBM Cloud Object Storage buckets to the operating system. I’ve primarily used centOS, but where appropriate, I’ve included other Linux flavours, including macOs too.

Having a server directly access Object Storage can be really useful. Object Storage is both low-cost (pay for what you use) and effectively infinite in size. It’s great for storing all sorts of files, including things like backups. Using s3fs, you can access files in your object storage with familiar commands and use it in a way that you would any other disk storage, from multiple servers, so it makes a great low-cost ‘file share’ too. 

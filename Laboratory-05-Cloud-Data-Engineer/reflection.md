# Reflection

In this activity, I learned more about object storage and how MinIO can be used to store files. Object storage is useful for storing many photos because it is made for files such as images, videos, and backups. It can be more suitable than using a normal hard drive when there are many files to store.

Docker made the MinIO setup easier because I only needed a few commands to run the server. I used commands like `docker pull`, `docker run`, `docker ps`, and `docker logs` to install and check MinIO.

I also experienced some problems while doing the activity. At first, I used `docker pull minio/minio`, but it gave me a pull access denied error. I then used `docker pull quay.io/minio/minio`, and this worked. I also accidentally typed `9001` in the terminal and got a `command not found` error. I learned that 9001 is a port and should be opened using the KillerCoda port option.

A bucket is a place where files or objects are stored. For this activity, I created a bucket named `client-photos` and uploaded a file called `sample.txt`.

To avoid losing files, companies can keep copies of their data and use more than one storage system or server. This can help protect the files if one server has a problem.

After doing this activity, I feel more comfortable using the Linux command line. I was able to run Docker commands, check the MinIO server, create a bucket, and upload a file. The errors I encountered also helped me understand what I was doing instead of just following the commands.

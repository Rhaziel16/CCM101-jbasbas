# Mission Reflection

This laboratory helped me understand why object storage is useful for applications that need to store a large number of files. Object storage is better suited for millions of photos because it is designed for unstructured data such as images, videos, and backups. Instead of treating the photos like files on a normal computer hard drive, object storage keeps the data as objects inside a bucket. This makes it suitable for applications such as a photo-sharing website.

Docker made deploying the MinIO server easier because I did not have to manually install and configure every part of the storage software. I only needed to run the Docker command with the required ports, image, and environment variables. Docker then created the MinIO container and allowed me to start the storage server quickly.

A bucket is a container used to organize and store objects in object storage. In this activity, I created a bucket named `client-photos` and uploaded a sample file into it. This helped me understand how applications can organize uploaded data.

Large enterprise companies can protect their object storage data by keeping multiple copies of data and using backup or replication systems. If one physical server fails, another copy can be used to prevent permanent data loss. They can also use monitoring, redundancy, and recovery systems to protect important data.

My confidence in using the Linux command line is also improving. At first, commands such as Docker commands looked complicated, but running them step by step made them easier to understand. I learned how to check running containers using `docker ps` and how to use a terminal to deploy a cloud service. This activity also helped me understand how Docker, Linux, GitHub, and cloud storage can work together in a real cloud computing environment.

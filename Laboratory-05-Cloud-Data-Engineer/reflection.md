# Reflection

This activity helped me understand how object storage works and how it can be used for storing many files. I learned that object storage is useful for user-uploaded photos because it is designed to store a large amount of files. Compared to traditional block storage, object storage is easier to use for files like photos, videos, and backups.

Docker also made the MinIO deployment easier for me. Instead of installing everything manually, I only needed to pull the image and run the container. I used Docker commands such as `docker pull`, `docker run`, `docker ps`, and `docker logs`.

I had a problem when I first tried to pull the MinIO image. I used `docker pull minio/minio`, but KillerCoda returned a pull access denied error. I searched for another available MinIO image and used `quay.io/minio/minio` instead. The second command worked and I was able to run MinIO. I also accidentally typed `9001` in the terminal and got a `command not found` message. I learned that the port should be opened using the KillerCoda port access option.

A bucket is a container where objects or files are stored. In my activity, I created a bucket named `client-photos` and uploaded `sample.txt`.

For real companies, object storage data can be protected from data loss by keeping copies of data and using redundancy. This helps protect files if a physical server has a problem.

My confidence with the Linux command line is improving because I was able to use Docker commands and check the MinIO container by myself. I also learned that errors are part of the process. Instead of stopping when the first command failed, I tried another way and was able to finish the activity.

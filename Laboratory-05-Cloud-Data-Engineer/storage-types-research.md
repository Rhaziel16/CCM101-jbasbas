# Storage Types Research

## Comparison of Storage Types

| Storage Type | Description | Primary Use Case | Cloud Provider Example |
|---|---|---|---|
| Block Storage | Stores data in fixed-size blocks. | Operating systems, databases, and applications | AWS EBS |
| File Storage | Stores data as files and folders. | Shared files and documents | AWS EFS |
| Object Storage | Stores data as objects with information about the file. | Images, videos, backups, and other files | AWS S3 |

## Why Object Storage is Good for User-Uploaded Images

Object Storage is a good choice for millions of user-uploaded images because it is made for storing large amounts of files. Each image can be stored as an object and accessed when needed.

For this activity, MinIO was used as the object storage system. The bucket used for the test was called `client-photos`.

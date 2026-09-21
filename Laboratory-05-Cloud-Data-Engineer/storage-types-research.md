# Types of Cloud Storage

## Comparison of Cloud Storage Types

| Storage Type   | Description                                                                         | Primary Use Case                                                                  | Cloud Provider Example |
| -------------- | ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------- | ---------------------- |
| Block Storage  | Stores data in fixed-size blocks that can be accessed individually.                 | Operating systems, databases, and applications that need fast storage.            | AWS EBS                |
| File Storage   | Stores files in a shared folder structure that can be accessed by multiple systems. | Shared files, documents, and applications that need a common file system.         | AWS EFS                |
| Object Storage | Stores data as objects together with metadata and a unique identifier.              | Images, videos, backups, documents, and other large amounts of unstructured data. | AWS S3                 |

## Why Object Storage is Suitable for the Client

Object Storage is a good choice for the client's photo-sharing application because it is designed to store large amounts of unstructured data such as images. It can organize many uploaded files using objects and buckets, making it suitable for applications that need to store millions of photos.

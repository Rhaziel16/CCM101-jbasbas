# MinIO Deployment

## Docker Command

The MinIO server was deployed using the following Docker command:

```bash
docker run -d -p 9000:9000 -p 9001:9001 --name minio-server \
-e "MINIO_ROOT_USER=cloudadmin" \
-e "MINIO_ROOT_PASSWORD=CloudNova2026!" \
minio/minio server /data --console-address ":9001"
```

## Web Console Port

The MinIO Web Console was accessed using:

```text
Port 9001
```

Port 9000 is used for the MinIO API, while port 9001 is used for the MinIO Web Console.

## Bucket Created

The storage bucket created for the client was:

```text
client-photos
```

A sample file was uploaded to the bucket to verify that the object storage system was working.

## Environment Variables

The `-e` flags in the Docker command were used to set environment variables inside the MinIO container.

```text
MINIO_ROOT_USER=cloudadmin
```

This sets the MinIO administrator username.

```text
MINIO_ROOT_PASSWORD=CloudNova2026!
```

This sets the MinIO administrator password.

Using environment variables makes it possible to configure the MinIO server when the Docker container is started.

## Deployment Verification

The MinIO container was verified using:

```bash
docker ps
```

The running container showed that MinIO was successfully deployed and that ports 9000 and 9001 were available.

## Result

The MinIO Web Console was successfully accessed through KillerCoda. The `client-photos` bucket was created and a sample file was uploaded successfully.

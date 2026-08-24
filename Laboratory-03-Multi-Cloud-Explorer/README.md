# Checkpoint 7 – Continue Your Linux Investigation

## Linux Server Investigation

A KillerCoda Playground was used to inspect the Linux server. The required Linux commands were used to collect information about the operating system, CPU, memory, and disk space.

## Commands Used

### 1. Operating System

```bash
cat /etc/os-release
```

This command was used to identify the Linux operating system and its version.

**Result:** Ubuntu 24.04.2 LTS

### 2. CPU Information

```bash
lscpu
```

This command was used to check the processor information of the Linux server.

**Result:** Intel Xeon E312x (Sandy Bridge), 1 CPU, approximately 2.0 GHz

### 3. Memory

```bash
free -h
```

This command was used to check the memory available on the Linux server.

**Result:** 1.96 GiB total memory

### 4. Disk Space

```bash
df -h
```

This command was used to check the disk space available in the Linux environment.

**Result:** 19 GB total disk space

## Cloud Migration

### If this Linux server were migrated to the cloud, which AWS, Azure, and GCP services could host it?

The Linux server could be migrated to any of the three major cloud platforms using their virtual machine services.

### AWS

**Amazon EC2** – a virtual machine service that can be used to run a Linux server and its applications.

### Microsoft Azure

**Azure Virtual Machines** – a cloud-based virtual machine service that supports Linux operating systems.

### Google Cloud Platform (GCP)

**Compute Engine** – a virtual machine service that can be configured to run a Linux server and its applications.

## Cloud Service Comparison

| Cloud Provider | Service | Purpose |
|---|---|---|
| AWS | Amazon EC2 | Host the Linux server as a virtual machine |
| Microsoft Azure | Azure Virtual Machines | Host the Linux server as a virtual machine |
| GCP | Compute Engine | Host the Linux server as a virtual machine |

## Terminal Output

The screenshot below shows the terminal commands and their outputs used to identify the operating system, CPU information, memory, and disk space.

![KillerCoda Terminal](screenshots/killercoda-terminal.png)

# Checkpoint 7 – Continue Your Linux Investigation

## KillerCoda Playground

A KillerCoda Playground was used to investigate the Linux server and collect its basic system information.

## Operating System

```bash
cat /etc/os-release
```

Ubuntu 24.04.2 LTS

## CPU Information

```bash
lscpu
```

Intel Xeon E312x (Sandy Bridge), 1 CPU, approximately 2.0 GHz

## Memory

```bash
free -h
```

1.96 GiB of memory

## Disk Space

```bash
df -h
```

19 GB of disk space

## Cloud Migration

If this Linux server were migrated to the cloud, the following AWS, Azure, and GCP services could be used to host it.

### AWS

**Amazon EC2** – provides virtual machines that can be used to run a Linux server.

### Azure

**Azure Virtual Machines** – provides cloud-based virtual machines that support Linux operating systems.

### GCP

**Compute Engine** – provides virtual machines that can be configured to run a Linux server.

## Terminal Output

The screenshot below shows the terminal output from the Linux commands used during the investigation.

![KillerCoda Terminal](screenshots/killercoda-terminal.png)

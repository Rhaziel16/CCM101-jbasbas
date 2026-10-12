# Backup Script Guide

## 1. Backup Script

The following Bash script creates a backup directory and compresses the application data into a `.tar.gz` file. It uses a timestamp in the filename so that each backup can have a different name.

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies

SOURCE_DIR="/root/app-data"
BACKUP_DIR="/root/backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")

echo "Initiating automated backup..."

# Create the backup directory if it does not exist
mkdir -p "$BACKUP_DIR"

# Compress the source directory into a tarball (.tar.gz)
tar -czf "$BACKUP_DIR/backup_$TIMESTAMP.tar.gz" "$SOURCE_DIR"

echo "Backup completed successfully at $TIMESTAMP!"
```

## 2. File Permission

The command `chmod +x /root/backup.sh` adds execute permission to the script. This allows the user to run the script as a program instead of receiving a permission error.

## 3. Cron Schedule

The Cron expression used is:

```text
0 2 * * * /root/backup.sh
```

This schedule runs the backup script every day at 2:00 AM, based on the system's time and time zone.

* **Minute (0):** Runs at minute zero.
* **Hour (2):** Runs at 2 AM.
* **Day of Month (*):** Runs every day of the month.
* **Month (*):** Runs every month.
* **Day of Week (*):** Runs every day of the week.

The script is located at `/root/backup.sh`, and the application data and backup files are stored in `/root/app-data` and `/root/backups`, respectively.

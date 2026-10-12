# Firewall Configuration

## 1. Allow SSH

```bash
sudo ufw allow ssh
```

This command allows SSH connections so administrators can manage the server remotely.

## 2. Set the Default Deny Policy

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
```

These commands block incoming traffic by default and allow outgoing traffic.

## 3. Enable the Firewall

```bash
sudo ufw enable
sudo ufw status verbose
```

These commands enable the firewall and display its current status and default policies.

## 4. Allow Port 8080

```bash
sudo ufw allow 8080/tcp
sudo ufw status numbered
```

The first command allows TCP traffic on port 8080. The second displays the firewall rules with their numbers.

## 5. Importance of Allowing SSH First

If UFW is enabled before allowing SSH, remote administrators may lose access to the server because incoming SSH connections can be blocked by the default deny policy.

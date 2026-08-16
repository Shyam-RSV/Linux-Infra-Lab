## Architecture

### 1. Raspberry Pi OS Lite — Client
- Acts as the client workstation
- SSH into servers
- Test DNS
- Access shared folders
- Clone Git repositories
- Generate logs and simulate users

### 2. Ubuntu Server 26.04 LTS — Infrastructure Server
- SSH Server
- Apache Web Server
- DNS Server
- Git Server
- Samba/NFS File Server
- User & Group Management
- Shared Storage
- Firewall

### 3. Rocky Linux 10 — Operations Server
- Monitoring
- Central Logging
- Backup Server
- Alerting
- Bash Automation
- Scheduled Tasks
- Performance Reports

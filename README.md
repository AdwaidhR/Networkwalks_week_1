# NetworkWalks Week 1 – Cybersecurity Lab Setup

## Project Overview
This project documents the setup of a cybersecurity lab environment using VirtualBox and Kali Linux as part of the NetworkWalks Week 1 project.

## Lab Configuration
- **Virtualization:** Oracle VirtualBox
- **Attacking Machine:** Kali Linux 2026.3
- **Network Type:** NAT Network
- **Network Subnet:** `10.0.0.0/24`
- **Kali Linux IP:** `10.0.0.2/24`
- **Gateway:** `10.0.0.1`
- **Internet Connectivity:** Verified using `ping -c 4 google.com`
- **Shared Folder:** Host Downloads folder mounted in Kali Linux
- **Shared Clipboard:** Bidirectional
- **Drag and Drop:** Bidirectional
- **Snapshot:** NetworkWalks Week 1 - Initial Setup

## Tasks Completed
1. Installed and configured VirtualBox.
2. Imported the Kali Linux virtual machine.
3. Configured the NAT Network.
4. Assigned the required static IP address.
5. Verified internet connectivity.
6. Enabled and tested the shared folder.
7. Configured clipboard and drag-and-drop.
8. Created a VirtualBox snapshot.

## Screenshots

### 1. Kali IP Address and Internet Connectivity
![Kali IP and Internet](screenshots/01-kali-ip-internet.png)

### 2. VirtualBox Network Configuration
![VirtualBox Network](screenshots/02-virtualbox-network.png)

### 3. Shared Folder
![Shared Folder](screenshots/03-shared-folder.png)

### 4. Clipboard and Drag-and-Drop
![Clipboard and Drag-and-Drop](screenshots/04-clipboard-dragdrop.png)

### 5. VirtualBox Snapshot
![VirtualBox Snapshot](screenshots/05-snapshot.png)

## Learning Outcomes
- Learned to configure a Kali Linux virtual machine.
- Practiced static IP configuration and network connectivity testing.
- Configured file sharing between the host and virtual machine.
- Learned to create and manage VirtualBox snapshots.

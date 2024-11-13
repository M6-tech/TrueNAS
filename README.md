# TrueNAS
![Sans titre](https://github.com/user-attachments/assets/392cb4a0-5d70-4c49-ae18-d083198a78e2)

## What is TrueNAS ?

TrueNAS is network-attached storage software that allows you to use commodity hardware. It is an effective tool for organizing and storing digital files, including images, videos, and documents.

It’s a family of open-source, free network-attached storage (NAS) operating systems built by iXsystems that use the OpenZFS file system and are based on Linux and FreeBSD. It is licensed under the terms of the BSD License and runs on commodity x86–64 hardware. The TrueNAS range includes free public versions (TrueNAS Core, previously known as FreeNAS), commercial versions (TrueNAS Enterprise), and Linux versions (TrueNAS SCALE). TrueNAS uses the SMB, AFP, NFS, iSCSI, SSH, rsync, and FTP/TFTP protocols to support clients running Windows, macOS, and Unix as well as a variety of virtualization hosts, including XenServer and VMware.

TrueNAS is managed through a comprehensive web interface that handles essential administrative functions. The web interface supports storage pool configuration, user management, sharing configuration, and system maintenance.

TrueNAS is like a digital home for your files, keeping them secure and ready whenever you need them.

## Features of TrueNAS

- Free and open source

- Built with OpenZFS file system for built-in RAID, data management tools, and automatic detection and repair of silent data corruption.

- Supports Snapshots and VMWare Snapshots and It supports BSD Jails for creating virtual machines.

- Supports Active Directory, LDAP, NIS, and Kerberos authentication.

- Cloud sync to Amazon S3, Backblaze B2, Box, Dropbox, FTP, Google Cloud Storage, Google Drive, HTTP, Hubic, Mega, Microsoft Azure Blob Storage, Microsoft OneDrive, OpenStack Swift, pCloud, SFTP, WebDAV, and Yandex.

- It checksums your data whenever it is written and verifies those checksums when data is read. It even checksums the metadata that describes the file system and allows you to periodically verify all checksums to determine if infrequently used data or backups are suffering from silent data corruption.

- TrueNAS is fast. It gives you the performance you need with a cache-first design approach that delivers blistering performance from flash memory for your most frequently and recently accessed SAN and NAS data.

## How to Install TrueNAS ?

_Download and Install TrueNAS in Virtual Machine_

- In this demonstration, I will use a virtual machine to install TrueNAS.

1. Download TrueNAS ISO — Visit the official TrueNAS website (https://www.truenas.com/download-truenas-core/) and download the latest TrueNAS ISO image.

2. Open VMware Workstation Pro and click on “File” to create a new virtual machine.

![Capture0](https://github.com/user-attachments/assets/abfd6a9e-85af-45d3-b8a2-811d35bf4b54)

4. Give your virtual machine a name (e.g., TrueNas_Core).

![Capture2](https://github.com/user-attachments/assets/ce281614-2900-48be-a76b-556872ff4dcb)

5. Choose “BSD” as the type and “FreeBSD (64-bit)” as the version.

![Capture1](https://github.com/user-attachments/assets/7c44ce25-fa94-41f9-a73e-bbc907c61386)

6. Set a minimum of 25 GB for the virtual hard disk size.

![Capture3](https://github.com/user-attachments/assets/68e9f643-09e4-4f99-bd7a-6127a7506510)

7. I will add also 4 Hard Disks "25 GB".

![Capture5](https://github.com/user-attachments/assets/55a0991c-1aa1-4b96-88bb-b226a04aaea2)


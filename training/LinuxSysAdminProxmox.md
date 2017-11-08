---
layout: train
title: Training SysAdmin Proxmox VE
permalink: /training/sysadmin-proxmox-ve
---

## Sekilas Tentang Proxmox VE

Proxmox VE (Virtual Environment) merupakan distro special untuk virtualisasi, dibangun dari basis distro Debian minimal dan berjalan dalam modus teks. Meski berbasis teks, proses manajemen Proxmox Virtual Environment mudah dilakukan melalui akses web, termasuk melakukan instalasi sistem dengan menggunakan teknologi VNC.

Proxmox merupakan salah satu alternatif selain VMware, sangat cocok untuk development ataupun production. Bagi para Sysadmin yang ingin melakukan development atau membangun lab sendiri namun terkendala dalam hal lisensi, proxmox merupakan salah satu alternatif. Selain free, fitur yang ditawarkan juga tidak kalah dari VMware vSphere.

## Kelebihan Proxmox

1. Free, gratis untuk dipergunakan
2. Menggunakan teknologi Virtualisasi Server Bare-Metal OS sehingga hemat penggunaan resources dan memiliki performance yang bagus
3. Mudah diinstall dan dikonfigurasi
4. Minimalis dan Powerful, hanya butuh sedikit memory untuk menjalankan host server
5. Mendukung teknologi virtualisasi server berbasis KVM dan OpenVZ
6. Mudah dibuat cluster dan High Availability Server
7. Mendukung Live Migration (dalam istilah vSphere : vMotion)
8. Mendukung banyak model storage : Local Directory, LVM, iSCSI maupun NFS
9. Mendukung auto backup sesuai schedule baik ke internal maupun eksternal storage
10. Mendukung berbagai format harddisk virtual


## Kebutuhan Sistem

### Minimal Hardware

- CPU: 64bit (Intel EMT64 or AMD64)
- Intel VT/AMD-V capable CPU/Mainboard (for KVM Full Virtualization support)
- Minimum 1 GB RAM
- Hard drive
- One NIC

### Recomended Hardware

- CPU: 64bit (Intel EMT64 or AMD64)
- Intel VT/AMD-V capable CPU/Mainboard (for KVM Full Virtualization support)
- 8 GB RAM is good, more is better (grab as much as possible)
- Hardware RAID with batteries protected write cache (BBU) or flash protection
- Fast hard drives, best results with 15k rpm SAS, Raid10
- Two or more Gbit NIC (for bonding), additional NIC´s depending on the preferred storage technology and cluster setup

## Materi Kursus

1. Pengenalan Proxmox VE
2. Instalasi Proxmox
3. Clustering Proxmox
4. Membuat Virtual Machine (VM) menggunakan KVM (Kernel Based Virtual Machine)
5. Membuat Virtual Machine (VM) menggunakan Linux Container (LXC)
6. Mengelola Storage
7. Konfigurasi Jaringan 
8. Mengelola User & Group







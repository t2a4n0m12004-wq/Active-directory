# Active-directory Lab

## Overview

Lab mô phỏng hệ thống mạng doanh nghiệp sử dụng Windows Server
và Windows Client trên môi trường VMware.

## Technologies

- Windows Server 2022
- Windows 10
- Active Directory Domain Services
- DNS
- DHCP
- Group Policy
- VMware
- TCP/IP
- Subnetting
- Network Troubleshooting

## Implemented

### 1. Active Directory
- Deploy Domain Controller
- Create OU, User, Group
- Join Windows Client vào Domain

### 2. DNS
- Configure DNS Server
- Configure DNS records
- Test name resolution bằng nslookup

### 3. DHCP
- Create DHCP Scope
- Configure IP range, Gateway, DNS
- Verify IP assignment trên Client

### 4. Group Policy
- Configure GPO
- Apply policies cho User/Computer
- Verify policy trên Client

### 5. Network

Thiết kế mô hình mạng gồm các site:
- Hà Nội – Headquarters
- Đà Nẵng – Branch
- TP.HCM – Branch

## Troubleshooting

Một số lỗi đã thực hành xử lý:
- Client không join được Domain
- DNS resolution failure
- DHCP không cấp IP
- Domain authentication issues
- Network connectivity issues

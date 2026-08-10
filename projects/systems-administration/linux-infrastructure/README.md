# 🖥️ Enterprise Linux Infrastructure Deployment for PromisedLand.com

![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Amazon EC2](https://img.shields.io/badge/Amazon%20EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)
![DNS](https://img.shields.io/badge/DNS-005571?style=for-the-badge)
![SSH](https://img.shields.io/badge/SSH-222222?style=for-the-badge&logo=openssh&logoColor=white)
![LVM](https://img.shields.io/badge/LVM-6B7280?style=for-the-badge)
![UFW](https://img.shields.io/badge/UFW-F43F5E?style=for-the-badge)

> **Designing and deploying a secure, scalable Linux infrastructure on Amazon Web Services (AWS) to support enterprise web services, storage management, networking, and system security.**

---

## 📋 Project Information

| **Detail** | **Information** |
|---|---|
| **Project Type** | Enterprise Linux Infrastructure Deployment |
| **Role** | Linux Systems Administrator |
| **Environment** | Amazon Web Services (AWS) |
| **Operating System** | Ubuntu Server 24.04 LTS |
| **Cloud Platform** | Amazon EC2 |
| **Project Status** | Completed |
| **Focus Areas** | Linux Administration, Cloud Infrastructure, Security, Storage Management |
| **Skills Applied** | Linux, AWS EC2, Apache2, LVM, DNS, SSH, ACLs, UFW |

---

## 🚀 Executive Summary

This project demonstrates the deployment and administration of an enterprise Linux infrastructure hosted on Amazon Web Services (AWS).

The environment was built using **Ubuntu Server 24.04 LTS on Amazon EC2** and incorporated practical Linux administration, cloud infrastructure, storage management, web services, networking, access control, and security practices.

Key implementation areas included **Logical Volume Manager (LVM), Apache2, DNS, SSH, Linux users and groups, Access Control Lists (ACLs), UFW firewall configuration, and backup planning**.

The project provided hands-on experience combining Linux system administration with AWS cloud infrastructure and strengthened my understanding of how cloud-hosted Linux environments can be designed, secured, and maintained for enterprise workloads.

---

## 🎯 Business Challenge

PromisedLand.com required a reliable and secure server environment capable of supporting business web services while providing flexibility for future growth.

The project presented several infrastructure requirements, including effective storage management, controlled user access, secure remote administration, reliable web and DNS services, and protection against unauthorized network access.

To address these requirements, an **Ubuntu Server 24.04 LTS environment was deployed on Amazon EC2**, combining Linux system administration practices with AWS cloud infrastructure.

The solution was designed to provide a practical foundation for hosting enterprise services while maintaining security, manageability, and scalability.

---

## 🎯 Project Objectives

The primary objectives of this project were to:

- Deploy and configure **Ubuntu Server 24.04 LTS on Amazon EC2**.
- Implement flexible storage management using **Logical Volume Manager (LVM)**.
- Configure Linux users, groups, permissions, and **Access Control Lists (ACLs)**.
- Deploy and configure **Apache2** for web services.
- Configure **DNS services** for reliable name resolution.
- Secure remote administration using **SSH**.
- Configure the **UFW firewall** to control network access.
- Develop a backup and recovery strategy to support business continuity.
- Apply practical Linux and cloud administration best practices.

---

## 👨🏽‍💻 My Role

As the **Linux Systems Administrator**, I was responsible for deploying, configuring, securing, and documenting the infrastructure.

My responsibilities included:

- Provisioning and configuring the Ubuntu Server environment on **Amazon EC2**.
- Managing Linux storage using **LVM**.
- Creating and managing users, groups, permissions, and ACLs.
- Installing and configuring **Apache2** and DNS services.
- Configuring secure remote access through **SSH**.
- Implementing and managing **UFW firewall rules**.
- Testing system connectivity, services, storage, and security configurations.
- Documenting the completed infrastructure and administrative procedures.

This project was particularly valuable because it gave me practical experience combining **Linux system administration with AWS cloud infrastructure**.

---

## 🧰 Technologies Used

| **Technology** | **Purpose** |
|---|---|
| ![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white) **Ubuntu Server 24.04 LTS** | Enterprise Linux operating system used to host and manage server services. |
| ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white) **Amazon EC2** | Cloud platform used to provision and host the Linux server. |
| **LVM** | Provides flexible storage allocation and management. |
| ![Apache](https://img.shields.io/badge/Apache-D22128?style=flat-square&logo=apache&logoColor=white) **Apache2** | Web server used to host web services. |
| **Bind9 DNS** | Provides domain name resolution and DNS services. |
| ![SSH](https://img.shields.io/badge/SSH-222222?style=flat-square&logo=openssh&logoColor=white) **SSH** | Provides secure remote administration of the Linux server. |
| **UFW Firewall** | Controls network traffic and restricts unauthorized access. |
| **Linux Users & Groups** | Manages authentication, authorization, and administrative access. |
| **ACLs** | Provides granular file and directory access permissions. |
| ![AWS S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=flat-square&logo=amazons3&logoColor=white) **Amazon S3** | Supports the planned backup and disaster recovery strategy. |

---

## 🏗️ Solution Architecture

The infrastructure follows a layered architecture in which **Amazon EC2 provides the cloud computing foundation**, while Ubuntu Server hosts and manages the enterprise services.

The architecture combines web services, DNS, secure remote administration, storage management, access controls, and firewall protection into a single managed Linux environment.

#### Architecture Flow

```text
                         ☁️ Amazon Web Services
                                  │
                                  ▼
                       ┌─────────────────────┐
                       │     Amazon EC2      │
                       │ Ubuntu Server 24.04 │
                       └──────────┬──────────┘
                                  │
             ┌────────────────────┼────────────────────┐
             │                    │                    │
             ▼                    ▼                    ▼
       🌐 Apache2             🌍 Bind9 DNS          🔐 SSH
       Web Services           Name Resolution      Remote Access
             │                    │                    │
             └────────────────────┼────────────────────┘
                                  ▼
                       ┌─────────────────────┐
                       │     LVM Storage     │
                       └──────────┬──────────┘
                                  │
                    ┌─────────────┼─────────────┐
                    ▼             ▼             ▼
                 👥 Users       🔑 ACLs       🛡️ UFW
                 & Groups      Permissions    Firewall
                                  │
                                  ▼
                       ☁️ Amazon S3 Backup

#### Architecture Overview

The Ubuntu Server instance serves as the central platform for the infrastructure. Apache2 provides web services, while Bind9 handles DNS functionality and SSH enables secure remote administration.

Storage is managed using LVM, allowing disk resources to be organized and expanded efficiently. Linux users, groups, and ACLs provide controlled access to system resources, while UFW adds a network-level security layer.

A planned Amazon S3 backup strategy provides an additional layer of resilience for business continuity and disaster recovery.

### ☁️ AWS EC2 Instance Deployment

*Screenshot showing the Ubuntu Server instance running on Amazon EC2, including the instance status and `t3.micro` configuration.*

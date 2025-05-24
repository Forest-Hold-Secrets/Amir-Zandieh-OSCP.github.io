---
layout: post
title: "HackTheBox: Keeper"
date: 2024-01-15
description: "Easy Linux box focusing on KeePass exploitation and CVE research"
tags: [hackthebox, linux, keepass, cve]
---

## Machine Info
- **OS**: Linux
- **Difficulty**: Easy
- **Points**: 20
- **Release**: 12 Aug 2023

## Enumeration

Initial nmap scan:

```bash
nmap -sC -sV -oN nmap/initial 10.10.11.227

PORT   STATE SERVICE VERSION
22/tcp open  ssh     OpenSSH 8.9p1 Ubuntu
80/tcp open  http    nginx 1.18.0

Initial Access
[Your writeup content here...]
Privilege Escalation
[Your content here...]

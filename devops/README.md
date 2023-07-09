# Devops

## Learn a Language

I've learned them from working experience and side projects.

- [x] Nodejs
- [x] Python

## Posix

- [x] standard streams (stdin, stdout, stderr) [READ](https://www.baeldung.com/linux/posix)

## Understand different OS concepts

- [x] I/O Management [READ](https://www.tutorialspoint.com/operating_system/os_io_hardware.htm)
- [x] Memory/Storage [READ](https://www.geeksforgeeks.org/memory-management-in-operating-system/)
- [x] Virtualization [Qubes OS](https://www.qubes-os.org/intro/)
- [x] File Systems [READ](https://www.tutorialspoint.com/operating_system/os_file_system.htm)

For virtualization I'm using Qubes OS, I highly recommend it.

- [x] Startup Management (init.d)

For this i've created a script to start the test containers of one of my work projects on startup.

Also learned about systemd and how the first process is started by the kernel.

- [x] Service Management (systemd) [READ](https://www.geeksforgeeks.org/linux-systemd-and-its-components/)

Systemd works as a replacement of init.d and is used to manage services.

- [ ] Thread and concurrencys

- [x] Processes [READ](https://www.geeksforgeeks.org/processes-in-linuxunix/)

Types of processes:

- Foreground process: A process that is started from the command prompt and doesn’t return the prompt to the user until it is completed or terminated.

- Background process: A process that runs behind the scenes. It does not require user intervention and runs as a child process of the shell.

## Networking

For networking im taking a course on Cisco Networking Academy. Progress so far:

- [x] Module 1 - Communication in a Connected World
- [x] Module 2 - Network Components, Types, Connections
- [x] Module 3 - Wireless and Mobile Networks
- [x] Module 4 - Build a Home Network
- [x] Module 5 - Communication Principles
- [x] Module 6 - Network Media
- [x] Module 7 - The Access Layer
- [x] Module 8 - The Internet Protocol
- [ ] Module 9 - IPv4 and Networking Segmentation
- [ ] Module 10 - IPv6 Addressing Formats and Rules
- [ ] Module 11 - Dynamic Addressing with DHCP
- [ ] Module 12 - Gateways to Other Networks
- [ ] Module 13 - The ARP Process
- [ ] Module 14 - Routing Between Networks
- [ ] Module 15 - TCP and UDP
- [ ] Module 16 - Application Layer Services
- [ ] Module 17 - Network Testing Utilities
- [ ] Final Exam

[Course Link](https://skillsforall.com/course/networking-basics?courseLang=en-US)

## Operating Systems

### Linux

- [x] Ubuntu/Debian
- [ ] Suse
- [ ] RHEL/Derivatives

### Unix

- [ ] FreeBSD
- [ ] OpenBSD
- [ ] NetBSD

## Learn to live in Terminal

1+ year of experience working with terminal.

## Terminal Multiplexers

- [x] tmux
- [ ] screen

## Process Monitoring

- [x] top
- [x] htop
- [ ] ps
- [ ] atop
- [ ] lsof

## System Performance

- [ ] iostat
- [ ] vmstat
- [ ] sar
- [ ] nmon

## Network tools

- [x] ping
- [x] dig
- [ ] traceroute
- [ ] mtr
- [ ] nmap
- [ ] netstat
- [ ] ufw / firewalld
- [ ] tcpdump
- [ ] iptables / nftables
- [ ] scp

## Learn Bash Scripting

I've built multiple scripts and apps with only bash here are a few

[dotfiles](https://github.com/jd-apprentice/dotfiles)
[dbn-tools](https://github.com/jd-apprentice/dbn-tools)
[file-uploader](https://github.com/jd-apprentice/file-uploader)
[image-manager](https://github.com/jd-apprentice/image-manager-cli)

## Vim/Nano/Powershell/Emacs

- [x] Vim (I've used vim for a while, but I'm not a power user)
- [x] Nano (Same as vim)
- [ ] Powershell
- [ ] Emacs

## Compiling apps from source

- [x] gcc
- [x] make

To understand make files i've created multiple of them under a bunch of my projects here is one example

[example](https://github.com/jd-apprentice/config/blob/main/Makefile)

For gcc I've just compiled a few hello world apps.

[example](https://github.com/jd-apprentice/AppImage-Hello-World/blob/main/usr/Makefile)

## Text manipulation tools

Just for fun [cmd-challenge](https://github.com/jd-apprentice/cmd-challenge)

- [x] wc (just used it a few times)
- [x] echo (used it a lot)
- [x] cat (used it a lot)
- [x] grep (basic usage)
- [x] sort (basic usage)
- [ ] sed
- [ ] awk
- [ ] cut
- [ ] uniq
- [ ] tr
- [ ] fmt

### Others

- [x] history
- [ ] strace
- [ ] dtrace
- [ ] systemtap
- [ ] uname
- [ ] df
- [ ] du

## What is and how to setup a **\_** ?

- [x] Web Server (nginx)
- [x] Reverse Proxy
- [ ] Forward Proxy
- [ ] Caching Server
- [ ] Load Balancer
- [ ] Firewall

My personal projects are on a droplet on digital ocean, I've setup nginx for reverse proxy to redirect to my apps that are running inside there.

Also the ones that are webpages have certbot for ssl.

## Containerization

- [x] Docker
- [ ] LXC

For docker I've created a few images and compose files for my personal projects or work

[dockerfile #1](https://github.com/jd-apprentice/dbn-tools/blob/master/Dockerfile)
[dockerfile #2](https://github.com/jd-apprentice/waifuland-api/blob/master/Dockerfile)

[docker-compose #1](https://github.com/jd-apprentice/dbn-tools/blob/master/docker-compose.yml)
[docker-compose #2](https://github.com/jd-apprentice/Nodejs-TypeORM/blob/master/docker-compose.yml)
[docker-compose #3](https://github.com/jd-apprentice/waifuland-api/blob/master/docker-compose.yml)

## Intrastructure as Code

- [x] Ansible (Learning ansible atm)
- [x] Terraform (also learning terraform)
- [ ] Kubernetes

## CI/CD

- [x] Github Actions
- [ ] Gitlab CI
- [ ] Jenkins
- [ ] CircleCI

Examples of github actions I've created

[example #1](https://github.com/jd-apprentice/dbn-tools-docs/blob/89e16d49e55f1c4deed232ecc39bfd50d7b14ba3/.github/workflows/update-and-restart.yml)
[example #2](https://github.com/jd-apprentice/Portfolio-Next/blob/main/.github/workflows/update.yml)
[example #3](https://github.com/jd-apprentice/dbn-tools/blob/master/.github/workflows/release.yml)

## Logs Management

- [ ] ELK Stack
- [ ] Loki

## Application Monitoring

- [x] New Relic (Only the basics)
- [ ] AppDynamics
- [ ] Jaeger

## Infrastructure Monitoring

- [ ] Prometheus
- [x] Grafana (Only the basics)
- [ ] Datadog

## Cloud Providers

- [x] Digital Ocean
- [x] AWS (less experience than DO)
- [x] Heroku
- [ ] Azure
- [ ] GCP

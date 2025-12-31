# Chocolatey

Download latest version from Releases:       
https://github.com/wldap64/Chocolatey/releases/tag/2.5.1


## System requirements

* Compatible with Windows client and server operating systems (can also run on older versions).
* PowerShell v2 or higher (installation from this website requires at least v3 due to TLS 1.2).
* .NET Framework 4.8 (the installer will attempt to install .NET 4.8 if it is not already present).

## Introduction

Chocolatey is a Windows package manager that streamlines installing, updating, and managing software from the command line. Instead of searching for installers and clicking through setup wizards, you can deploy applications with a single command, making it a strong fit for developers, system administrators, and DevOps teams. Chocolatey packages capture silent install instructions and metadata (such as versioning, dependencies, and verification details), enabling repeatable, automated setups across laptops, servers, and CI/CD build agents.

Chocolatey can use public community repositories as well as private, internal feeds, so organizations can standardize approved software and control distribution. It integrates well with PowerShell and common automation tooling, allowing you to script environment provisioning, enforce consistent toolchains, and reduce configuration drift. Teams can also schedule upgrades, pin critical versions when stability matters, and produce deterministic workstation or build images.

For security-conscious environments, Chocolatey supports practices such as checksum validation, package moderation workflows, and repository governance. In regulated settings, you can mirror packages internally, restrict installation sources, and maintain audit-friendly change controls around what gets installed and when.

Beyond the open-source CLI, Chocolatey offers enterprise capabilities (often referred to as Chocolatey for Business), including centralized management, deployment orchestration, and reporting for large fleets of endpoints. Whether you’re onboarding a new developer workstation or managing thousands of Windows machines, Chocolatey provides a scalable approach to automating software lifecycle management.

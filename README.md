# Hardened Linux Workspace Deployment & Secure Lab Infrastructure

## Project Overview
This repository documents the deployment, virtualization provisioning, and architectural configuration of an enterprise-ready Linux testbed running Ubuntu 24.04.1 LTS. The core objective is to construct a secure foundational environment engineered for executing automated security toolsets, parsing network telemetry, and conducting controlled malware detonation experiments safely without exposing the baseline host network.

## Technical Artifacts Index
* Procedure.pdf: End-to-end console captures tracing hypervisor provisioning, guest ISO mounting, disk partition scaling, and baseline OS initialization.
* Requirements.md: System hardware baselines, distribution source image prerequisites, and virtualization hypervisor matrices.
* Links.md: Verified distribution registries tracking source packages for the target systems.

---

## Featured Engineering Walkthrough: Virtualized Hypervisor Provisioning

### 1. Hardware Emulation Profile
* Hypervisor Wizard Deployment: Initialized a Typical Workspace Configuration matrix within VMware Workstation Pro 17 to build a stable hardware profile.
* Compute Resource Allocation: Provisioned a balanced baseline consisting of 4 GB System Memory (RAM) and 2 logical processing cores to maintain consistent processing performance during live analysis streams.

### 2. OS Image Mounting & Automation Interface
* Guest Ingestion Pipeline: Routed the system storage controllers to target the official downloaded Ubuntu 64-bit disk image file (`ubuntu-24.04.1`).
* Automated Access Control: Configured local user accounts ('VinG') and administrative credential structures during the initial provisioning sequence to ensure zero deployment reliance on unencrypted default passwords.

### 3. Block Storage Partitioning & Sector Management
* Allocation Metrics: Established a standalone virtual block storage volume with a custom storage capacity threshold to support multi-tool installations.
* Segment Optimization: Implemented a split-disk sector management configuration layout. This splits the virtual storage unit into multiple logical files to optimize background host backup management and maximize virtual disk migration portability across external hypervisor frameworks.

---

## Core Systems Administration Competencies
* Hypervisor Engineering: Allocating computational, memory, and virtual block storage matrices across Type-2 hypervisors.
* Linux Kernel Workspace Deployment: Provisioning verified LTS distribution images from cold boot to desktop environment maturity.
* Secure Sandboxing Design: Building isolated host-only guest endpoints designed to fully contain automated vulnerability testing payloads.

# Miles Li

**Platform Engineer · Cloud-Native Architect · Infrastructure Builder**

> **The system is the core; I am its architect.**

I design and operate production infrastructure where **explicit boundaries, deterministic behavior, and controlled complexity** matter.

My work sits at the intersection of **Kubernetes, cloud infrastructure, distributed systems, observability, and automation** — turning fragmented infrastructure into reproducible, operable systems.

```text
Self-consistency
        +
Explicit boundaries
        +
Controlled complexity
        ↓
Higher-tier correctness
```

---

## 🧭 Engineering Philosophy

I tend to approach infrastructure as a system rather than a collection of services.

```text
Complexity
   │
   ├── eliminate what is unnecessary
   ├── isolate what must coexist
   ├── automate what can be declared
   └── observe what cannot be assumed
                │
                ▼
          Predictable Systems
```

I care particularly about:

* **Structural simplicity** over accidental complexity
* **Declarative infrastructure** over manual operations
* **Strong boundaries** between tenants, environments, and failure domains
* **Deterministic deployments** and reproducible infrastructure
* **Observable state** instead of implicit assumptions
* **Safe migrations** without unnecessary downtime
* **Automation** that reduces operational entropy

---

## ☁️ Platform & Cloud

```text
Cloud
├── AWS
│   ├── EKS
│   ├── VPC / TGW
│   ├── IAM
│   ├── ALB / Gateway
│   ├── S3
│   └── CloudWatch
│
└── Aliyun
    ├── ACK
    ├── VPC / CEN
    └── Cloud Infrastructure
```

My primary focus is building **multi-region, multi-tenant cloud platforms** with Kubernetes at the center.

Core technologies:

`Kubernetes` `EKS` `ACK` `Terraform` `Helm` `GitOps` `AWS` `Aliyun`

---

## ⚙️ Distributed Systems

I have worked extensively with stateful middleware and production migrations:

```text
Kafka
  ├── Cluster Operations
  ├── Replication
  ├── MirrorMaker
  └── Live Migration

Zookeeper
  └── Stateful Cluster Operations

RabbitMQ
  ├── Cluster Migration
  └── Zero-Downtime Cutover
```

One of my major infrastructure projects involved reconstructing and migrating mission-critical **Kafka, Zookeeper, and RabbitMQ** infrastructure across Southeast Asian regions, with a focus on:

* Zero-downtime migration
* Cross-region network topology
* Client transparency
* Message ordering
* Data integrity
* Controlled cutover and rollback

The interesting part was never simply moving the servers.

It was preserving the **system's behavior while its underlying topology changed**.

---

## 🔭 Observability

I treat observability as a first-class part of infrastructure design.

```text
                    ┌──────────────┐
                    │   Runtime    │
                    └──────┬───────┘
                           │
             ┌─────────────┼─────────────┐
             ▼             ▼             ▼
        Metrics         Logs          Events
             │             │             │
             ▼             ▼             ▼
       Prometheus         ELK         Splunk
             │
             ▼
          Grafana
             │
             ▼
       System Insight
```

Stack:

`Prometheus` `Grafana` `ELK` `Splunk` `node_exporter`

I am particularly interested in the gap between:

> **"the system is running"**

and

> **"we actually understand what the system is doing."**

---

## 🚀 Selected Projects

### 📊 K8s-Grafana

**Kubernetes observability & Prometheus dashboard engineering**

A collection of production-oriented Grafana dashboards and Prometheus queries for Kubernetes environments.

The goal is straightforward:

> Make cluster state visible enough that operational decisions can be made from evidence rather than intuition.

**Focus:** Kubernetes · Prometheus · Grafana · Metrics · Production Observability

[→ View repository](https://github.com/TheRealMilesLee/K8s-Grafana)

---

### 🖼️ Oura

**Declarative wallpaper delivery pipeline for Apple platforms**

An exploration of engineering aesthetics through a fully automated content pipeline.

```text
Git Repository
      │
      ▼
Asset Validation
      │
      ▼
Optimization
      │
      ▼
GitHub Actions
      │
      ▼
Edge Distribution
      │
      ▼
SwiftUI Client
```

**Focus:** SwiftUI · GitHub Actions · Automation · Content Delivery

[→ View repository](https://github.com/MilesCorporate/iOS-WallpaperCollections)

---

### 🗂️ The-Wallpaper-Collection

A GitHub-native image repository designed as a structured, version-controlled asset store.

Instead of treating wallpapers as static files, the project explores the idea of **content as an immutable, automatable data source**.

[→ View repository](https://github.com/MilesCorporate/The-Wallpaper-Collection)

---

### 🎵 MusicPlayer-macOS

**Native macOS audio player**

A minimalist native macOS music player focused on predictable lifecycle management, constrained abstractions, and a clean interaction model.

**Focus:** Swift · macOS · Audio · Native Systems

[→ View repository](https://github.com/MilesCorporate/MusicPlayer-macOS)

---

## 🏗️ Infrastructure Architecture

My preferred infrastructure model looks roughly like this:

```text
                     Git
                      │
                      ▼
              Declarative Configuration
                      │
          ┌───────────┴───────────┐
          ▼                       ▼
      Terraform                 Helm
          │                       │
          ▼                       ▼
      Cloud Layer            Kubernetes Layer
          │                       │
          └───────────┬───────────┘
                      ▼
                 Production
                      │
              ┌───────┴───────┐
              ▼               ▼
         Observability     Automation
              │               │
              └───────┬───────┘
                      ▼
               Controlled State
```

The objective is not to eliminate complexity.

It is to **make complexity explicit, bounded, and controllable**.

---

## 🧰 Technology

```text
Cloud
AWS · Aliyun

Container & Orchestration
Kubernetes · EKS · ACK · Helm

Infrastructure as Code
Terraform · GitOps

Networking
VPC · TGW · CEN · ALB · Gateway API

Middleware
Kafka · Zookeeper · RabbitMQ

Observability
Prometheus · Grafana · ELK · Splunk

Automation
GitHub Actions · Jenkins · GitLab CI

Systems
Linux · macOS

Languages
Python · Go · Bash · Swift · C/C++ · Java · SQL
```

---

## 🌌 Beyond Infrastructure

I enjoy engineering systems at different layers — from cloud control planes and distributed middleware down to native applications.

There is a common thread between them:

**reduce unnecessary complexity, define the boundaries, and make the system behave predictably.**

Infrastructure is where I spend most of my time.

But the underlying interest is broader:

> **How do we build systems that remain understandable as they become larger?**

---

## 📡 Network Handshake

**Static Wiki**
[therealmileslee.github.io](https://therealmileslee.github.io)

**Professional Graph**
[LinkedIn](https://linkedin.com/in/hengyi-li-968744191)

**Secure Gateway**
`trdli@ucdavis.edu`

---

```text
┌─────────────────────────────────────────────────────┐
│                                                     │
│   Build systems.                                    │
│   Reduce entropy.                                   │
│   Make complexity explicit.                         │
│                                                     │
│                  — Miles Li                          │
│                                                     │
└─────────────────────────────────────────────────────┘
```

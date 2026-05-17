# `whoami --profile miles.li`

```yaml
identity:
  name: Miles Li (Hengyi Li)
  role: Platform Engineer / Cloud-Native Architect
  motto: "The system is the core; I am its architect."
  logic: [Structural Rationalism, Complexity Reduction, Determinism]

```

---

> **"Self-consistency, explicit boundaries, and controllable complexity are, in themselves, a higher tier of correctness."**

---

## 🪐 System Specification

```nix
{ config, pkgs, ... }: {
  # Core Runtime Environment
  environment.systemPackages = with pkgs; [ linux macOS ghostty nix-flakes neovim ];

  # Architectural Directives
  orchestration.core = {
    engine = "Kubernetes (EKS / ACK)";
    state = "Declarative GitOps via Helm & Automated Pipelines";
    boundary = "Immutable compute layers with strict multi-tenant resource isolation";
  };

  infrastructure.provisioning = {
    provider = [ "AWS (PH/ID/MY)" "Aliyun" ];
    toolchain = "Terraform IaC with continuous state tracking";
    governance = "Cross-account S3 data migration and regional lifecycle compliance";
  };

  middleware.topology = {
    engines = [ "Kafka" "Zookeeper" "RabbitMQ" ];
    hardening = "Industrial-scale cluster governance, chaos injection, and zero-downtime live migrations";
  };

  observability.telemetry = {
    stack = [ "Prometheus" "Grafana" "ELK" "Splunk" ];
    objective = "Data-driven systemic insight, sub-millisecond alert vectors, and deterministic state capturing";
  };
}

```

---

## 🚀 Production Manifests & Repositories

### 📂 [K8s-Grafana](https://github.com/TheRealMilesLee/K8s-Grafana)

**Runtime Observability & Enterprise Telemetry Hardening**
This repository serves as a definitive blueprint for large-scale Kubernetes observability, translating chaotic cluster runtimes into deterministic, high-density visualization dashboards. It optimizes custom Prometheus vector queries to eliminate monitoring blind spots, ensuring total engineering control over stateful production environments.

### 🖼️ [Oura](https://github.com/MilesCorporate/iOS-WallpaperCollections) & [The-Wallpaper-Collection](https://github.com/MilesCorporate/The-Wallpaper-Collection)

**Declarative UI & Automated Content Delivery Pipelines**
An exploration of engineering aesthetics mapped onto mobile platforms. The architecture utilizes a headless GitHub repository as an immutable asset database, deploying automated GitHub Actions workflows to handle asset validation, optimization, and edge distribution, serving high-density visual states via SwiftUI and Kingfisher to the client device.

### 🎵 [MusicPlayer-macOS](https://github.com/MilesCorporate/MusicPlayer-macOS)

**Native Audio Engine & Structural Interaction Restraint**
A native macOS audio player engineered with minimalist constraints. It implements rigid memory allocations and tight lifecycle boundaries within the Swift audio core, internalizing raw sound waves into a predictable, highly performant system runtime while stripping away all non-essential UI friction.

---

## 🏭 Distributed System Milestones

**Southeast Asia Middleware Reconstruction**
Architected and executed the zero-disruption live migration of mission-critical Kafka, Zookeeper, and RabbitMQ clusters across the PH, ID, and MY regions. Engineered the entire cutover matrix to handle complex cross-border network topologies, ensuring complete client-side transparency, strict message ordering, and zero data loss across multi-terabyte stateful layers.

**IDC Cloud-Native Architecture Synthesis**
Reconstructed regional data center foundations into reproducible multi-tenant EKS clusters. Standardized internal environments via Terraform blueprints, effectively halting cross-region configuration drift, hardening IAM boundaries, and eliminating operational environmental entropy.

---

## 📊 Telemetry Stream

---

## 📡 Network Handshake

**Static Wiki** // [therealmileslee.github.io](https://therealmileslee.github.io)

**Professional Graph** // [LinkedIn](https://linkedin.com/in/hengyi-li-968744191)

**Secure Gateway** // `trdli@ucdavis.edu`

---

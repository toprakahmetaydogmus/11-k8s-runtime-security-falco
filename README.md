# ☸️ Kubernetes Runtime Threat Detection (Falco eBPF Rules & Hardening)

[![GitHub release (latest by date)](https://img.shields.io/github/v/release/toprakahmetaydogmus/11-k8s-runtime-security-falco?color=blue&label=Release)](https://github.com/toprakahmetaydogmus/11-k8s-runtime-security-falco/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

Developer: **Toprak Ahmet Aydoğmuş**

---

## 🎯 1. Overview
Kubernetes runtime security engine modeling eBPF kernel event detection via Falco rules. Detects container escapes, sensitive mount access (`/proc`, `/sys`), ServiceAccount token misuse, and unauthorized process spawning.

---

## 🚀 2. Quick Start

```bash
git clone https://github.com/toprakahmetaydogmus/11-k8s-runtime-security-falco.git
cd 11-k8s-runtime-security-falco
python -m unittest discover tests/
```

---

## 📜 3. License
Licensed under the [MIT License](LICENSE).  
Developer: **Toprak Ahmet Aydoğmuş**.

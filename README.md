# Git with GOST Support — Docker Image

This repository provides a Docker image with a custom-built version of Git that includes support for **GOST cryptography** (GOST R 34.10-2012 and GOST R 34.11-2012, etc). It is suitable for secure software development, CI/CD pipelines, and environments requiring compliance with Russian cryptographic standards.

## 🔐 Features

- Git compiled with OpenSSL fork that includes GOST algorithms
- Supports GOST digital signatures and hashes
- Lightweight and minimal base image
- Ready for integration into secure workflows

## 🐳 Usage

Build:

```bash
docker build -t <name> .
```

Run:

```bash
docker run -it -v $(pwd)/repo:/repo -t <name>
```

Run again:
```bash
docker start -ai <cont_name>
```

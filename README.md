# 🐳 PHP CLI Docker Image

[![Build & Push](https://github.com/nstwf-docker/php-cli/actions/workflows/docker-build-push.yml/badge.svg)](https://github.com/nstwf-docker/php-cli/actions/workflows/docker-build-push.yaml)
[![License](https://img.shields.io/github/license/nstwf-docker/php-cli)](LICENSE.md)

---

## Description

Lightweight PHP CLI image for running PHP scripts.

---

## Usage

Run `php -v` command:

```bash
docker run --rm nstwf/php-cli php -v
```

Run your PHP script:

```bash
docker run --rm -v $(pwd):/app -w /app nstwf/php-cli php your-script.php
```
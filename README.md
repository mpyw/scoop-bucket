# Scoop Bucket

This repository contains Scoop manifests for mpyw tools.

## Installation

```powershell
scoop bucket add mpyw https://github.com/mpyw/scoop-bucket.git
scoop install <manifest>
```

**Example:**

```powershell
scoop bucket add mpyw https://github.com/mpyw/scoop-bucket.git
scoop install suve
```

## Available Manifests

- **[sql-http-proxy](https://github.com/mpyw/sql-http-proxy)** - YAML configuration-based HTTP to SQL proxy server
- **[suve](https://github.com/mpyw/suve)** - Git-like CLI/GUI for AWS Parameter Store and Secrets Manager

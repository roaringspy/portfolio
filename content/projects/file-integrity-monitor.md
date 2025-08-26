---
title: "File Integrity Monitor (Python)"
date: 2025-08-27
draft: false
---

A custom Python-based tool to detect unauthorized file modifications in real-time.

### Key Features
- **Real-Time Monitoring**: Implemented the watchdog library to monitor file system events including creation, modification, deletion, and renaming.
- **Hash-Based Detection**: Utilized SHA256 hashing to detect unauthorized changes by comparing current file hashes against a stored baseline in a JSON file.
- **Customizable Patterns**: Enabled users to define include and exclude filename patterns for targeted and efficient file tracking.

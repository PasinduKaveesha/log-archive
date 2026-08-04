# Log Archive Tool

A simple Bash command-line tool to archive log files with a timestamp.

**Project URL:** https://roadmap.sh/projects/log-archive-tool  

![Bash](https://img.shields.io/badge/Bash-Script-blue)
![Linux](https://img.shields.io/badge/Platform-Linux-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Features

- Accepts any log directory as an argument
- Compresses logs into a `.tar.gz` archive
- Creates timestamped archive names (`logs_archive_YYYYMMDD_HHMMSS.tar.gz`)
- Stores archives in a dedicated `archived_logs/` directory
- Records every archive action in `archive.log`

## Usage

```bash
./log-archive <log-directory>

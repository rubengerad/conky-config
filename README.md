**Conky config to monitor memory, graphics card usage, Git repositories, and MCP servers for LLM Projects**

This conky configuration provides comprehensive monitoring for developers working on LLM projects, including:

## Features
- **System Information**: Hostname, OS, Kernel, Uptime
- **CPU Monitoring**: Usage, temperature, frequency, core details
- **Graphics Card**: NVIDIA GPU monitoring with CUDA cores, memory usage
- **Memory**: RAM and swap usage
- **Git Integration**: Repository status, branch, commits, and sync status
- **MCP Monitoring**: Model Context Protocol servers and LLM processes
- **I/O Performance**: Disk usage and read/write speeds
- **Network**: Interface monitoring with up/down speeds
- **Process List**: Top 10 processes by CPU/memory usage

## Git Monitoring
- Current repository name (from git working directory)
- Active git branch
- Repository status (clean/modified)
- Last commit information (hash + message)
- Number of unpushed commits

## MCP Monitoring
- Active MCP servers count
- GitHub MCP server processes
- Playwright MCP server processes
- Claude Desktop processes
- LLM-related processes (ollama, llama, openai, anthropic)

## Installation
1. Install conky: `sudo apt install conky-all` (Ubuntu/Debian)
2. Copy `conky.conf` to your home directory or desired location
3. Run: `conky -c /path/to/conky.conf`

## Usage
The configuration automatically detects git repositories and MCP servers in the current working directory where conky is executed. For best results, run conky from your development project directory.

![conky-mem-monitor](https://github.com/user-attachments/assets/d0a14f51-8ca9-43da-a085-dbd201bc132b)

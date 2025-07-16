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
- Current repository name
- Active git branch
- Repository status (clean/modified)
- Last commit information
- Number of unpushed commits

## MCP Monitoring
- Active MCP servers count
- Claude Desktop processes
- OpenAI API processes  
- LLM-related processes (ollama, llama, etc.)
- Python MCP processes

![conky-mem-monitor](https://github.com/user-attachments/assets/d0a14f51-8ca9-43da-a085-dbd201bc132b)

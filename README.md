# MCP Server

A MCP server that performs mathematical calculations and automatically creates PowerPoint presentations with the results.

## Overview

This project consists of three main components:
- `mcp-server.py`: The main server that provides mathematical and PowerPoint manipulation tools
- `mcp-client.py`: A sample client demonstrating basic usage
- `talk2mcp.py`: An advanced client using Gemini AI for natural language processing

## Features

- Mathematical Operations:
  - Basic arithmetic (add, subtract, multiply, divide)
  - Advanced math (power, square root, cube root, factorial)
  - Trigonometric functions (sin, cos, tan)
  - Special functions (ASCII conversion, exponential sums)

- PowerPoint Integration:
  - Automatic presentation creation
  - Rectangle drawing for result highlighting
  - Text formatting and positioning
  - Automated PowerPoint handling (open/close)


## Installation
1. Clone the repository
2. Install the required dependencies

```bash
pip install -r requirements.txt
```

## Usage

### Basic Usage (mcp-client.py)
```bash
python mcp-client.py
```
This will:

1. Convert text to ASCII values
2. Calculate exponential sums
3. Create a PowerPoint presentation with results

### Advanced Agentic AI Usage (talk2mcp.py)
```bash
python talk2mcp.py
```

Requires:

- Gemini API key in .env file

# DnSmoke

A tool to generate random DNS noise.

## Installation
`pip install dnsmoke`

## Usage
You can add the command to your **system startup**  to ensure it runs in the background automatically or run when required.

- **Basic run:** `dnsmoke` or  `python3 dnsmoke.py`
- **Custom speed (default 6 queries/min):** `dnsmoke -q 15`
- **Avoid specific network (Home IP):** `dnsmoke -n 192.168.1.12`
- **Use custom domain list:** `dnsmoke -f domains.txt`

## Arguments
- `-q` : Queries per minute (Default: 6)
- `-n` : IP to avoid (exits if matched)
- `-f` : Load custom domains from file


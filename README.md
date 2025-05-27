# Prerequisites
- **Go 1.18+** installed and added to your PATH.
If you don’t have Go installed yet, you can download it here: https://go.dev/dl/
- Terminal:
  - PowerShell / CMD (for Windows)
  - Git Bash / WSL / Linux terminal (for bash scripts)

## ⚙️ Building the server

1. Open your terminal and navigate to the repository folder:
```bash
cd PATH_TO_YOUR_REPOSITORY
```
2. build the server (this will generate a <b>server.exe</b> file):

```bash
go build 
```

## Running the server
After building, start the server:

```bash
./server.exe
```

The server listens on port **8080**

If it starts successfully, you should see a message like:

```bash
Server running on port 8080...
```

📁 Examples in the examples/ folder
The project includes an examples/ directory with helper scripts for API testing.

# Example usage 
Located at:

```bash
examples/login.sh
```

# How to use
1. Navigate into the examples folder:

```bash
cd examples
```

2. Make sure the script is executable:

```bash
chmod +x login.sh
```

3. Run the script with your credentials:

```bash
./login.sh user pass
```
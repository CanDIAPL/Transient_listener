# Transient listener #

Codebase to listen to real time data streams (GCNs, TNS etc.) and store them in database, most probably MongoDB.

### Environment Installation
Used `uv` to do most of the installation here. Use the following list of commands
```
# Install uv (if not already installed)
$ curl -LsSf https://astral.sh/uv/install.sh | sh  # Linux/macOS or WSL
# Or: powershell -c "irm https://astral.sh/uv/install.ps1 | iex"  # Windows

# Create virtual environment 
uv venv ### or uv venv my-env-name
source .venv/bin/activate # On Windows: .venv/Scripts/activate
# or source my-env-name/bin/activate

# Install packages for development
$ uv pip install -e ".[dev]"  
```

### Repository Structure ###

TBD

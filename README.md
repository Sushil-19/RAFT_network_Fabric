# Hyperledger Fabric Test Network

A complete Hyperledger Fabric test network with 2 organizations, 1 peer per organization, 1 Raft ordering node, CouchDB, and Hyperledger Explorer.

## Quick Start

### Prerequisites
- WSL2 with Ubuntu 22.04
- Docker & Docker Compose
- Node.js 18+
- jq
- fabric binaries installed properly with env vars set properly

### One-Command Setup

```bash
# Clone the repository
git clone <your-repo-url>
cd <repository-name>

# Make script executable
chmod +x chain.sh

# Run the script (takes 10-15 minutes)
./chain.sh

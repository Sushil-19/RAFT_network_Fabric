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
git clone https://github.com/Sushil-19/RAFT_network_Fabric.git
cd RAFT_network_Fabric

# Make script executable
chmod +x chain.sh

# Run the script (takes 10-15 minutes)
./chain.sh
```
### Results are like below
<img width="1352" height="677" alt="Screenshot 2026-02-14 184832" src="https://github.com/user-attachments/assets/ba508727-6e87-443b-9cfe-dbf796091947" />
<img width="1346" height="692" alt="Screenshot 2026-02-14 185011" src="https://github.com/user-attachments/assets/7b3c4b5a-3382-46b1-b420-0c7afe194853" />
<img width="1344" height="691" alt="Screenshot 2026-02-14 185028" src="https://github.com/user-attachments/assets/5cd3396f-a251-47a8-8d31-dec5a1da67de" />
<img width="1357" height="703" alt="Screenshot 2026-02-14 185056" src="https://github.com/user-attachments/assets/b4b63679-5bd1-409c-a62d-ad43099f4b75" />
<img width="1356" height="698" alt="Screenshot 2026-02-14 185138" src="https://github.com/user-attachments/assets/b56904d8-1cb0-4c29-a297-f9a6f2b1d1c0" />
<img width="1356" height="686" alt="Screenshot 2026-02-14 185205" src="https://github.com/user-attachments/assets/693df5af-c152-4842-9973-45c26dc3b282" />
<img width="1359" height="684" alt="Screenshot 2026-02-14 185237" src="https://github.com/user-attachments/assets/7179f626-f450-424f-a69f-fc88dffe7667" />

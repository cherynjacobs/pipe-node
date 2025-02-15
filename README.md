# pipe-node
# Pipe Network Node Setup

Follow these instructions to set up a Pipe Network Node.

## 1️⃣ Install the `pop` Binary
```bash
curl -L -o pop "https://dl.pipecdn.app/v0.2.5/pop"
chmod +x pop

2️⃣ Create a Cache Directory
```bash
mkdir download_cache
3️⃣ Sign Up with Referral Code
./pop --signup-by-referral-route 381fc9dcb6255802
4️⃣ Start the Node
./pop \
  --ram 8 \              # Set RAM in GB  
  --max-disk 500 \       # Max disk usage in GB  
  --cache-dir /data \    # Cache location  
  --pubKey <YOUR_SOLANA_PUBLIC_KEY>  # Your Solana wallet address
🛠 Troubleshooting Command:

If you get any errors, use this:
./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <YOUR_SOLANA_PUBLIC_KEY>
5️⃣ Save Node Info (Important!)
nano ~/node_info.json
Make any necessary changes, then press Ctrl + X, then Y, and Enter to save.
6️⃣ Check Node Status
./pop --status
7️⃣ Check Points Earned
./pop --points
8️⃣  Restart Node the Next Day
./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <YOUR_SOLANA_PUBLIC_KEY>


Docs- https://docs.pipe.network/devnet-2

Check Points & Status From Dashboard -: https://dashboard.pipenetwork.com/node-lookup

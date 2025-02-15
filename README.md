# 🚀 Pipe Network Node Setup Guide
Follow these steps to set up and run your node.

## 🔹 1️⃣ Install
```bash
curl -L -o pop "https://dl.pipecdn.app/v0.2.5/pop"
chmod +x pop
🔹 2️⃣ Make Directory
```bash

mkdir download_cache
🔹 3️⃣ Sign-up With Command
```bash

./pop --signup-by-referral-route d93ec7a125f095ab
🔹 4️⃣ Start The Node
bash
Copy
Edit
./pop \
  --ram 8 \              
  --max-disk 500 \       
  --cache-dir /data \    
  --pubKey <YOUR_SOLANA_PUBLIC_KEY>
🛠 Troubleshooting
If you face any errors, try running:

bash
Copy
Edit
./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <YOUR_SOLANA_PUBLIC_KEY>
🔹 5️⃣ Save Node Info (Very Important!)
bash
Copy
Edit
nano ~/node_info.json
After editing, press Ctrl + X, then Y, and Enter to save.

🔹 6️⃣ Check Node Status
bash
Copy
Edit
./pop --status
🔹 7️⃣ Check Points Earned
bash
Copy
Edit
./pop --points
🔹 8️⃣ Generate Referral Code
bash
Copy
Edit
./pop --gen-referral-route
🔹 9️⃣ Restart Node Next Day
bash
Copy
Edit
./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <YOUR_SOLANA_PUBLIC_KEY>
yaml
Copy
Edit

Install
bash
Copy
Edit
curl -L -o pop "https://dl.pipecdn.app/v0.2.5/pop"
chmod +x pop
Make Directory
bash
Copy
Edit
mkdir download_cache
Sign-up With Command
bash
Copy
Edit
./pop --signup-by-referral-route d93ec7a125f095ab
Start The Node
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
Save Node Info (Very Important!)
bash
Copy
Edit
nano ~/node_info.json
After editing, press Ctrl + X, then Y, and Enter to save.

Check Node Status
bash
Copy
Edit
./pop --status
Check Points Earned
bash
Copy
Edit
./pop --points
Generate Referral Code
bash
Copy
Edit
./pop --gen-referral-route
Restart Node Next Day
bash
Copy
Edit
./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <YOUR_SOLANA_PUBLIC_KEY>

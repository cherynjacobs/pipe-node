# 🚀 Pipe Network Node Setup Guide  
Follow these steps to set up and run your node.  

## 1️⃣ Install  

```bash
curl -L -o pop "https://dl.pipecdn.app/v0.2.5/pop"
chmod +x pop
```

2️⃣ Make Directory
```bash
mkdir download_cache
```
3️⃣ Sign-up With Command

```bash
./pop --signup-by-referral-route 6c9dde82ae4757c3 
```
4️⃣ Start The Node
```bash
./pop \
  --ram 8 \              
  --max-disk 500 \       
  --cache-dir /data \    
  --pubKey <YOUR_SOLANA_PUBLIC_KEY>
```
  🛠 Troubleshooting
If you face any errors, try running:
```bash
./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <YOUR_SOLANA_PUBLIC_KEY>
```
5️⃣ Save Node Info (Very Important!)
```bash
nano ~/node_info.json
```
After editing, press Ctrl + X, then Y, and Enter to save.
6️⃣ Check Node Status
```bash
./pop --status
```
7️⃣ Check Points Earned
```bash
./pop --points
```
8️⃣ Restart Node Next Day
```bash
./pop --ram 8 --max-disk 500 --cache-dir /data --pubKey <YOUR_SOLANA_PUBLIC_KEY>
```

Docs- https://docs.pipe.network/devnet-2

Check Points & Status From Dashboard -: https://dashboard.pipenetwork.com/node-lookup
```
![image](https://github.com/user-attachments/assets/bea4bff1-020e-40dd-bb07-3bd827bfa6b1)


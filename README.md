# 🚀 Pipe Network Node Setup Guide  
Follow these steps to set up and run your node.  
## ⚠️ Prerequisites  

### **For Ubuntu Users**  
✅ No extra setup required.  

### **For Windows Users**  
🔹 **Install Windows Subsystem for Linux (WSL):**
To download wsl in windows you can watch videos in youtube there are plenty of them and its simple

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
 #dont forget to edit the public key 
 
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



hi

# 🚀 EthStorage V1 Trusted Setup Ceremony (Local/VPS Guide)

## 📌 Requirements
- Ubuntu 22.04 (Local PC या VPS)
- 2 vCPU, 4 GB RAM, 30+ GB SSD
- GitHub account (≥ 1 महीना पुराना, ≥ 1 Public repo, ≥ 5 followers, ≥ 1 following, Gists enabled)

---

## 🛠 Installation Steps

### 1. सिस्टम अपडेट करें
```bash
sudo apt update && sudo apt upgrade -y
sudo apt install -y curl git build-essential
2. Node.js v18 और npm v9.2 इंस्टॉल करें
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt install -y nodejs
sudo npm install -g npm@9.2
3. वर्शन चेक करें
node -v
npm -v
4. Temporary वर्कस्पेस बनाएं
mkdir ~/trusted-setup-tmp && cd ~/trusted-setup-tmp
5. Phase2 CLI इंस्टॉल करें
sudo npm install -g @p0tion/phase2cli
6. CLI वर्शन चेक करें
phase2cli --version
7. GitHub Authentication
phase2cli auth
GitHub login करें
p0tion को Gists read/write access allow करें
8. Ceremony में योगदान दें
screen -S ceremony
phase2cli contribute -c ethstorage-v1-trusted-setup-ceremony
screen से बाहर: Ctrl+A, D
वापस आने के लिए:
screen -r ceremony
9. Cleanup (optional)
phase2cli clean
phase2cli logout
rm -rf ~/trusted-setup-tmp
✅ GitHub Checklist
 अकाउंट ≥ 1 महीना पुराना
 ≥ 1 Public Repository
 ≥ 5 Followers
 ≥ 1 Following
 GitHub Gists enabled
🎉 Done! अब आप Ceremony में सफलतापूर्वक शामिल हो गए हैं।


---

ये version 100% plain text है — कोई hidden character या fancy quotes नहीं,  
GitHub में डालोगे तो commands एकदम clean copy होंगी और terminal में error नहीं आएगा।  

तुम चाहो तो मैं अभी इसे तुम्हारे `BHUWANBOOS/EthStoragenode` repo के README में डालने के लिए final version बना सकता हूँ।
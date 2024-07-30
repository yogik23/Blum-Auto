# Blum-Auto Claim Game 

Copas Satu-satu ke termux
```
pkg update
```
```
pkg install nano
```
```
pkg install nodejs 
```
```
pkg install npm
```
```
npm audit fix
```
```
git clone https://github.com/fattahkus/blum
```
```
cd blum
```
```
ls
```
```
nano blum.json
```
```
npm install
```
```
node index.js
```

Delete File nano dan buat ulang File nano
```
rm -rf blum.json && nano blum.json
```

Done

# Blum-Auto Claim Game in VPS

Install Tmux 
```
apt install tmux
```
Buat Sesi baru blum
```
tmux new-session -s blum
```
Instal semua package
```
apt install nano
```
```
apt install nodejs
```
```
apt install npm
```
```
npm audit fix
```
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh
```
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```
```
source ~/.bashrc
```
```
nvm list-remote  
```
```
nvm install v22.3.0
```
```
nvm alias default node
```
Jalankan Blum
```
git clone https://github.com/fattahkus/blum
```
```
cd blum
```
```
rm -rf blum.json && nano blum.json
```
```
npm install
```
```
npm audit fix --force
```
```
node index.js
```

Keluar dari sesi tmux ```ctrl-b + d``` \
Masuk sesi tmux
```
tmux attach-session -t blum
```

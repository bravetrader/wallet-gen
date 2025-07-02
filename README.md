# wallet-gen
```
curl -fsSL https://bun.sh/install | bash
exec $SHELL
bun --version
```
Allow port 8888
```
sudo apt update && sudo apt install ufw -y
sudo ufw allow 8888
```
Clone repo
```
git clone https://github.com/bravetrader/wallet-gen
```
```
cd wallet-gen
```
Install dependencies:
```
bun install
```
Build dependencies:
```
bun run build
```
Start and generate your wallet, wallet address info will be save in folder wallet-gen
```
bun start
```
Faucet: [octra faucet](https://faucet.octra.network/)

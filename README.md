# Interacao-com-Uniswap
Este repositório demonstra como interagir com o Uniswap V3 em testnet (Sepolia).
# 🚀 Uniswap Testnet Interaction

Este repositório demonstra como interagir com o **Uniswap V3** em uma **testnet Ethereum** (ex: Sepolia ou Goerli) utilizando **Node.js** e **Ethers.js**.

---

## 📋 Pré-requisitos

- Ubuntu com Node.js instalado  
- Conta no [Metamask](https://metamask.io/) configurada para a testnet  
- ETH de faucet na testnet escolhida  
- Acesso ao RPC da rede (ex: [Infura](https://infura.io/) ou [Alchemy](https://www.alchemy.com/))  

---

## ⚙️ Instalação

```bash
# Atualizar pacotes
sudo apt update && sudo apt upgrade -y

# Instalar Node.js e npm
sudo apt install nodejs npm -y

# Clonar este repositório
git clone https://github.com/seu-usuario/uniswap-testnet-demo.git
cd uniswap-testnet-demo

# Instalar dependências
npm install
PRIVATE_KEY="sua_chave_privada"
RPC_URL="https://sepolia.infura.io/v3/SEU_PROJECT_ID"


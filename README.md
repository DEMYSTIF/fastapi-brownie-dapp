# FastAPI-Brownie-DApp

Ethereum Certificate DApp made for Pythonistas.

## 🛠 Built With

<div align="left">
<a href="https://docs.python.org/3/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/DEMYSTIF/DEMYSTIF/main/assets/icons/python.svg" width="36" height="36" alt="Python" /></a>
<a href="https://eth-brownie.readthedocs.io/en/stable/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/DEMYSTIF/DEMYSTIF/main/assets/icons/ethereum.svg" width="36" height="36" alt="Ethereum" /></a>
<a href="https://docs.vyperlang.org/en/stable/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/DEMYSTIF/DEMYSTIF/main/assets/icons/vyper.svg" width="36" height="36" alt="Vyper" /></a>
<a href="https://fastapi.tiangolo.com/tutorial/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/DEMYSTIF/DEMYSTIF/main/assets/icons/fastapi.svg" width="36" height="36" alt="FastAPI" /></a>
</div>

## ⚙️ Run Locally

Clone the repository

```bash
git clone https://github.com/DEMYSTIF/fastapi-brownie-dapp
cd fastapi-brownie-dapp
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

> For Linux

```bash
source /venv/bin/activate
```

> For Windows PowerShell

```bash
.\venv\Scripts\Activate.ps1
```

Install packages

```bash
pip -r requirements.txt
```

Compile the contract

```bash
brownie compile
```

Test the contract

```bash
brownie test
```

Run a blockchain (ganache/geth/foundry) on http://127.0.0.1:8545

Deploy the contract

```bash
brownie run deploy_cert.py
```

Start the application

```bash
uvicorn main:app --reload
```
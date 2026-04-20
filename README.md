# EVM Wallet Generator

Simple and fast tool to generate multiple EVM-compatible wallets (Ethereum, BSC, Polygon, etc.) using Python.

---

## Features

* Generate multiple EVM wallets
* Export wallets to JSON file
* Extract wallet addresses into TXT file
* Works offline (secure local generation)

---

## Requirements

* Python 3.8+
* pip

---

## Installation

Clone repository:

```
git clone https://github.com/kol2000/EVM-wallet-generator.git
cd EVM-wallet-generator
```

Install dependencies:

```
pip install -r requirements.txt
```

---

## Usage

Run the script:

```
python main.py
```

Then choose:

```
1 - Generate wallets
2 - Extract addresses
3 - Exit
```

---

## Example

Generate 5 wallets:

```
Enter number of wallets: 5
```

---

## Output

* wallets.json → contains private keys and addresses
* wallet_addresses.txt → contains only wallet addresses

---

## Example Output

```
0xAbc123...
0xDef456...
```

---

## Security

* NEVER share your private keys
* Store generated wallets securely
* This tool works locally, but security depends on your system

Private keys give full access to funds.

---

## Supported Networks

* Ethereum
* Binance Smart Chain (BSC)
* Polygon
* Arbitrum
* Optimism

---

## Tech Stack

* Python
* eth-account

---

## TODO

* [ ] Add mnemonic support (BIP39)
* [ ] Add CSV export
* [ ] Add CLI arguments
* [ ] Add Docker support

---

## Author

Alexander — https://github.com/kol2000

---

## Contributing

Pull requests are welcome.
If you have ideas — open an issue

# MnemonicBrute

## Overview
MnemonicBrute is a robust and efficient tool designed to brute force Ethereum wallet mnemonics. It operates using a multi-threaded approach, ensuring surprisingly fast performance. This tool automatically generates seed phrases and checks balances on Ethereum networks. If a wallet with a non-zero balance is found, the wallet's details (address, mnemonic, private key, and balances) are logged and saved to a file named `result.txt`.

## Features
- **High Performance:** Utilizes multi-threading for faster processing.
- **Automatic Generation:** Automatically generates Ethereum seed phrases.
- **Balance Checking:** Checks balances for generated wallets on Ethereum networks.
- **Detailed Logging:** Logs and saves wallet information for wallets with non-zero balances.
- **Secure:** Ensures the security and integrity of the brute force process.
 
## Latest version
Also you can download the latest version of the program in the release section

## Installation
To install MnemonicBrute, clone the repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/MnemonicBrute.git
cd MnemonicBrute
pip install -r requirements.txt
```

## Usage
Run the tool using the following command:

```bash
python mnemonicbrute.py
```

The tool will start generating seed phrases and checking wallet balances. All results will be saved in `result.txt`.

## Demonstration

![1](https://github.com/user-attachments/assets/dc57fb0b-dd50-4436-8fa6-967537509708)

## Contributing
We welcome contributions from the community. If you wish to enhance the functionality or security of this tool, please fork the repository and submit a pull request with your improvements.

## Acknowledgments
- **Community Support:** Thanks to the community for providing the underlying technologies that make this tool possible.
- **User Contributions:** Gratitude to all users who contribute by sharing their feedback and improvements.

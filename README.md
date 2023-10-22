# CrossChainSentinel - Cross-Chain Smart Contract Vulnerabilities Dataset

CrossChainSentinel is a comprehensive dataset of cross-chain smart contract vulnerabilities, designed to facilitate research, development, and security analysis of smart contracts. This dataset includes 300 files, consisting of 158 benign smart contracts and 142 malicious smart contracts, distributed across various vulnerability types, such as reentrancy, integer overflow/underflow, and unprotected ether withdrawal.

## Dataset Overview

- **Total Files:** 300
  - **Benign Files:** 158
  - **Malicious Files:** 142
    - **Reentrancy:** 42
    - **Integer Overflow/Underflow:** 48
    - **Unprotected Ether Withdrawal:** 52

## Files Structure

The dataset is organized in the following directory structure:
CrossChainSentinel/ \\
│ \\
├── Total/ \\
│ ├── Contract1.sol \\
│ ├── Contract2.sol \\
│ ├── ... \\
│ \\
├── Benign/ \\
│ ├── Contract1.sol \\
│ ├── Contract2.sol \\
│ ├── ... \\
│ \\
├── Malicious/ \\
│ ├── Reentrancy/ \\
│ │ ├── Contract159.sol \\
│ │ ├── Contract160.sol \\
│ │ ├── ... \\
│ │ \\
│ ├── Integer Overflow/Underflow/ \\
│ │ ├── Contract201.sol \\
│ │ ├── Contract202.sol \\
│ │ ├── ... \\
│ │ \\
│ ├── Unprotected Ether Withdrawal/ \\
│ │ ├── Contract249.sol \\
│ │ ├── Contract250.sol \\
│ │ ├── ... \\
│ \\
├── Labels/ \\
│ ├── contract_labels.csv \\
│ ├── detail_label.csv \\

- The `Total/` directory contains all smart contract files.
- The `Benign/` directory contains benign smart contract files.
- The `Malicious/` directory contains malicious smart contract files, categorized by vulnerability type.
- The `Labels/` directory includes label CSV files, one for benign and another for malicious contracts.

## CSV Labels

- `contract_labels.csv` - This file contains labels for benign smart contracts, indicating they are free from known vulnerabilities.
- `detail_label.csv` - This file contains labels for malicious smart contracts, including the type of vulnerability they contain.

## License
This dataset is provided under the LICENSE. Please review and comply with the license terms before using the dataset.

## Acknowledgments
We would like to express our gratitude to the contributors, researchers, and organizations that contributed to the creation and curation of the CrossChainSentinel dataset.

For any questions, concerns, or inquiries, please contact anhkiet1227@gmail.com or 20520605@gm.uit.edu.vn
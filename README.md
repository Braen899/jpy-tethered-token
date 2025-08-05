# JPY Tethered

JPY Tethered (JPYT) is a decentralized yen-pegged stablecoin deployed on the TRON blockchain as a TRC-20 token.

## ℹ️ Token Details
- **Website**: [https://www.jpyt.dev](https://www.jpyt.dev)
- **Contract**: `TKe8ncE5EcE8t5jvN6YRxpd5xHGi7LG85t`
- **Symbol**: `JPYT`
- **Decimals**: `6`

## 📁 Repository Structure

### `/contracts/JPYT.sol`
- This is the **modular contract** written using OpenZeppelin imports.
- Best for development and understanding the contract logic.
- Requires external dependencies (`@openzeppelin/...`) when compiling.

### `/contracts/Flattened_JPYT.sol`
- This is the **flattened version** of the contract.
- Contains all dependencies in a single file (no imports).
- Used for verification on [TRONSCAN](https://tronscan.org) or other block explorers.

### `/metadata/JPYT_metadata.json`
- Standard metadata used for verification or integration into dApps and explorers.

### `tokenlist.json`
- JSON definition of the token (symbol, decimals, logo URI, etc.)
- Useful for inclusion in wallets or aggregators.

---

## 🧾 License

This project is licensed under the MIT License.

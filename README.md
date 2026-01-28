# My Dapp

A Web3 application - foundation built with Cradle

## Getting Started

### Prerequisites

- Node.js >= 20.0.0
- pnpm >= 9.0.0
- Rust (for Stylus contracts)

### Installation

```bash
pnpm install
```

### Environment Variables

Copy `.env.example` to `.env` and fill in the required values:

```bash
cp .env.example .env
```

Required variables:
- `NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID`: WalletConnect Cloud project ID for wallet connections
- `PRIVATE_KEY`: Private key for deployment and transactions

### Development

```bash
pnpm dev
```

### Available Scripts

- `pnpm dev`: Start development server
- `pnpm build`: Build for production
- `pnpm start`: Start production server
- `pnpm lint`: Run ESLint
- `pnpm deploy:token`: Deploy ERC20 token
- `pnpm token:info`: Get token information

## Project Structure

```
├── src/                 # Application source code
├── contracts/           # Stylus smart contracts
├── docs/               # Documentation
├── .github/            # GitHub Actions workflows
└── package.json
```

## License

MIT

---

Generated with ❤️ by [Cradle](https://cradle.dev)

# Skeleton Health — Frontend

Patient-facing web application for managing encrypted health records on blockchain. Built as a single-page app with MetaMask wallet integration.

## Features

- **MetaMask Authentication**: Connect with any Web3 wallet
- **Record Dashboard**: View, upload, and manage encrypted health records
- **Access Control**: Grant time-limited access to healthcare providers
- **Audit Trail**: View complete history of who accessed your records
- **Storage Plans**: Manage IPFS storage allocation
- **Client-Side Encryption**: AES-256-GCM — all encryption happens in your browser

## Tech Stack

- Vanilla JavaScript (no framework)
- Ethers.js v6 (wallet & contract interaction)
- Web Crypto API (AES-256-GCM encryption)
- CSS Custom Properties (design system)

## Setup

```bash
# Serve locally
npx serve .

# Or open index.html directly in browser
```

The app connects to the backend API and Polygon blockchain automatically.

## Architecture

See the [full technical architecture doc](https://github.com/skeleton-health/docs/blob/main/02_TECHNICAL_ARCHITECTURE.md).

## License

MIT — see [LICENSE](LICENSE)

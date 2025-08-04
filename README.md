# Chrono Clash

Chrono Clash is a turn-based multiplayer battle game built on Etherlink. Players connect their crypto wallets, stake tokens, and compete in strategic battles for real rewards. All game logic, match results, and payouts are handled on-chain for maximum fairness and transparency.

## Features

- **Turn-based Multiplayer Battles:** Challenge friends or match with others in real time.
- **Staking & Winnings:** Stake tokens before each match; the winner takes the prize, paid out instantly via smart contract.
- **On-chain Game Logic:** All core gameplay, including moves, results, and rewards, is secured by the Etherlink blockchain.
- **Wallet Integration:** Connect with MetaMask, WalletConnect, or other Ethereum-compatible wallets.
- **Unique Characters:** Play as Zeus, Athena, Hades, or Nyx—each with their own abilities and playstyles.
- **Rich UI & Audio:** Enjoy smooth animations, sound effects, and a modern, responsive interface.

## Quick Start

1. **Install dependencies:**
   ```bash
   pnpm install
   ```

2. **Set up environment:**
   - Copy `.env.example` to `.env` and set your Etherlink RPC URL and WalletConnect Project ID if needed.

3. **Run the app:**
   ```bash
   pnpm dev
   ```
   Visit [http://localhost:3000](http://localhost:3000) in your browser.

4. **Connect your wallet:**  
   Use the in-game wallet connect button. Make sure you’re on the Etherlink Testnet.

5. **Play & Battle:**  
   Choose your character, stake tokens, and start battling!

## Smart Contract

- The core game logic is in `contract/main.sol` (`BattleArena` contract).
- Handles character management, match creation/joining, turn-based moves, and automatic payout to winners.
- Stakes are pooled and the winner receives the prize minus a small platform fee.

## Contract Address

- **Address:** `0x7B80B5f84C84F2DfC4846938e8B1b3283d75453a`
- **Explorer:** [View on Etherlink Explorer]([https://testnet-explorer.etherlink.com](https://testnet.explorer.etherlink.com/address/0x7B80B5f84C84F2DfC4846938e8B1b3283d75453a))

## Etherlink Integration

- Uses Etherlink for fast, low-cost, and Ethereum-compatible transactions.

## Tech Stack

- Next.js 15, React 19, TypeScript
- TailwindCSS for styling
- Solidity smart contracts (Etherlink L2)
- Framer Motion, Howler.js for UI/UX

## License

MIT

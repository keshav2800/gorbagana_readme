# Gorbana Wordle 🎮

A fast, Solana-based Wordle game built on the Gorbagana testnet. Experience Wordle like never before with blockchain integration, multiplayer modes, and token rewards!

## 🎯 Game Overview

Gorbana Wordle transforms the classic Wordle game into a blockchain-powered experience with three exciting game modes:

### 📅 Daily Challenge
- Play the daily Wordle and build your streak
- Track your progress with persistent streaks
- Compete on the global leaderboard
- Earn tokens for consistent performance

### ⚔️ Word Duel
- Go head-to-head with another player in real-time
- Winner takes all token rewards
- Private room creation for friends
- Live opponent tracking

### 👑 Word Royale
- Global tournament-style competition
- Multiple players compete simultaneously
- Token prize pools for top performers
- Real-time leaderboard updates

## 🚀 Gorbagana Integration

This game is built specifically for the **Gorbagana testnet**, leveraging:

- **Zero-MEV execution** for fair gameplay
- **Instant finality** for real-time multiplayer
- **Web2-like speed** for seamless user experience
- **Native test tokens** for rewards and incentives
- **Backpack wallet** integration for easy access

### Blockchain Features
- Wallet-based authentication
- Token rewards for achievements
- On-chain game state verification
- Decentralized leaderboards
- Smart contract integration for fair play

## 🛠️ Technology Stack

- **Frontend**: Next.js 14 with TypeScript
- **Styling**: Tailwind CSS with custom animations
- **Animations**: Framer Motion
- **State Management**: Zustand
- **Blockchain**: Solana Web3.js
- **Wallet**: Backpack Wallet Adapter
- **Deployment**: Vercel

## 📦 Installation & Setup

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Backpack wallet extension

### Local Development

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd gorbana-wordle
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env.local
   ```
   
   Add your Gorbagana testnet RPC endpoint:
   ```
   NEXT_PUBLIC_RPC_ENDPOINT=your-gorbagana-rpc-endpoint
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000)

### Production Build

1. **Build the application**
   ```bash
   npm run build
   ```

2. **Start the production server**
   ```bash
   npm start
   ```

## 🎮 How to Play

### Getting Started
1. Connect your Backpack wallet
2. Choose your preferred game mode
3. Start playing Wordle with blockchain rewards!

### Game Rules
- Guess the 5-letter word in 6 attempts
- Green tile: Letter is correct and in right position
- Yellow tile: Letter is in the word but wrong position
- Gray tile: Letter is not in the word
- Complete the word to win tokens!

### Token Rewards
- **Daily Challenge**: 1-5 tokens based on performance
- **Word Duel**: Winner takes all (10-50 tokens)
- **Word Royale**: Tournament prizes (100-1000 tokens)

## 🔧 Configuration

### Gorbagana Testnet Setup
1. Add Gorbagana testnet to your Backpack wallet
2. Get test tokens from the faucet
3. Configure RPC endpoint for optimal performance

### Customization
- Modify word lists in `components/games/DailyGame.tsx`
- Adjust token rewards in game components
- Customize UI themes in `tailwind.config.js`

## 🚀 Deployment

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Set environment variables in Vercel dashboard
3. Deploy automatically on push to main branch

### Manual Deployment
1. Build the application: `npm run build`
2. Upload build files to your hosting provider
3. Configure environment variables

## 📱 Mobile Support

The game is fully responsive and optimized for:
- iOS Safari
- Android Chrome
- Mobile wallets (Backpack mobile)

## 🤝 Contributing

We welcome contributions! Please see our contributing guidelines:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🐛 Support

- **Discord**: Join our community for support
- **Twitter**: Follow [@Gorbagana_chain](https://twitter.com/Gorbagana_chain) for updates
- **GitHub Issues**: Report bugs and feature requests

## 🙏 Acknowledgments

- Built for the Gorbagana testnet hackathon
- Inspired by the original Wordle game
- Powered by Solana blockchain technology
- Community-driven development

---

**Built with ❤️ for the Gorbagana community**

*Play Wordle on Solana's fastest testnet!* 
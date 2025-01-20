# StarkGuardian 🛡️

StarkGuardian is an AI-powered Telegram bot that helps users interact with Starknet blockchain through natural language commands. Built using Eliza, OpenAI, and Starknet Agent Kit, it provides easy access to wallet management and token operations.

## ✨ Core Features

### Wallet Information
- View wallet public address
- Check ETH balance
- List all token balances
- Get token details and prices

### Token Operations
- Transfer tokens to other addresses
- Swap tokens between pairs
- Check transaction status

### Telegram Bot Integration
- Natural language interaction
- Real-time responses
- User-friendly interface
- Secure wallet operations

## 🛠️ Technology Stack

### Core Technologies
- Eliza Framework
- OpenAI Integration
- Starknet Agent Kit
- Telegram Bot API

### Key Components
- **Eliza**: Natural language processing and command handling
- **OpenAI**: Advanced prompt processing and response generation
- **Starknet Agent Kit**: Blockchain interaction and transaction management
- **Telegram Bot**: User interface and command processing

## 💬 Usage Examples

### Checking Wallet Details
```
"Show my wallet details"
"What's my ETH balance?"
"List all my tokens"
```

### Token Transfers
```
"Send 1 ETH to 0x1234..."
"Transfer 100 USDC to 0xabcd..."
```

### Token Swaps
```
"Swap 1 ETH to USDC"
"Exchange 100 USDT for ETH"
```

## 🚀 Getting Started

### Prerequisites
```bash
- Node.js v23+
- pnpm
- Telegram Bot Token
- Starknet Wallet
```
## Edit the character files

Open `src/character.ts` to modify the default character. Uncomment and edit.

### Custom characters

To load custom characters instead:
- Use `pnpm start --characters="path/to/your/character.json"`
- Multiple character files can be loaded simultaneously

### Add clients
```
clients: [Clients.TWITTER, Clients.DISCORD],
```

## Duplicate the .env.example template

```bash
cp .env.example .env
```

### Environment Setup
```env
STARKNET_PRIVATE_KEY=your_private_key
ANTHROPIC_API_KEY=your_api_key
STARKNET_RPC_URL=your_rpc_url
TELEGRAM_BOT_TOKEN=your_bot_token
PUBLIC_ADDRESS=your_public_address
```

### Installation
```bash
# Clone the repository
git clone https://github.com/ankit875/starkguardian.git

# Install dependencies
cd starkguardian
pnpm install

# Start the bot
pnpm start
```

## 🔒 Security Features

- Secure private key handling
- Transaction confirmation prompts
- Error handling and validation
- Rate limiting protection

## 🛣️ Future Enhancements

### Planned Features
- Multi-wallet support
- DeFi protocol integration
- Advanced analytics
- Portfolio tracking
- Price alerts

## 📝 Hackathon Notes

This project was developed for the Starknet Hackathon 2024, focusing on:
- Natural language interaction with Starknet
- Seamless telegram bot integration
- Token management and swaps
- Wallet information retrieval

## 🙏 Acknowledgments

- Starknet Foundation
- OpenAI Team
- Eliza Framework Developers
- Starknet Agent Kit Team


Note: this requires node to be at least version 23 when you install packages and run the agent.

# SMS Handler BOT

A bot for handling SMS-related services, including buying numbers and checking OTP statuses from SMS-RU and SMS-Activate.

## Features

- Buy numbers from SMS-RU and SMS-Activate
- Check OTP status for purchased numbers
- Delete numbers (SMS-RU)
- View balances for both services

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js
- npm

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/sms-handler-bot.git
   cd sms-handler-bot
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env` file in the root directory and add your API keys:

   ```plaintext
   SMSHUB=your-smshub-api-key
   SMSACTIVATE=your-smsactivate-api-key
   ```

   You can get your API keys by registering on these services:
   - [SMSHub](https://smshub.org/en/main)
   - [SMS-Activate](https://sms-activate.io/en)

### Usage

Run the bot by executing the following command:

```bash
npm start
```

You will be presented with a menu to select between SMS-RU and SMS-Activate services.

## Donations

If you would like to support the development of this project, you can make a donation using the following addresses:

- **Solana**: `95m5zAspEMNy5Dhc6hGCuUKygP8e7kLLC6dz23cJ13nk`
- **EVM**: `0xa7816292d470BC4e4426a5FAdA71A42C0f370C53`
- **BTC**: `bc1qj7han8vx7vzd7ecwkmkqytgd403326qcjcq5at`

### License

This project is licensed under the MIT License.

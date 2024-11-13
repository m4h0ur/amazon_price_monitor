# Amazon Price Monitor Bot 🤖

A Telegram bot that monitors product prices on Amazon.nl and Amazon.de, alerting users when prices change.

## Features ✨

- Monitor product prices from Amazon.nl and Amazon.de
- Real-time price change notifications
- Support for multiple products per user
- Easy to use Telegram interface
- Docker containerization for easy deployment

## Prerequisites 📋

- Python 3.11+
- Docker
- Telegram Bot Token

## Installation 🚀

1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/REPO_NAME.git
cd REPO_NAME
```

2. Configure environment variables:
   - Copy `.env.example` to `.env`
   - Add your Telegram Bot Token

```bash
TELEGRAM_BOT_TOKEN=your_token_here
CHECK_INTERVAL=3600
```

3. Build and run with Docker:
```bash
docker-compose up -d
```

## Usage 💡

Available commands:
- `/start` - Start the bot
- `/help` - Show help message
- `/add <url>` - Add a product to monitor
- `/list` - List monitored products
- `/remove` - Remove a product from monitoring

## Project Structure 📁

```
amazon-price-monitor/
├── docker-compose.yml
├── Dockerfile
├── requirements.txt
├── README.md
└── src/
    └── price_monitor.py
```

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📄

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

- Thanks to the Python Telegram Bot community
- Beautiful Soup documentation
- Docker documentation
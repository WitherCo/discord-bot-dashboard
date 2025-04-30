# Discord Bot Dashboard

An open-source dashboard for managing Discord bots. Built with `Node.js`, `Express.js`, `React.js`, and `Discord.js`. Free for anyone to use and contribute to.

## Features
- User authentication via Discord OAuth2.
- Manage bot settings and commands.
- View server statistics and activity.
- Role and moderation tools.

## Getting Started

### Prerequisites
- Node.js installed
- A Discord bot token
- MongoDB or PostgreSQL for storing data

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/WitherCo/discord-bot-dashboard.git
   cd discord-bot-dashboard
   ```

2. Install dependencies:
   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. Set up environment variables:
   - Create a `.env` file in the `backend` directory with the following:
     ```
     DISCORD_TOKEN=your-bot-token
     CLIENT_ID=your-client-id
     CLIENT_SECRET=your-client-secret
     REDIRECT_URI=http://localhost:5000/auth/callback
     ```

4. Run the backend:
   ```bash
   cd backend
   npm start
   ```

5. Run the frontend:
   ```bash
   cd frontend
   npm start
   ```

6. Open `http://localhost:3000` in your browser.

## Contributing
See [CONTRIBUTING.md](CONTRIBUTING.md).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

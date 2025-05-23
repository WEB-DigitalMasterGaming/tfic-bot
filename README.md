﻿# TFIC Discord Bot
TFIC Discord Bot
This is the official Discord bot for The Frontier Initiative Corporation (TFIC) — a Star Citizen organization.

The bot handles event management, role-based RSVPs, real-time embed updates, and full integration with the TFIC org website.

Tech Stack
Language: Node.js (ES6+ syntax)

Library: discord.js

Hosting: Railway (serverless hosting)

Backend Integration: REST API calls to TFIC website backend

Authentication: Discord OAuth + Bot Tokens

Features
✅ Event Creation with Interactive RSVP Buttons
✅ Real-Time Event Embed Updates (Discord ↔ Website Sync)
✅ Department-based RSVP Role Handling
✅ Capacity-limited RSVP Management
✅ Dynamic Role and Username Display on Events
✅ Secure API Integration with JWT Authorization
✅ Full Slash Command Support (coming soon)

Development Setup
Prerequisites
Node.js 18+

Yarn

A Discord Bot Application (with correct permissions)

Local Setup
bash
Copy
Edit
# Clone the repo
git clone https://github.com/DreamVisionGames/tfic-bot.git

# Navigate into project directory
cd tfic-bot

# Install dependencies
yarn install

# Start the bot
yarn start
Environment Variables
Create a .env file in the root:

ini
Copy
Edit
DISCORD_TOKEN=your_discord_bot_token
DISCORD_CLIENT_ID=your_bot_client_id
DISCORD_GUILD_ID=your_server_guild_id (optional for guild-specific commands)
BACKEND_API_URL=https://your-backend-api-url
BACKEND_API_KEY=your_jwt_or_secret_for_api
DISCORD_TOKEN - Your bot's login token from the Discord Developer Portal.

BACKEND_API_URL - Your TFIC backend API base URL.

BACKEND_API_KEY - Secure key for authenticating API requests to the backend.

Deployment Notes
Bot is deployed to Railway.

Railway automatically manages environment variables securely.

Ensure you update permissions when inviting your bot (requires:

Send Messages

Manage Messages

Embed Links

Use Application Commands

Manage Roles (if dynamically assigning roles later))

Related Repositories
TFIC Website Frontend

TFIC Website Backend + API

License
Private Repository.
All rights reserved © DreamVision Games | TFIC 2025+

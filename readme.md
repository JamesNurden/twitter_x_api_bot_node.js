Twitter X API Bot

This repository contains a Node.js application for a Twitter bot that leverages both the Twitter API and the OpenAI API to tweet automatically. The bot is scheduled to tweet every hour and includes authentication and token management.

Table of Contents

Features

Installation

Usage

Configuration

Contributing

License

Features

Automated Tweeting: The bot tweets regularly at scheduled intervals.
Twitter Authentication: Secure OAuth 2.0 authentication with Twitter.
OpenAI Integration: Generates tweet content using OpenAI's GPT-3.
Firebase Firestore: Stores tokens and other necessary data.

Installation

To get started with the Twitter X API Bot, follow these steps:

Clone the repository:

git clone https://github.com/your-username/twitter_x_api_bot_node.js.git
cd twitter_x_api_bot_node.js

Install dependencies:

npm install

Set up environment variables: 

Create a .env file in the root directory and add your Twitter API credentials, OpenAI credentials, and 

Firebase credentials:

TWITTER_CLIENT_ID=your_twitter_client_id
TWITTER_CLIENT_SECRET=your_twitter_client_secret
OPENAI_API_KEY=your_openai_api_key
FIREBASE_PROJECT_ID=your_firebase_project_id

Start the server:

node index.js

Usage

Once the server is running, the bot will:

Authenticate with Twitter.
Generate tweet content using OpenAI.
Tweet the generated content every hour.

Running the Bot

To run the bot locally, execute:

node index.js

Configuration

Ensure you have the necessary credentials and configurations:

Twitter API: Obtain the Client ID and Client Secret from your Twitter Developer Portal.
OpenAI API: Sign up on the OpenAI website and get your API key.
Firebase: Set up a Firebase project and get your credentials.

Firestore Setup

Ensure your Firebase project is set up to use Firestore for storing tokens. Your Firestore database should have a document for storing OAuth tokens.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes or improvements.

Fork the repository.
Create a new branch.
Make your changes.
Open a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for more details.

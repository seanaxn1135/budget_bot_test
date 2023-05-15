# Telegram Bot

This project is a Telegram bot built using TypeScript, GTS for linting, and ESLint for code formatting. The bot utilizes the `telegraf` library for interacting with the Telegram Bot API and the `google-spreadsheet` package for working with Google Spreadsheets.

## Prerequisites

Before running this bot, make sure you have the following installed:

- Node.js (https://nodejs.org) - LTS version recommended

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/seanaxn1135/budget_bot.git

   ```

2. Navigate to the project directory:

   ```bash
   cd budget-bot

   ```

3. Install the dependencies using npm:

   ```bash
   npm install
   ```

## Configuration

1. Obtain a Telegram Bot token by creating a new bot using the BotFather. Note down the token as you will need it later.
2. Configure the bot token:

   - Create a new file named .env in the project root directory.
   - Add the following line to the .env file, replacing <YOUR_TOKEN> with your actual bot token:
     ```.env
     TELEGRAM_BOT_TOKEN=<YOUR_TOKEN>
     ```

## Usage

To start the bot, run the following command in the project directory:

```bash
npm start
```

This command compiles the TypeScript code to JavaScript and starts the bot using Node.js.

## Linting and Formatting

To lint your code and ensure it follows the project's coding style, you can use the following npm scripts:

    - npm run lint: Runs the linter and reports any linting errors.
    - npm run fix: Attempts to automatically fix linting errors when possible.

## Testing

This project uses Jest as the testing framework and Playwright for end-to-end testing. To run the tests, follow these steps:

1.  Ensure that the bot is running or start the bot using npm start.

2.  Open a new terminal and navigate to the project directory.

3.  Run the following command to execute the tests:

    ```bash
    npm test
    ```

# 🚀 Deploying a Contact Form on Cloudflare Workers

## Setting Up the Required Code:

1. Begin by creating a Telegram bot using [BotFather](https://t.me/botfather) and obtain its API Token.
2. Activate your bot by sending `/start` in its Private Messages.
3. Navigate to [Yoshitsu](https://yoshitsubot.t.me?start=github) and retrieve your User ID using the `/id` command.
4. Edit the `cf-worker.js` file located in your project directory, adding your Bot token and User ID.
5. Ensure to save and apply the modifications to the `cf-worker.js` file.

## Deploying the Cloudflare Worker:

1. Access [Cloudflare Workers](https://workers.cloudflare.com) and create an account if you haven't already.
2. Craft a new worker and paste the JavaScript code from your modified `cf-worker.js` file.
3. Activate and deploy the worker to generate its unique URL.

## Integrating with Your Website:

1. Navigate to your website's codebase.
2. Locate the `[form_worker_url]` placeholder within the `index.html` file.
3. Replace the placeholder with the URL of your deployed Cloudflare worker.

---

### Reddit Joke Bot
This Reddit bot responds to comments on selected subreddits with jokes retrieved from a database. The bot looks for certain phrases in comments and replies with a joke that fits the context.

### Installation
To use this bot, follow these steps:

1. Clone the repository to your local machine using git clone https://github.com/your_username/reddit-joke-bot.git.
2. Change into the project directory using cd reddit-joke-bot.
3. Create a virtual environment using python -m venv env.
4. Activate the virtual environment using source env/bin/activate (Linux/Mac) or env\Scripts\activate (Windows).
5. Install the required packages using pip install -r requirements.txt.
6. Create a Reddit account and a new Reddit app here.
7. In the app's settings, add a redirect URI with the value http://localhost:8000/.
8. Note down the client_id and client_secret for your Reddit app.
9. Create a .env file in the root directory of the project and add the following variables using the following format:
### 
1. REDDIT_CLIENT_ID=<your_client_id>
2. REDDIT_CLIENT_SECRET=<your_client_secret>
3. REDDIT_USERNAME=<your_reddit_username>
4. REDDIT_PASSWORD=<your_reddit_password>
### Usage
To use the bot, follow these steps:

1. Start the bot using python bot.py.
2. The bot will look for comments containing certain phrases and respond with a joke retrieved from the database.
3. The bot will continue to run until you stop it manually.
### Troubleshooting
If you encounter any issues while using the bot, please try the following troubleshooting steps:

1. Make sure you have created a Reddit app and added the necessary variables to your .env file.
2. Check the console for any error messages.
3. If you are not seeing any responses from the bot, check that the bot has been granted the necessary permissions to access the subreddit.
4. If you are still experiencing issues, please create a new issue on the project's GitHub page.
### Credits
This bot was created by [Your Name]. The jokes are retrieved from a database.

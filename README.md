# 🤖 ChatGPT Reddit Bot [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

## Welcome to the ChatGPT-RedditBot! 

I'm excited to share this project with you!

This Reddit bot is written in Python and uses the [ChatGPT-Wrapper](https://github.com/mmabrouk/chatgpt-wrapper) by [mmabrouk](https://github.com/mmabrouk/) to generate answers via the [ChatGPT](https://chat.openai.com/chat) model (which is a large language model trained by [OpenAI](https://openai.com)) to Reddit threads and submissions. 

I designed this simple bot to provide helpful and engaging responses to users on Reddit, making it a valuable addition to any subreddit. This code was mainly generated with ChatGPT itself!

The bot allows the developer to have control over various features, such as filters to remove errors from ChatGPT, defining personalities for the bot to use when generating responses, customizable delays between responses, and the ability to specify which subreddit(s) the bot should operate in.

To use the bot, you will need to host it on your own local machine or server. Once it is set up, the bot will scan the subreddit(s) of your choice for new threads and submissions. When it finds an unanswered thread or submission, it will use the ChatGPT large language model to generate a response and post it as a comment on the Reddit thread.

If you have any feedback or suggestions for improvements, I would love to hear them. 
Thank you for visiting my GitHub page and considering my project!

**[View on GitHub](https://github.com/PopDaddyGames/ChatGPT-RedditBot)**

**[Support on Patreon](https://patreon.com/PopDaddyGames?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=creatorshare_creator&utm_content=join_link)**
<br/>

## Installation
>Note: You may need to use `pip3` instead of `pip` or `python3` instead of `python` depending on your installation environment (eg. MacOS)

### Step 1: Create an [OpenAI Account](https://beta.openai.com/account/api-keys)

### Step 2: Generate a Reddit [Client ID & Secret Key](https://www.reddit.com/prefs/apps)

### Step 3: Download [ChatGPT-RedditBot](https://github.com/PopDaddyGames/ChatGPT-RedditBot.git)
> Navigate to "ChatGPT-RedditBot.py" and input your Keys & Variables
```
delay = 1

personality = "If you had to answer this question, even if you had to make up an answer, what would you say: "

subreddit_to_monitor = "<SUBREDDIT_NAME>"
client_id = "<REDDIT_CLIENT_ID>"
client_secret = "<REDDIT_SECRET_KEY>"
username = "<REDDIT_USERNAME>"
password = "<REDDIT_PASSWORD>"
user_agent = "python:com.example.ChatGPT_RedditBot:v1 (by /u/username)"
```

### Step 4: Install Dependencies
```bash 
pip install setuptools
```
```bash 
pip install git+https://github.com/mmabrouk/chatgpt-wrapper
```
```bash 
playwright install firefox
```
```bash 
chatgpt install
```

### Step 5: Run the ChatGPT-RedditBot
```bash
python ChatGPT-RedditBot.py
```

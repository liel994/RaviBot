# Discord Bot

This Discord bot provides features such as music playback, member verification, and basic moderation tools like mute, kick, and ban.

## Requirements

- Python 3.x
- discord.py
- yt-dlp
- python-dotenv

## Setup

1. Clone this repository:
   
git clone https://github.com/your-username/your-repository-name.git
2. Install the required dependencies:

pip install -r requirements.txt
3. Create a `.env` file in the same directory and add your Discord bot token:

DISCORD_TOKEN=your_token_here
4. Run the bot:


## Commands

- `!play <url>`: Play a YouTube video in a voice channel
- `!pause`: Pause the music
- `!resume`: Resume the music
- `!stop`: Stop the music and disconnect the bot from the voice channel
- `!join`: Make the bot join your voice channel
- `!leave`: Make the bot leave the voice channel
- `!mute <@member>`: Mute a member in the server
- `!unmute <@member>`: Unmute a member in the server
- `!kick <@member> [reason]`: Kick a member from the server (optional reason)
- `!ban <@member> [reason]`: Ban a member from the server (optional reason)
- `!unban <member_name>`: Unban a member by their username
- `!deafen <@member>`: Deafen a member in a voice channel
- `!undeafen <@member>`: Undeafen a member in a voice channel

## How it works

- When the bot is added to your server, it will automatically send a welcome message to a specific channel when a new member joins.
- A verification button will appear in the "verification" channel, allowing users to gain the "member" role by clicking it.

## License

This bot is open-source and free to use. Modify and distribute it as you wish. (Feel free to add any license you prefer)


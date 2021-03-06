# vebxor-discord-bot

Simple discord bot for some fun commands, made using discord.py

## Setup/Installation
- Create a bot at the [discord developer pages](https://discord.com/developers/applications) and add to your server.  
  

- Install the required python packages:  
>`pip install -r requirements.txt`   
     
   
- Install FFmpeg for the host machine. For linux/debian:  
>`sudo apt install ffmpeg`

- Make a .env file with the token for your discord bot, called DISCORD_TOKEN, e.g:
>`DISCORD_TOKEN=SECRETTOKEN123466134`
## Run
run the main.py file on your host machine from *src* folder:
>`python main.py`

## Commands

- **.roll** *x* *y*  
Simulates rolling an x-sided dice y number of times. 

- **.imdbs** *moviename*
Search for a movie on IMDB with the name *moviename*, showing the rating, genres, and an URL.

- *play_sound*  
  This command uses the file name (without extension (mp3)) as a command to play the mp3 file in the user's channel. E.g ape.mp3 is played with the following command.  
    
  **.ape**
  The bot joins the user writing the command's voice channel and plays the *ugy_jon.mp3* file.

- **.yomama**
The bot tells a random yo mama joke. 

- **.play** *YouTube URL*  
  Play sound from a YouTube video in the current voice channel.

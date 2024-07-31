<div align="center">

  <a href="https://discord.gg/9FVBpcHz">
    <img src="https://img.shields.io/discord/1079074933008781362.svg?label=Discord&logo=Discord&colorB=7289da&style=for-the-badge" alt="Support">
  </a>

<br>

  <a href="https://www.python.org/downloads/">
    <img src="https://img.shields.io/badge/Made%20With-Python%203.9-blue.svg?style=for-the-badge&logo=Python" alt="Made with Python 3.9">
  </a>
</div>

## open-source usando TrueSkill MMR.

### 
`Python 3.9.X` - [aqui](https://www.python.org/downloads/)

`pip` - https://pypi.org/project/pip/

1. Clone or Download this repository:
```bash
git clone git@github.com:HenrySpartGlobal/InHouseQueue.git
```
2. Rename a `.env.example` to `.env`.

3. Fill in all the details
Check out https://github.com/InHouseQueue/generate-emoji-ids to automatically print emoji Ids without doing these 1 by 1. Make sure you have emojis uploaded to your server. Only fill in emoji IDs for the games you are playing.

```env
# Discord Bot Token
TOKEN=

# Emoji ID's for Roles in League of Legends
# Example <:MID:1066065288862380033>
# To get this, In discord Enter the emoji and add \ to the start of it. Then press enter.
TOP=""
JUNGLE=""
MID=""
SUPPORT=""
ADC=""

# Emoji ID's for Roles in Valorant
CONTROLLER=""
DUELIST=""
INITIATOR=""
SENTINEL=""

# Emoji ID's for Roles in Overwatch
TANK=""
DPS=""
SUPPORT_OW=""

# Discord ID of Owners. Use the SAME ID for BOTH values if there is only 1 owner.
DEV_1=
DEV_2=

# Guild/Server ID of where the bot is running. Use the SAME ID for BOTH values if there is only 1 server.
GUILD_1=
GUILD_2=

# Discord ID of the Bot
BOT_ID=

# Discord ID of the Error Log channel. Use the SAME ID for BOTH values if there is only 1 error log channel.
ERROR_LOG_CHANNEL_ID_1=
ERROR_LOG_CHANNEL_ID_2=

```
5. Install requirements. 
   1. `pip install -r requirements.txt`

6. Run the Bot
```
python3 main.py


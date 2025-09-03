## Installation

1. First, clone the repository:  
   ```bash
   git clone https://github.com/bucu0368/Bots-ThunderX
   ```
2. After cloning, run the bot:
   ```bash
   python main.py
   ```
## Setting Up

1. Rename `example.env` to `.env` and replace the bot token value:
   ```env
   TOKEN=YOUR_BOT_TOKEN_HERE
   ```
   • Replace the Owner ID(s) [here](https://github.com/bucu0368/Bots-ThunderX/blob/main/utils/config.py#L7) (in `utils/config.py`).
2. **Prefix:**
   Default Prefix: `$`
   > You can change prefix **[here](https://github.com/bucu0368/Bots-ThunderX/blob/main/utils/Tools.py#L84)**.
   
4. **For Music:**  
   A public Lavalink is used, get a list of more public lavalinks available [here](https://lavalinks-list.vercel.app/). For better audio quality, it is recommended to set up your private Lavalink v4.  
   > Update your Lavalink URL, password, and other configurations [by clicking here](https://github.com/bucu0368/Bots-ThunderX/blob/main/cogs/commands/music.py#L339).
- If you are using your private lavalink & have youtube plugin enabled/working but the Spotify plugin is not working, than you can Uncomment Lines `(445 - 452)` in `(cogs/commands/music.py)`, this will convert a Spotify track to YouTube Track.

5. **Logging & Notifications:**  
   - **Command Logs:** Get a channel webhook URL and update it [here](https://github.com/bucu0368/Bots-ThunderX/blob/main/main.py#L75) (in `main.py`).  
   - **Guild Joins:** Add the channel ID [here](https://github.com/bucu0368/Bots-ThunderX/blob/main/cogs/events/on_guild.py#L25) (in `cogs/events/on_guild.py`).  
   - **Guild Leaves:** Add the channel ID [here](https://github.com/bucu0368/Bots-ThunderX/blob/main/cogs/events/on_guild.py#L109) (in `cogs/events/on_guild.py`).

6. **No Prefix Commands:**  
   There are several `np` commands like `np add`, `np remove`, `auto np add`, `auto np remove`, `auto np role`, etc. Check and modify them as needed in `cogs/commands/np.py`.

7. **Emojis & Colors:**  
   Unfortunately, there is no centralized setup for emojis & embed colors. You need to manually update emojis in all files where they are used.

To obtain a license or permission, [join our support server](https://discord.gg/odx).

## Made By Bucu0368
[GitHub](https://github.com/bucu0368)

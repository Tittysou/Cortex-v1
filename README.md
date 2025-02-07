# Discord Bot Base - Cortex

Welcome to the **Cortex Discord Bot Base**! This base is designed to provide a solid foundation for developing a feature-rich and efficient Discord bot.

## Features

- **Slash Commands & Prefix Commands**
- **Custom Event Handling**
- **Database Integration (MongoDB & SQLite)**
- **Modular Command System**
- **Error Handling & Logging**
- **Auto-Reloading for Commands & Events**
- **Permission & Cooldown System**
- **Multi-Guild Support**

## Requirements

- Node.js (latest LTS version recommended)
- Discord.js (v14 or later)
- A Discord bot token ([Get one here](https://discord.com/developers/applications))
- A database (optional but recommended for persistent data)

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/Tittysou/Cortex-v1.git
   cd Cortex-v1
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Rename the `example-config.json` to `config.json`:
   ```env
{
    "token": "",
    "id": "",
    "developerIds": [ 
    "",
    ""
    ],
    "devGuild": "",
    "prefix": "",
    "mongoDBUrl": ""
}
   ```

4. Start the bot:
   ```sh
   npm start
   ```

## Usage

- **Running the bot in development mode:**
  ```sh
  npm run dev
  ```

## Contributing

Feel free to fork this repository and submit pull requests with improvements, bug fixes, or new features!

Happy coding! 🚀


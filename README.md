# VSayPlugin

🧩 **VSayPlugin** is a lightweight plugin for Spigot 1.16.5 that allows server staff to broadcast global messages with a custom author name and sound notification.

--------------------------------------------------------------------------

## 📦 Features

- Simple command: `/vsay <author> <message>`
- Fully customizable message format
- Sound notification for all online players
- Easy language and formatting configuration
- Supports color codes

-------------------------------------------------------------------

## 📂 Installation

1. Download the compiled `VSayPlugin.jar`
2. Place it into your server's `plugins/` directory
3. Restart the server
4. Optionally edit `config.yml` for translations or custom formatting

---------------------------------------------------------------

## ⚙️ Configuration (`config.yml`)

messages:
  usage: "&cUsage: /vsay <author> <message>"
  format: "&6{author}&7 → &r{message}"
  consoleFormat: "&8[VSay] &6{author}&7 → &r{message}"
{author} will be replaced with the specified name

{message} will be replaced with the full message

Supports color codes using &
---------------------------------------------

💬 Example Usage

/vsay Ve1gos &aWelcome to the server!
/vsay Server &cRestart in 5 minutes!

Players will see:

Ve1gos → Welcome to the server!
Server → Restart in 5 minutes!

---------------------------------------------

🔐 Permissions
Permission	Description
vsay.use	Allows usage of the /vsay command

# Stingbat Bot
## A Discord bot for playing Shadowdark RPG

<div style="overflow: hidden; margin-bottom: 20px;" markdown="1">
<img src="images/avatar_prod.png" alt="StingBat Bot Avatar" style="float: left; width: 100px; margin: 5px 15px 15px 0; border-radius: 10px;" />
This is a Discord bot designed for playing [Shadowdark RPG](https://www.thearcanelibrary.com/pages/shadowdark "Shadowdark RPG"), by The Arcane Library. It is heavily inspired by [Avrae](https://avrae.io/), a bot designed for playing D&D 5e. I had previously made an attempt to use Avrae for Shadowdark, but found that the differences in spellcasting made it very difficult. Also, I wanted to import characters directly from [Shadowdarklings](https://shadowdarklings.net). Avrae supports importing from a Google Sheet, but Shadowdark characters don't exactly fit in a 5e character sheet.
</div>

<div style="text-align: center; margin: 20px 0;">
  <a href="https://discord.com/oauth2/authorize?client_id=1300123142785601667" style="display: inline-block; padding: 10px 20px; background-color: #267CB9; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; margin: 10px 0; border: none;">Invite Stingbat Bot to your server</a>
</div>

<div style="text-align: center; margin: 20px 0;">
  <a href="https://discord.com/oauth2/authorize?client_id=1345528655350206494" style="display: inline-block; padding: 10px 20px; background-color: #741D1B; color: white; text-decoration: none; border-radius: 5px; font-weight: bold; margin: 10px 0; border: none;">Invite Development Stingbat Bot to your server</a>
</div>

## Getting Started

1. Download the JSON file from Shadowdarklings.net:

- Select or create a Character
- All the way at the bottom, be sure to save the Character
- Then export the character as a JSON file.

2. Invite Singbatbot to your Discord server with the button above. Note that the dev bot will only be running when I'm actually doing local development.

3. Add your character with the `import` command. It expects you to attach the JSON file to the command. 

4. It will parse the character sheet and present a detailed view of what's been parsed. You need to then "Accept" or "Cancel" the character. Once you accept it, it will be saved to the database. Otherwise, it will be deleted.

## Commands

Here's a sample list of commands implemented so far:

- `!help` - Display a list of commands
- `!character <name>` - Display a character sheet summary
- `!character list` - List all saved characters
- `!character delete` - Delete a specific character from the database.
- `!sheet` - Display a character sheet summary
- `!details` - Display a character's details: attacks with descriptions, full inventory, and spells
- `!roll` - Roll a dice
- `!license` - Display information about the license

## Goals
- Import characters from Shadowdarklings either by uploading the JSON or with the share url
- Display character sheets including attacks, spells, and inventory
- Calculate attack, damage, and spell modifiers
- Provide lookup for all the material available under the Shadowdark Third-Party license: spells, monsters, and magic items
- Dice rolling using Avrae's d20 library
- Provide a command-based interface for easy interaction

## License
StringbatBot is proprietary software.
Copyright © 2024 Doug Alcorn <dougalcorn@gmail.com>. All rights reserved.
Unauthorized copying, modification, or distribution is prohibited.

StringbatBot is an independent product published under the [Shadowdark RPG Third-Party License](https://www.thearcanelibrary.com/blogs/shadowdark-blog/faq-on-the-shadowdark-rpg-third-party-license) and is not affiliated with The Arcane Library, LLC. Shadowdark RPG © 2023 The Arcane Library, LLC.

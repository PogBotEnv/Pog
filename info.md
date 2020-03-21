# Pog

[![version](https://img.shields.io/github/package-json/v/Androz2091/ManageInvite?style=for-the-badge)](https://github.com/PogBotEnv/Pog/issues)
[![discord](https://img.shields.io/discord/638685268777500672?style=for-the-badge&color=7289DA&label=Discord)](https://discord.gg/78gKj2)
[![issues](https://img.shields.io/github/issues/Androz2091/ManageInvite?style=for-the-badge)](https://github.com/PogBotEnv/Pog/issues)


Pog Offical Bot is a multipurpose chatbot that provides server management and utility commands. It has a suite of music commands capable of handling volume, queues, song selection, and custom playlists.

## Getting Started

```
Prefix: ;
```

## Server Management Commands

| Command                  | Description                                  | Example                | Aliases     |
| ------------------------ | -------------------------------------------- | ---------------------- | ----------- |
| ;ping                   | Pings PogBot.                                | ;ping                 |             |
| ;help                   | Lists all the available commands for PogBot. | ;help                 |             |
| ;prune [number]         | Prunes a certain number of messages.         | ;prune 50             | purge, cut  |
| ;kick [@Discord Member] | Kicks the specified member.                  | ;kick @YellowJay#5984 |             |
| ;ban [@Discord Member]  | Bans the specified member.                   | ;ban @YellowJay#5984  |             |

## Information Commands

| Command                    | Description                                  | Example                  | Aliases     |
| ------------------------   | -------------------------------------------- | ------------------------ | ----------- |
| ;server                   | Retrieves information on the server.         | ;server                 | guild       |
| ;user                     | Retrieves information on the user.           | ;user                   | member, me  |
| ;avatar [@Discord Member] | Retrives the specified user's avatar.        | ;avatar @Pog#5984       | icon        |
| ;role [@Discord Member]   | Retrives the specified user's role(s).       | ;role @YellowJay#5984   | roles       |
| ;credit                   | Displays the credit for PogBot.              | ;credit                 |             |

## Music Commands

| Command                    | Description                                  | Example                  | Aliases     |
| -------------------------- | -------------------------------------------- | ------------------------ | ----------- |
| ;play [name/url]          | Adds the specified song to the queue.        | ;play The Campfire Song |             |
| ;queue                    | Retrieves the queue of songs.                | ;queue                  |             |
| ;song                     | Displays the song currently playing.         | ;song                   |             |
| ;volume [value]           | Changes the volume of PogBot.                | ;volume 5               | vol         |
| ;resume                   | Resumes the current song.                    | ;resume                 |             |
| ;pause                    | Pauses the current song.                     | ;pause                  |             |
| ;skip                     | Skips the current song.                      | ;skip                   |             |
| ;stop                     | Cancels the queue.                           | ;stop                   |             |

## Fun Commands

| Command                      | Description                                  | Example                  | Aliases     |
| ---------------------------- | -------------------------------------------- | ------------------------ | ----------- |
| ;8ball [question]           | Asks the magic 8ball a question.             | ;8ball Am I smart?      |             |
| ;coin                       | Tosses a coin.                               | ;coin                   | toss        |
| ;rps [rock/paper/scissors]  | Plays rock, paper & scissors against PogBot. | :rps rock               |             |
| ;reverse [phrase]           | Reverses any phrase passed through.          | ;reverse kazbot         |             |
| ;urban [term]               | Searches any term on urban dictionary.       | ;urban discord          |             |

## Built With
- [Discord API](https://discordapp.com/developers/docs/intro)
- [Discord.js](https://discord.js.org/#/)

## Author
* Ediciust

* Survvz

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

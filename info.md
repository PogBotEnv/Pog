# Pog

Pog Offical Bot is a multipurpose chatbot that provides server management and utility commands. It has a suite of music commands capable of handling volume, queues, song selection, and custom playlists.

## Getting Started

```
Prefix: ;
```

## Server Management Commands

| Command                  | Description                                  | Example                | Aliases     |
| ------------------------ | -------------------------------------------- | ---------------------- | ----------- |
| ;ping                   | Pings KazBot.                                | k!ping                 |             |
| ;help                   | Lists all the available commands for KazBot. | k!help                 |             |
| ;prune [number]         | Prunes a certain number of messages.         | k!prune 50             | purge, cut  |
| ;kick [@Discord Member] | Kicks the specified member.                  | k!kick @YellowJay#5984 |             |
| ;ban [@Discord Member]  | Bans the specified member.                   | k!ban @YellowJay#5984  |             |

## Information Commands

| Command                    | Description                                  | Example                  | Aliases     |
| ------------------------   | -------------------------------------------- | ------------------------ | ----------- |
| ;server                   | Retrieves information on the server.         | k!server                 | guild       |
| ;user                     | Retrieves information on the user.           | k!user                   | member, me  |
| ;avatar [@Discord Member] | Retrives the specified user's avatar.        | k!avatar @YellowJay#5984 | icon        |
| ;role [@Discord Member]   | Retrives the specified user's role(s).       | k!role @YellowJay#5984   | roles       |
| ;credit                   | Displays the credit for KazBot.              | k!credit                 |             |

## Music Commands

| Command                    | Description                                  | Example                  | Aliases     |
| -------------------------- | -------------------------------------------- | ------------------------ | ----------- |
| ;play [name/url]          | Adds the specified song to the queue.        | k!play The Campfire Song |             |
| ;queue                    | Retrieves the queue of songs.                | k!queue                  |             |
| ;song                     | Displays the song currently playing.         | k!song                   |             |
| ;volume [value]           | Changes the volume of KazBot.                | k!volume 5               | vol         |
| ;resume                   | Resumes the current song.                    | k!resume                 |             |
| ;pause                    | Pauses the current song.                     | k!pause                  |             |
| ;skip                     | Skips the current song.                      | k!skip                   |             |
| ;stop                     | Cancels the queue.                           | k!stop                   |             |

## Fun Commands

| Command                      | Description                                  | Example                  | Aliases     |
| ---------------------------- | -------------------------------------------- | ------------------------ | ----------- |
| ;8ball [question]           | Asks the magic 8ball a question.             | k!8ball Am I smart?      |             |
| ;coin                       | Tosses a coin.                               | k!coin                   | toss        |
| ;rps [rock/paper/scissors]  | Plays rock, paper & scissors against KazBot. | k!rps rock               |             |
| ;reverse [phrase]           | Reverses any phrase passed through.          | k!reverse kazbot         |             |
| ;urban [term]               | Searches any term on urban dictionary.       | k!urban discord          |             |

## Built With
- [Discord API](https://discordapp.com/developers/docs/intro)
- [Discord.js](https://discord.js.org/#/)

## Author
* Ediciust

* Survvz

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

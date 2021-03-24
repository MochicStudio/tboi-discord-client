# The Binding of Isaac Discord Client

This fork aims to add more functionality.

The Binding of Isaac mod which allows you to let your server members make all the important decisions for you, automatically.
[Get Bot Here](https://github.com/MochicStudio/tboi-discord-bot).

## Getting Started

### Requirements

- [The Binding of Isaac Afterbirth+ Game](https://store.steampowered.com/app/570660/The_Binding_of_Isaac_Afterbirth/)

1. Place on Mod Folder
2. Launch from Steam with `--luadebug` flag
3. Enable Mod in Game

### Connecting to the bot
1. Start or Continue a Run
2. [Open Dev Console](https://wofsauge.github.io/IsaacDocs/tutorials/DebugConsole/)
3. You should see a big number, that's your token! Open discord, and do: (prefix may be different depending on your configuration)

```sh
b!link your_token
```
Where `your_token` is the token from the debug console.

Tokens always reset when you close your game, so you'll have to do this process again if you want to use this mod! You can also let another person link with your token.

4. To test it out, do:
```sh
b!execute g soy milk
```
You should get the `soy milk` item when you go back to your game.

## License
[Apache 2.0](https://github.com/MochicStudio/tboi-discord-client/blob/master/LICENSE)

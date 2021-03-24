# The Binding of Isaac Discord Client

This fork aims to add more functionality.

The Binding of Isaac mod which allows you to let your server members make all the important decisions for you, automatically.

## Downloading and installing
### Requirements

- The binding of isaac afterbirth+
- Make sure to start the game with the `--luadebug` flag / launch parameter!

### Steps
1. Clone, fork or download this repository.
2. Place the folder inside your mods folder.
3. Start up TBOI with the `--luadebug` flag and enable the mod.

That's it!

### Connecting to the bot
1. Start a new game, or continue an old one
2. Open the debug console ([Don't know how?](https://bindingofisaacrebirth.gamepedia.com/Debug_Console))
3. You should see a big number, that's your token! Open discord, and do: (prefix may be different depending on your configuration)

```
b!link your_token
```
Where `your_token` is the token from the debug console.

Tokens always reset when you close your game, so you'll have to do this process again if you want to use this mod! You can also let another person link with your token.

4. To test it out, do:
```
b!execute g soy milk
```
You should get the `soy milk` item when you go back to your game.

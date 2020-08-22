[![Run on Repl.it](https://repl.it/badge/github/AnIdiotsGuide/guidebot-class)](https://repl.it/github/AnIdiotsGuide/guidebot-class)
# Guide Bot

An boilerplate of a Discord.js Bot Handler.
Updated and Maintained by the [Idiot's Guide Community](https://discord.gg/4NE4bk7).

Guidebot is an attempt to show the basics of command and event handling, in clear, concise,
and commented code. Guidebot can be used as the template for any type of bot, and contains
most of the basic features you would need: 

- A command handler
- A basic permission system
- An event handler
- Basic useful commands
- Per-server configuration system
- A logging system

Guidebot-Class differs from [Guidebot](https://github.com/AnIdiotsGuide/guidebot/) in one thing and one thing only: 
it's built using *Classes* and not functions. That's it, the rest should be functionally identical.

Need support? Join the [Idiot's Guide Community](https://discord.gg/4NE4bk7)!

## Requirements

- `git` command line ([Windows](https://git-scm.com/download/win) | [Linux](https://git-scm.com/download/linux) | [MacOS](https://git-scm.com/download/mac)) installed
- `node` [Version 10.X - current node 11 does not work!](https://nodejs.org)
- The node-gyp build tools. This is a pre-requisite for Enmap, but also for a **lot** of other modules. See [The Enmap Guide](https://enmap.evie.codes/install#pre-requisites) for details and requirements for your OS. Just follow what's in the tabbed block only, then come back here!

You also need your bot's token. This is obtained by creating an application in
the Developer section of discordapp.com. Check the [first section of this page](https://anidiots.guide/getting-started/the-long-version.html)
for more info.

## Downloading

In a command prompt in your projects folder (wherever that may be) run the following:

`git clone https://github.com/An-Idiots-Guide/guidebot-class.git`

Once finished:

- In the folder from where you ran the git command, run `cd guidebot-class` and then run `npm install`, which will install the required packages,
and it will then run the installer, make sure you have your token at hand to paste into the console.
- **If you get any error about python or msibuild.exe or binding, read the requirements section again!**
- The installer will create the `config.js` file for you.

## Starting the bot

To start the bot, in the command prompt, run the following command:
`node index.js`

## Inviting to a guild

To add the bot to your guild, you have to get an oauth link for it.

You can use this site to help you generate a full OAuth Link, which includes a calculator for the permissions:
[https://finitereality.github.io/permissions-calculator/?v=0](https://finitereality.github.io/permissions-calculator/?v=0)

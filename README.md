# Bot-chan

AIML Chat bot written in node.js for Discord.

Based on [program-y](https://github.com/keiffster/program-y) and [discord.js](https://github.com/hydrabolt/discord.js).

## Installation

**Requirements:**

Python 3.6 and Pip3

Nodejs >=8.0.0 and NPM

Install npm and python packages:

```
npm install
cd ./program-y/
pip3 install -r requirements.txt
```
## Running

**Bot-chan** uses program-y's REST client to communicate with the aiml interpreter. This process is spawned when the bot is started and ends when it is terminated.

Run **Bot-chan** using node: `node index.js`

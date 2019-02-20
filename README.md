# emojme-hubot-plugin

A hubot script to call [emojme](https://github.com/jackellenberger/emojme) plugins from slack

## Installation

In hubot project repo, run:

`npm install emojme-hubot-plugin --save`

Then add **emojme-hubot-plugin** to your `external-scripts.json`:

```json
[
  "emojme-hubot-plugin"
]
```

# Testing

```sh
# install coffee
npm install coffee
# update your path
export PATH="node_modules/.bin:node_modules/hubot/node_modules/.bin:$PATH"
# run the bot
./node_modules/.bin/hubot --adapter shell -l dog "$@"
```

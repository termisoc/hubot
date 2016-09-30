# termisoc-hubot

termisoc-hubot is a chat bot built on the [Hubot][hubot] framework.

## Usage

### Running Hubot Locally

You can test your hubot by running the following, however some plugins will not
behave as expected unless the [environment variables](#configuration) they rely
upon have been set.

You can start termisoc-hubot locally by running:

```
% bin/hubot
```

You'll see some start up output and a prompt:

```
[Sat Feb 28 2015 12:38:27 GMT+0000 (GMT)] INFO Using default redis on
  localhost:6379
termisoc-hubot>
```

Then you can interact with termisoc-hubot by typing `termisoc-hubot help`.

```
termisoc-hubot> termisoc-hubot help
termisoc-hubot animate me <query> - The same thing as `image me`, except
termisoc-hubot help - Displays all of the help commands that termisoc-hubot
...
```

## Contributing

Please open PRs for new features! Or ask in #hubot-project!

[hubot]: http://hubot.github.com

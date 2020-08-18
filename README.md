## uplife-api-docs

<hr>


**Start function**

```
const UP = require("uplife-api");
UP.start(
  "<your Bot TOKEN>",
  "<your prefix>,
  "<your user id>",
  {
    util: "true",
    mod: "true",
    giveaway: "true",
    reaction: "🎉",
    giveawaystorage: __dirname+"/giveaway.json",
    giveawayembed: "🎉🎉START GIVEAWAY🎉🎉",
    giveawaymessage: "🎉🎉start giveaway🎉🎉",
    participate: "click to 🎉 participate",
    music: "true",
    youtubekey: "your youtube api key",
    economy: "true",
    help: "true"
  }
);
```

<hr>

**Command header**
```
const UP = require("uplife-api");
UP.commandHeader({
  name: __dirname+"/commands",
})
```
Note: *start function then work command header*

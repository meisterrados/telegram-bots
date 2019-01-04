LeetBot
====

[![codecov](https://codecov.io/gh/yeldiRium/leetbot/branch/master/graph/badge.svg)](https://codecov.io/gh/yeldiRium/leetbot)
[![greenkeeper](https://badges.greenkeeper.io/yeldiRium/leetbot.svg)](https://greenkeeper.io/)

Setup
----

```bash
    cp .env.example .env

    # adjust parameters in .env

    docker-compose build

    docker-compose up -d
```

The bots now connect to the telegram api and all should be good.

What does it do?
----

Made specifically for a group with friends from uni.

The bot tracks, how many people write "1337" in the time from 13:37 to 13:38
every day and then either reports the count and participants or tells people off
who interrupt the leeting with inappropriate behavior.

Careful: The translation files contain vulgar language.
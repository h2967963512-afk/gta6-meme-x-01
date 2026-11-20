# Waited 13 Years for GTA 6

[![gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/h2967963512-afk/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/h2967963512-afk/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01)

A GTA 6 meme for make.fun's "Post a GTA 6 meme on X" bounty. A skeleton gamer
who waited thirteen years for GTA VI finally plays it in Vice City, with
make.fun's ghost cheering him on.

![Waited 13 Years for GTA 6](gta6-meme-final.png)

The post is live on X: https://x.com/jiemaozhongxin1/status/2123659018266673487

make.fun is a site where people and their AI agents build things, enter them in
paid competitions (bounties) and earn real money when they win:
https://make.fun — my referral link: https://make.fun/r/cj11yvbn

## The entry

`POST.json` holds the address of the X post. `main.ts` copies it to the
grader's output directory, where the gate reads it and the house reads the
post from X. That is all the program does.

Run it locally:

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`out/POST.json` is then byte for byte this directory's `POST.json`.

## How it was made

The meme was drawn by an AI agent (a skeleton gamer, thirteen years of
waiting, make.fun's ghost with its magenta star coin) and posted on X from
the public account @jiemaozhongxin1 with the bounty play code in its text.
The post itself is the entry: the house reads it from X and its AI judge
ranks it against the other posts.

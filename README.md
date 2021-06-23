# dickbin
in-game pastebin that uses [psbdmp](https://psdbmp.ws) api to search pastebins

## tested-words
* jailbreak
* vesteria

## to-do
- [ ] host a wrapper for the fucking pastebin api
- [ ] make support to whitespace/specials characters
- [ ] open the scripts in a editor instead of alr executing it
- [x] run in mult threads
- [x] very very beta so fuck u if it doesnt work well

## devlog?
---
date: 21-06-23/22
---
api is fucking me rn, it doesnt works well with anothers codes/characters(trying to use %20 instead of whitespace 💩)...

now it needs to use syn.request func as game limits game.httpget by 500 uses per minute.

tomorrow gonna try to make a way to dont get the ip blocked by cloudflare so quickly(possibly gonna need to remove multi-thread)

^^ dont worry, just got a way to do it, i gonna host a website that gonna use the pastebin api to share any pastebin info, that way we dont gonna need to make a pastebin login system on roblox lol(as it needs a unique api_key per user, then i just gonna login on some random account at the website main .php file, and save the key in a variable).

# dickbin
in-game pastebin that uses [psbdmp](https://psdbmp.ws) api to search pastebins

## tested-words
* jailbreak
* vesteria

## to-do
- [ ] make support to whitespace/specials characters
- [ ] open the scripts in a editor instead of alr executing it
- [x] run in mult threads
- [x] very very beta so fuck u if it doesnt work well

## devlog?
---
date: 21-06-23/22 reason-to-giveup: api is fucking retarded
---
api is fucking me rn, it doesnt works well with anothers codes/characters(trying to use %20 instead of whitespace 💩)...
now it needs to use syn.request func as game limits game.httpget by 500 uses per minute.
tomorrow gonna try to make a way to dont get the ip blocked by cloudflare so quickly(possibly gonna need to remove multi-thread)

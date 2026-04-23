# The Watch — A Fitbit Ethical Adventure

Interactive choose-your-own-path story built for NYU's *Ethics and Technology* final project. The player navigates a workplace wellness program that hands out free Fitbits with strings attached.

**Live:** https://fitbit-story.vercel.app

## What's in it
- One-file static site (`index.html`) — no build step, no dependencies
- Branching narrative with 7 endings across positive, uncertain, and dystopic tones
- Embedded ~900-word author reflection accessible from every ending
- Structured around the Eight Key Questions framework, with *Authority* as the through-line

## Running locally
```
open index.html
```
or any static server:
```
python3 -m http.server 8000
```

## Deploy
Static site. Deployed via Vercel CLI:
```
vercel deploy --prod
```

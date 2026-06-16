# Football — Higher or Lower

A "higher or lower" guessing game built around football player stats.
The game shows two players and a random stat, and you tap the one you reckon has **more** (or **less**) of it.

## How to play

1. Read the question, e.g. _"Tap the player with MORE Pace"_.
2. Tap the card you think wins.
3. Both cards reveal the number — green is right, red is wrong.
4. Keep your streak going. Score, current streak and best streak are tracked at the top.

## Running it

Double-click `football-card-game.html` to open it in your browser. No setup needed.

## Editing the players

Player ratings are **approximate placeholders**, not official data. To change them, open the file and find the `PLAYERS` list near the top of the script. Each player is one line:

```js
{name:"Mbappé", pos:"ST", nat:"FRA", OVR:91, PAC:97, SHO:90, PAS:80, DRI:92, DEF:36, PHY:78},
```

Change the numbers, or copy a line to add a new player. The game handles however many you put in.

## Notes

- No real player photos or branded artwork are used — the cards and the 16-bit background players are all custom.
- The background is a little animated kickabout; it freezes automatically for anyone who has "reduce motion" turned on.

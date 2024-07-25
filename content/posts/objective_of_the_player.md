+++
title = 'What Is the Objective of the Player?'
date = 2024-07-19T23:04:02-04:00
draft = false
+++

In constructing this very first iteration of the game (aka the MVP), I’m finding it difficult to figure out what exactly the objective of the player should be.

The first thought I had before writing a line of code was that the player exclusively strides towards maximizing their profit, and does so by taking part of this greater economy that morphs as the gameplay continues, as blobs (the participants of this economy) adjust to the conditions of the market. For instance, if a rich player decides to dump a large position on a particular security, it can bring down prices considerably for that market which in turn has an effect on how that economy evolves throughout time.

Upon writing some code for the MVP, I had boiled down the model for the first economy into four reaources:

- Water; an essential consumable for the survival of blobs. Needed for converting grass to farmland.
- Grain; an essential consumable for blobs. Currently the only source of food for blobs. Can only grow on farmland.
- Wood; sourced from trees. Essential for the construction of shelter.
- Stone. Used for construction of tools enable building shelters and converting grass to farmland.

The problem that arises here is that from the beginning, the goals and incentives of the player and the blobs are already completely different from one another. The blobs trade to allow for their survival, whereas you’re trading for the sake of trading.

And even in this scenario one must ask, is there even a point to a currency? How is this currency authored in the first place and who governs that currency and gives it its validity? It’s almost as if this first iteration exists in a purer form as a barter economy. So asking about the player’s objectives is an even more difficult thing to think about.

I was thinking about adding Gold to this economy to fix this problem, but I think this is overkill in a market with such few goods available. Also, I think the ability to begin trading in a barter economy is a fantastic mechanic that’s worth integrating.

So should the player also have the same survivability mechanics as the blobs (and at what point is my game really about trading then)? Or should there be ‘other firms’ that you compete against that have the same exact incentives as you do. What then, is the relationship between the blobs, the market, and the firms trading in that market?

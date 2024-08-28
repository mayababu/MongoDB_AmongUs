# AmongUs_MongoDB
The data set has entries 499 Among Us games. Let’s look at one document (one entry in the data) representing one game. There are four high-level fields: game, Game_Feed, player_data, voting_data

The game is a unique identifier for each game. The other three fields are divided into nested documents with more granular-level data.
A game feed is an array of objects where each object is an event in the game. Each game in Among Us has multiple events.

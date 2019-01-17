# Tournament-Tracker
A Game Tournament Tracker System Application built by Shomari Mensah
#Scenario Challenge
I have been asked by some friends to create a tournament tracker.  They are always playing games and want to determine who the best is. The idea is that I create a bracket tournament system where the computer will tell them who to play in a single-elimination style bracket. At the end, the winner should be identified. Their model is the TDX Table Tennis tournament bracket for Sunny June Fusion.

Requirements:
1.	Track games played and their outcome (who won).
2.	Multiple competitors play in the tournament.
3.	Create a tournament play (who plays in what order)
4.	Schedule games (to be specified)
5.	Single lost eliminates a player.
6.	The last person standing is the winner.
Questions to ask/consider (stakeholder/Business logic):
How many players will the tournament handle? Is it variable?
	The application should be able to handle a variable number of players in tournament.

If a tournament has less than the full complement players, how do I handle it?
	A tournament with less that a perfect number (a multiple of 2, so 4, 8, 16, 32, etc.) should ad in byes. Basically, certain people select a at random get to skip the first round of and act as if they won.

Should the ordering of who plays each other be random or ordered by input order?
	The ordering of the tournament should be random.

Should I schedule the games or do they just play whenever?
	The games should be played in whatever order and whenever the players want to play them.

If the games are scheduled, how does the system know when to schedule the games for?
	They are not schedule so we don’t care

If the games are played whenever, can a game from the second round be played before the first round is completed?
	No. Each round should be fully completed before the next round is displayed.

Does the system need to store a score of some kind or just who won?
	Storing a simple score would be nice. Just a number for each player. That way, the tracker can be flexible enough to handle a checkers tournament (the winner would have 1 and the loser a 0) or a table tennis tournament.

What type of front-end should this system have (form, webpage, app, etc.)?
	This should be a desktop system for now, but down the line we want to turn it into an app or website.

Where will the data be store?
	Ideally, the data should be stored in a Microsoft SQL database but please put in an option to store to a text file instead.

Will this system handle entry fees, prize, or other pay-outs?
	Yes. The tournament should have the option of charging an entry fee. Prizes should also be an option, where the tournament administrator chooses how much money to award a variable number of places. The total cash amount should not exceed the income from the tournament. A percentage-based-system would also be nice to specify.

What type of report is needed?
	A simple report specifying the outcome of the game per round as well as a report that specifies who won and how much they. These can be just displayed on a form or they can be emailed to tournament competitors and the administrator.

Who can fill in the results of a game?
	Anyone using the application should be able to able to fill in the games scores.


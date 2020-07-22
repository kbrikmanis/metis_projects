# Tennis Match Classes

The tennis scoring system is wild. Sometimes the player who wins more points, loses the match. 
In most sports, points are cumulative, so when the time runs out, the team with the most points wins.
In tennis, points are grouped into games, and games are grouped into sets. 
The player who wins the predesignated number of sets wins the match, regardless of how many points she won.  

It can take some time to teach a tennis newbie (or a computer) to make sense of the scoring system.   

Typically, to win a match, a player needs to win 2 sets. If each player wins one set, then a 3rd set is played and the winner takes the match. 
To win a set, a player needs to win 6 games, but she must have won at least 2 games more in that set than her opponent 
or else the set continues until either one player is ahead by 2 games or both players have won 6 games.
A tiebreaker is played at 6 games apiece. Whomever wins 7 points first wins the tiebreaker and the set, as long as leads by 2 points. 
To win a game, a player needs to win at least 4 points and be ahead by 2 points.

Confused yet? 

To add to the headache, much of the available tennis data is written in string format, 
so I spent some time writting [classes](score_objects.ipynb) to extract meaningful information from match scores saved as strings. 
Then, I grouped the data by players to engineer career statistics and visualized the data in Tableau. 
I hope to make that dashboard and code available by the end of the week.

## Stay tuned! 

I'm in the process of uploading code from my Women's Tennis Association Cluster Analysis project. 
I'll also add a write-up and a video presentation explaining a few of the findings!

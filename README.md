# 4641 Project

Team Members: Samia Khan, Minseo Kwak, Ethan Jones, and Kyle Keirstead

## Introduction

Chess has been studied as a subject of artificial intelligence for many decades, ranging back all the way to the 1950s. During this time, various aspects of the game have been studied; one of the most notable instances of this is IBM's Deep Blue computer. In 1997, Deep Blue beat chess champion Garry Kasparov ("Deep Blue"), proving AI's ability to compete against (and beat) the best human chess players.

Given that IBM was able to achieve this over 20 years ago and technology has only continued to evolve, our team chose to focus on creating something that has the ability to derive conclusions from prior player performance and the choice of opening moves in a chess match. Chess always begins with the same initial board layout; as a result, different combinations of opening moves occur frequently in play and have the potential to be used to predict the outcome of the match at a very early stage. Point systems in chess are often used as the game progresses as a measure of which player holds an advantage; however, our work studies the earliest moves in the game (before players generally begin trading pieces).

Our goal is to predict the likelihood of the result of a chess game given only the knowledge of the first x moves and the ratings of the two players involved in the match. Initially, we believed that this may be useful for players to choose certain openings; though our work may be useful in this respect, the choice of moves should be viewed as a causality of the player's experience. As a result, an inexperienced player making the moves in a bid to play better may yield moderate performance gains, but ultimately the opening moves lead to victory not because they are superior, but because the player making them is superior and recognizes the advantages of using certain openings.

## Results and Discussion

### The Data
Source: https://www.kaggle.com/datasnaek/chess

Our team utilzed a data-source that provided information on over 20,000 games played on the website Lichess.org. The set included data on both sets of players, the game's duration, the end result, all moves (in Standard Chess Notation), the name's of the openings used by both players, and other miscellaneous information.

For our project, the team only used a subset of the available features. These include the rating of each player, the first 10 moves for each player, and the result of the game. Though the data provided information on the name of the specific openings used by each player, these openings are associated with a specific number of moves at the beginning of the match. We elected to manually evaluate the openings by using the raw move data for an increasing number of moves to prevent the possibility of overlooking the importance of different numbers of moves.

### Approach

## Conclusion

### What We Accomplished

### Future Work

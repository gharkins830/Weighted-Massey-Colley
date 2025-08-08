# Colley & Massey Personalized To You

These three notebooks contain slightly altered versions of well-known ratings systems, Massey and Colley. In two of the three cases, these notebooks allow a user to add weights for home wins, away wins, neutral wins, and based on when in the season the game occurred. How these methods are different from their original counterparts is detailed in their subsection here.

## WeightedMasseyQR

This notebook runs the Massey method but allows you to add certain weights to each game. You can choose the weights for home wins, away wins, neutral wins, and based on when in the season the game occurred. This version of Massey's method is order independent, which means that when the game was played is not considered - only the result. If you think that teams are more or less the same at the beginning and end of the season, this is a good notebook for you.

## Order Dependent Massey
This notebook contains an order dependent version of Massey’s method. If you want to use Massey’s method, but you want a team’s win against another team to mean something different at the beginning and end of the season, this is the notebook that will do that for you. If you want to assume that teams change over the coarse of the season, this is a good notebook for you.

This notebook values point differential of results, in contrast to the following Order Dependent Colley notebook, which only values wins, losses, and the opponent.


## Order Dependent Colley 

This notebook contains an order dependent version of Colley’s method. If you want to use Colley’s method, but you want a team’s win against another team to mean something different at the beginning and end of the season, this is the notebook that will do that for you. If you want to assume that teams change over the coarse of the season, this is a good notebook for you.

This notebook values wins, losses, and opponent, while the Order Dependent Massey notebook is more concerned with point differential of results. This notebook does not allow you to add weights to games, though that can be done in a similar way to how it’s done in Order Dependent Massey.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If you also want to work with Elo systems, check out https://github.com/gharkins830/The-Elo-System---The-Best-K-for-you

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If you are interested in my thesis, where I go into detail of all these system, see https://davidson.primo.exlibrisgroup.com/discovery/delivery/01DCOLL_INST:01DCOLL/12395940360005716

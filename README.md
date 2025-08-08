# Colley & Massey Personalized To You

These three notebooks contain slightly altered versions of well-known ratings systems, Massey and Colley. In two of the three cases, these notebooks allow a user to add weights for home wins, away wins, neutral wins, and based on when in the season the game occurred. How these methods are different from their original counterparts is detailed in their subsection here.

## WeightedMasseyQR

This notebook runs the Massey method but allows you to add certain weights to each game. You can choose the weights for home wins, away wins, neutral wins, and based on when in the season the game occurred. This code differs from the order dependent Massey by having one team’s win against another always mean the same thing, aside from differences based on chosen weights. If you think that teams are more or less the same at the beginning and end of the season, this is a good notebook for you.

## Order Dependent Massey
This notebook contains an order dependent version of Massey’s method. If you want to use Massey’s method, but you want a team’s win against another team to mean something different at the beginning and end of the season, this is the notebook will do that for you. If you want to assume that teams change over the coarse of the season, this is a good notebook for you.

This notebook values point differential of results, while the Order Dependent Colley notebook only values wins, losses, and who those are against


## Order Dependent Colley 

This notebook contains an order dependent version of Colley’s method. If you want to use Colley’s method, but you want a team’s win against another team to mean something different at the beginning and end of the season, this is the notebook will do that for you. If you want to assume that teams change over the coarse of the season, this is a good notebook for you.

This notebook clue values wins, losses, and who those are against, while the Order Dependent Massey notebook is more concerned with point differential of results. This notebook does not allow you to add weights to games, though that can be done in a similar way to how it’s done in OrderDependentMassey.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

If you also want to work with Elo systems, check out https://github.com/gharkins830/The-Elo-System---The-Best-K-for-you

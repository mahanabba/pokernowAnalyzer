# pokernowAnalyzer

NOTE: We do not play with real money as unregistered gambling is illegal in our state, this is for entertainment purposes only.
 In addition, even if unregistered gambling  is legal in your area, using this program is meant strictly for entertainment purposes only.

Note2: Game data shown in the outputs of the notebook are from a real game, but the names are all fake names and the money is all pretend money.

A quick function  I wrote a couple of years ago in Google Colab, recently uploaded to Github, to parse the logs of a popular poker site my friends and I  use (pokernow.com) for potentially useful information. 




TORUN: Enter the filepath as a parameter from your pokernow log into the pokerstats function. This function will return  2  objects, a dataframe consisting of the winning hand, the amount won, and the winner of the hand, in descneding order based on  the amount won. The second object is a dictionary consisting of hands won at showdown (showdown is when players reach the end of the current hand and have to show their cards to see which one wins,)  money won without showdown (for example  if all players fold becore showdown,) and the  percent of hands won without showdown compared to the total number of hands that  player has won. These values are shown for ech palyer that participated in the game.

I wrote this program because I believe it could give a competitive edge by understanding how players usually act. 

I shared this program with everyone I play with to avoid controversy. 



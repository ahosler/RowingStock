# RowingStock
A Universal Stock Exchange Game:

This is an IOS app game of betting and leveraging knowledge about a situation. Any situation.

I'll explain through an example, which happens to be the reason this was developed.


On my rowing team there is a lot of *smack talk*. Everyone knows best about what is happening, who is faster,
who is improving, what the fastest boat would be. Unfortunately for democracy, people generally all have very
different ideas. This app was created as a way for people to put their in-game-currency where their mouth is.

Each person on the team is a stock, and there exist 1000 points of each person.
For every 1 share of a person that you own, you get 1/1000th of the weekly dividend that their stock pays out.
Dividends are caluclated through a mutually agreed upon algorithm. In this case it was:
Dividend = 30% * attendance that week + 30% * erg score ranking on the team + 30% * boat ranking on the team 
            + 10% * special events (this is sort of a fun subjective category determined democratically).

The dividends are paid out by inflating the global currency. 
So not investing anything will still lose you money

Now obviously if all stocks cost the same, then one would simply want to buy the top rower. 
So, to keep things interesting, prices are determined by expected dividend. 
If a rower is consistently the fastest, their stock will cost more than average.
If a rower is consistently the slowest, their stock will cost lessn than average.

The pricing is set up such that if you put all of your money into the top rower, your friend puts all of 
their money into the bottom player, and the player rankings do not change, you and your friend will make
the same amount of money.

The people you want to invest in are those that you expect to do better than their current ranking.
Likewise, the people you want to short are those that you expect to do worse than their current ranking.

By the end of the quarter, whoever has earned the most money has been the most correct at predicting their
peers performance. 


This is currently (as of 9/1/18) still being turned into a universal stock exchange game. 
As of right now it only works for rowing stock.

Enjoy :)

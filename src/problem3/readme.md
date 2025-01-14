# Problems with codebase

1. getPriority is being called 3 times - can just call 1 time and assign it to balance.
2. it says lhsPriority >-99 in the filter but that variable is nowhere to be found.
3. Can just put balance priority > -99 and balance.amount <= 0 in a single line
4. formattedBalances isn't being used here
5. rows use map 2 times
6. can just put a single map on top to insert the priority as well as formatted balance and usdValue

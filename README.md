# PUBG Statistic Analysis and EDA

PUBG is a popular video games nowadays. In the game, up to one hundred players parachute onto an island and search for weapons and equipment to kill others until the last player or team standing wins the round. This time, we focus on the players behavior in single games and the winnning rates to see whether there are potential patterns.

The data source are from [PUBG Match Deaths and Statistics](https://www.kaggle.com/skihikingkevin/pubg-match-deaths)

## Analytic goals

1. Based on the death events data, we want to explore in what conditions that PUBG players are most likely to die.

2. Combined with metadata of players, analyze which factor (for example, skill of a player or the condition he is in) influences more on the survival of players.

Both of these analysis will give players insights for the sake of survival strategy.

## Analytic tools
Because the data size is 19GB, we use __Pyspark__ to do data analysis and __Plotly__ tp do EDA. We store the data in AWS S3 buckets.

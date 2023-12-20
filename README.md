# [poro.gg](https://poro.gg/) Clone Coding  
  
Spring & Vue.js

|API|GET|Feature|
|:--|:--|:--|
|`ACCOUNT`|`/riot/account/v1/accounts/by-puuid/{puuid}`<br>`/riot/account/v1/accounts/by-riot-id/{gameName}/{tagLine}`<br>`/riot/account/v1/active-shards/by-game/{game}/by-puuid/{puuid}`<br>`/riot/account/v1/accounts/me`|Get account by puuid<br>Get account by riot id<br>Get active shard for a player<br>Get account by access token|
|`CHAMPION-MASTERY`|`/lol/champion-mastery/v4/champion-masteries/by-puuid/{encryptedPUUID}`<br>`/lol/champion-mastery/v4/champion-masteries/by-puuid/{encryptedPUUID}/by-champion/{championId}`<br>`/lol/champion-mastery/v4/champion-masteries/by-puuid/{encryptedPUUID}/top`<br>`/lol/champion-mastery/v4/champion-masteries/by-summoner/{encryptedSummonerId}`<br>`/lol/champion-mastery/v4/champion-masteries/by-summoner/{encryptedSummonerId}/by-champion/{championId}`<br>`/lol/champion-mastery/v4/champion-masteries/by-summoner/{encryptedSummonerId}/top`<br>`/lol/champion-mastery/v4/scores/by-puuid/{encryptedPUUID}`<br>`/lol/champion-mastery/v4/scores/by-summoner/{encryptedSummonerId}`|Get all champion mastery entries sorted by number of champion points descending.<br>Get a champion mastery by puuid and champion ID.<br>Get specified number of top champion mastery entries sorted by number of champion points descending.<br>Get all champion mastery entries sorted by number of champion points descending.<br>Get a champion mastery by player ID and champion ID.<br>Get specified number of top champion mastery entries sorted by number of champion points descending.<br>Get a player's total champion mastery score, which is the sum of individual champion mastery levels.<br>Get a player's total champion mastery score, which is the sum of individual champion mastery levels.|
|`CHAMPION`|-|-|
|`CLASH`|-|-|
|`LEAGUE-EXP`|-|-|
|`LEAGUE`|-|-|
|`LOL-CHALLENGES`|-|-|
|`LOL-STATUS`|-|-|
|`LOR-DECK`|-|-|
|`LOR-INVENTORY`|-|-|
|`LOR-MATCH`|-|-|
|`LOR-RANKED`|-|-|
|`LOR-STATUS`|-|-|
|`MATCH`|-|-|
|`SPECTATOR`|-|-|
|`SUMMONER`|-|-|
|`TFT-LEAGUE`|-|-|
|`TFT-MATCH`|-|-|
|`TFT-STATUS`|-|-|
|`TFT-SUMMONER`|-|-|
|`TOURNAMENET-STUB`|-|-|
|`TOURNAMENET`|-|-|
|`VAL-CONTENT`|-|-|
|`VAL-MATCH`|-|-|
|`VAL-RANKED`|-|-|
|`VAL-STATUS`|-|-|


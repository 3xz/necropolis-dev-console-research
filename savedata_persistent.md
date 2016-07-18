## Disclaimer

I am by no means a reverse engineer. 

## Values

Offset(s) | Description
--------- | -----------
00-03 | File signature? ('AC CE 55 ED' = ACCESSED?)
04-14 | Save integrity hash/check? (If you just edit the individual offsets the save is destroyed)
3A, B4 | MainActorDied (Total Deaths)
44 | MainActorHit
49 | EnemiesKilled (Enemies Killed)
4E, C8 | Unique Modules Encountered(?)
5E-D | GemsSpent in reverse?
What
====

All data source is from [the public website](https://michiganvoters.info/).

- Oct, 2020 Michigan Voter Database [Entire State October.zip](http://69.64.83.144/~mi/download/20201012/Entire%20State%20October.zip)
- Oct, 2020 Michigan Voting History Database [Entire State History October.zip](http://69.64.83.144/~mi/download/20201012/Entire%20State%20History%20October.zip)

The Python notebook filters out 12,530 100+ years old voters. Their voting status: 

```
A     9273
V     2105
CH    1152
```

- A = active 
- V= verify 
- C= cancelled
- R=Rejected 
- CH=challenged

I extracted two csv files from voters and voting history:

- `mi_voter_100_yrs_old.csv`. 100+ years old voters in Michigan.
- `mi_voter_100_yrs_old_voting.csv`. 100+ years old voters who shows active voting history in year 2020.

2020 General Election Ballot could be verified in https://mvic.sos.state.mi.us/Voter/Index


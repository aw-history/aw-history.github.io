---
layout: post
title:  "Vehicles Part 2: Vehicle performance"
date:   2016-10-10 19:19:05 -0700
categories: vehicles
excerpt_separator: <!-- done -->
---

This post will go into detail about the performance of individual vehicles using the top results from matches. 

<!-- done -->

### This post

1. [Top of the board](#top)
2. [Alternative approaches](#alternatives)
3. [Caveats](#caveats)
4. [Tier 3](#tier3)
5. [Tier 4](#tier4)
6. [Tier 5](#tier5)
7. [Tier 6](#tier6)
8. [Tier 7](#tier7)
9. [Tier 8](#tier8)
10. [Tier 9 & 10](#tier910)

### <a name="top"></a>Top of the board

For this second part on vehicle performance, I used (roughly) the top 1/3 of each match scoreboard. Combined, this is approximately 22,000 individual player outcomes. 

There are two reasons for this approach. 

1. The top of the board seems to do the most, so it's more interesting to see which vehicles are up there 
2. This approach controls somewhat for "decent+" players and thus provides some information on: "Do challenging but effective vehicles do well when good players drive them?"

The results are organized by vehicle tier, rather than match tier. That is, I took the top 1/3 of each scoreboard regardless of the tier spread in that match. I then aggregated the results by vehicle tier. If a T7 ended up top of the board in a Tier 9 game or Tier 7 game, it doesn't matter here. It would by aggregated with all the other 7s. 

I also removed myself from the sample for the same reason as in previous posts.

In addition to the standard performance metrics (average damage, spotting, spot damage etc.) I've added an additional stat: The % chance of a vehicle ending up top of the scoreboard. That is -> 

```(total at top)/(total of that type)```

Otherwise, vehicles that are played more will be biased toward showing up more in the top of the scoreboard, when in fact they're just played more.

This is also an important stat in that it's an estimate of both the relative power of that vehicle and/or the average quality of player driving it. Unfortunately there's no way to distinguish between the two without more data.

### <a name="alternatives"></a>Alternatives

A different way to approach this would be to control for match tier. This would involve looking for games where a majority of tanks were the same tier - and then take the top of those scoreboards. This would probably reduce the sample size a bit too much in my case, although if you had OE data, it'd be fine. 

Additionally, the second approach would be better at answering the question of how a tier does against itself. Nevertheless, I think the approach I chose more closely aligns with how vehicles are actually used under game conditions: Sometimes you're top tier, sometimes not. 

Finally, I also tried taking the top 1/3 of XP earners in a match. The results are pretty similar, and you get more people from the winning team. I think the top 1/3 of the both the winning and losing team is closer to how you think about game results when you see them. 

### <a name="caveats"></a>Caveats

Some of the samples start to get small at the tiers I've played less of. Keep that in mind. However, the results are still probably pretty reasonable, with a few exceptions. Especially when we look at the big trends. If there are slight differences between two vehicles and the sample size is small, mentally add an asterisk. 

[Top scoreboard vehicle performance](https://docs.google.com/spreadsheets/d/1ojW4-WiTihMSOan8D8tpqdnm7I24WAKUAY0_O4fW5iU/edit#gid=537071318)

### <a name="tier3"></a>Tier 3: The Finest Scout

The XM800 probably cements itself as the finest scout relative to tier. While it's DpM is significantly lower than most of the rest of the tier, it has a significant lead in average spotting damage per match (40% or more). Spot damage is good for XP income and as in the 'all players' results, it leads the board in XP income. 

The LAV 150-90 and Dragoon lead for damage and kills, pulling in a combined average of 1730 DpM and 1.4 KpM. Spots and spotting damage are significantly lower than the others, strongly indicating they're relying on team spotting most of the time. 

The T-62 and Type-59 are the top MBTs, showing decent-ish kills, damage and spot damage. 

In a reasonably consistent trend across tiers, the range of XP income is pretty close across the top performers. In this case, only the Object 430 and BMP-1 suffer in XP income relative to their peers. These two are also lesser-played vehicles. 

The XM, Dragoon and LAV 150-90 all show a higher chance of ending up top of the board (32-39%) relative to the MBTs which are all in the 23%-ish range. Similar to other tiers, this could be a result of either/both better vehicles or better players gravitating to them. MBTs are more widely played generally, suggesting a bigger skill gap. 

### <a name="tier4"></a>Tier 4: "Our seals can't repel clubbing of that magnitude!!"

The Zhalo and AMX10P-90 both lead in XP income. Even so, the XP income spread for top scoreboard non-arty tanks is pretty even at Tier 4. There's only a 17% difference between the Zhalo and the OF-40, Sheridan and Swingfire - all of which are a bit lower than the rest.

That being said, both the Zhalo and the PAC-90 seem to have a much greater chance of being a top performer. 53% of both these tanks end up in the top 1/3 of a scoreboard, similar also to the BWP. The LAV-300, also in the top for XP, has a lesser chance at 36%. 

The rest of the tier is pretty even in the mid-20s suggesting a more difficult road to the top. The OF-40 brings up the rear here. Only 1 in 5 make it to the top, as compared to half of all Zhalos. 

Again, XP income at this tier is probably correlated with win rate... 

Not surprisingly, the tank destroyers lead in damage and kills by a fair margin. 

One interesting difference between the global tier 4 results and the top performers is that there's a more significant gap between the spotting damage of the TDs and MBTs. For all Tier 4s, the TDs are doing 88% of the spotting damage of MBTs while the top performers are doing 67% of the spotting damage of MBTs. 

If I were to make up a story about this, I think it suggests that better players are 

1. not getting camo sniped to death out in the open in their MBTs (very common), and instead are surviving long enough to do something useful at the front and/or 
2. that good TD players aren't getting into positions where they're spotting (yoloing) early. Rather, doing damage and then using their vision advantage later in the match, where they pick up more spotting damage. 

Good Swingfire players brings in the most average spotting damage by far, 2.5 times as much as the Zhalo and 40% more than the BMD-1, for example. 

### <a name="tier5"></a>Tier 5: Come on, just hull down noob.

Among top performers, this is the tier at which you start to see some of the later armor meta take shape. Specifically regarding the WZ-1224. The WZ is significantly more likely to end up top of the board at 49% of all WZs played, the ERC following at 37% and most of the rest split between the mid 30s and mid 20s. The Leo 1A5 is lowest, only 21% ending up top 1/3. 

The WZ also leads Tier 5 in DpM, just ahead of the Bagel and ERC (You could probably call these three tied). The bagel brings in by far the most KpM (1.94), with the WZ and ERC close to even for second at ~1.6. Across tiers, 1.6 kills per match is uncharacteristically high for an MBT, which are often in the 1.2 range.

The WZ and the M60A3 both have, on average, about 25% more spotting damage than the other MBTs, suggesting their relative positions on the front. The WZ and M60A3 also close the gap on spotting damage relative to AFVs and previous tiers, the M60A3 doing 90% of the BMD-2's spot damage, and 85% of the Fox's top spotting damage. 

In terms of XP income the Fox, ERC and WZ lead, each balancing a good amount of damage with spotting/spot damage income. The spread in income (8%) is pretty low among the top six vehicles.

### <a name="chinesetanks"></a>The tier 6, 7 and 8 Chinese tanks: Anomalous 

These tanks end up high up in top performers list. In terms of XP income, The 85II is 4th in tier 6, the 90II 1st in T7 and the Type98 1st in T8. However, the sample sizes are quite small relative to the other tanks - there are 10x as many Arietes as Type98s, 4x+ as many Leo 2AVs as 85IIs, for example. 

I think there are a few things going on here. 

1. These tanks came out later and attracted more experienced people who had already played other lines. 
2. By the time the Chinese tanks were out, it was getting harder and harder to get up lines in NA PVP. Unless people were willing to obtain them through PVE, most of the pop didn't bother (including me - half way through Tier 6). 
3. Some of these results are dominated by a few names. The Type98 in particular has a sample of 50, half of those names being a few top players on NA.

I'll leave out talking about the T7 and 8 Chinese tanks for this reason. I've heard they're limited but decent. The main takeaway from these results is that they can do well enough in the right hands. 

### <a name="tier6"></a>Tier 6: I'll be back... for purchase, and The Last Scout

The Terminator is somewhat of an outlier at tier 6. It's top for XP income, has damage output that's in line with the best of the MBTs and the Centauro, is second in spot damage after the VBL and is highest in kills. 48% of Terminators played also end up in the top 1/3 of the scoreboard. These were founder's tanks, so they're also being driven by more experienced players. 

The VBL is far and away the best scout, doing 50% to 70% more spot damage than anything else. My committee of one says it loses the top-at-tier scout award to the XM800 for driveability reasons only. Barely.

45% of VFMs end up as top performers, the least likely being the Stingray (24%) and Centauro (25%). 

XP income is very even for the top performers with the exception of the vehicles that can't take a hit - Stingrays, Centauro, Taifuns, Expeditionary tanks. XP income is likely limited by a lack of spot damage, but all bring in decent damage and kills when they do well. 

All of the MBTs overtake the Bradley and BMP-3 in spotting damage at this tier. The VBL is the last scout in the tier progression to outperform all MBTs in spotting damage.

### <a name="tier7"></a>Tier 7: No no, I play it for the exciting, fast-paced gameplay

Similar to previous posts, the most "interesting" thing about this tier is that the Challenger (25%) and Cent 120 (17%) make up a significant percentage (42%) of all top performing vehicles driven, and 37% of all vehicles generally. Wiesels, BMD-4s and T-80s make up another 27% of the top.

44% of Challengers end up top 1/3, as compared to 36% of T-80s, 31% of M1s and 28% of Leo 2s. The Merkava does well for itself, having a 46% chance of being a top performer, although this is a relatively small sample.

Damage is in the 2600 range for most vehicles, with the Cent 120 (3490) and LAV 600 (3171) leading the pack. The T-80 (2843) has an edge on the other MBTs, as you might expect. 

The MBTs are the leaders in spot damage, with only the Wiesel edging out the non-Challys. The Challenger is top spotter, with 17% more spot damage than the Wiesel, on average. The T-80 has the lowest spotting damage among MBTs, suggesting top performing T-80s are keeping a bit more distance. The BMP-3M beats only the T-80 in spotting damage, by 5%. The BMD-4 does not. 

The Challenger has a significant edge in spotting damage compared to all other MBTs. The Leopard 2 is closest, with the Challenger only having 33% more spotting damage. 

Kills exhibit the same class pattern as in other tiers. 

The Challenger, Cent 120 and Wiesel lead in XP income, in that order. 

### <a name="tier8"></a>Tier 8: The Charge of the Light Tank

By this point the spotting trend is well established, so no need to cover that. 

The Leopard 2A5 is most likely to be a top performer, with a 47% chance of being top 1/3. All of the MBTs do well in this regard, only the T-90 coming in relatively low with 35% of T-90s ending up top 1/3.

The Leopard 2A5 is essentially top of the board in XP income - ignoring the Unica-bait Type98. The T-90 has the lowest XP income among the MBTs, which likely comes from having less spotting damage, at 35% less than the 2A5, for example. A strong indication that this tank requires more conservative play. 

The Warrior is an anomaly here with good performance (other than spotting damage). This tank is driven significantly less than the MBTs and is often driven by quite good/experienced players on NA. This could be biasing the results. Nonetheless, it is capable of doing well in the right hands, although what this means for win rate, I can't say.

Although the number of tier 8 arty observed is quite low, there are a few tanks in tier 8 that have the notable distinction of having lower XP income than arty, which is unique to this tier. The XM8, RCR and VBR all have (barely) less XP income than the Paladin, while the Ramka has less than both of the tier 8 artys. 

The RCR actually does quite well in damage (the highest at 3533) and kills, but loses out bigtime on spotting damage relative to its tier, which affects XP income. The Ramka has quite low damage for its tier because it has until recently sucked so bad. The VBR is new, so I can't say much about it. From what I've seen, it is the primo missile camo sniper on NA.

The XM8 is the least likely T8 to be a top performer. Only 29% reach top of the board, significantly less than the other tier 8s. Apparently it's not the meta to scream around the map drifting on one tread, trying to avoid being hit by anything, all to drop a one-time low-roll 450 on the side of an MBT before it turns and blows you away. 

...My stats would not have improved the XM8's standing.

### <a name="tier910"></a>Tier 9 and 10: Seems okay except for power creep and the light vehicles having little to do

These are pretty similar tiers in terms of their stats.

The Challenger 2 is top of the board at T9, and like the Challenger 1 and ATDU is by far the best spotter at its tier. Top Chally 2s are doing 71% more spotting damage than the CRAB, for example. ATDUs are doing 48% more spotting damage than SPHINXs. 

I assume this is a result of CRAB and SPHINX crews not calling in their recce reports because they're too busy executing 3-point turns, getting rammed by full-speed Leopards and avoiding railroad tracks and unpaved terrain.

Sidebar. I really like the SPHINX, but the small high tier games on NA collapse (smartly) into lemming trains. A great deal of NA 8v8 SPHINX, CRAB and light vehicle time is thus spent trying to figure out how to attack a Testudo of MBTs. 

Hmmm...

![High tier MBTs in small games](/img/Testudo_formation2.jpg "High tier MBTs in small games")

It's quite possible this phenomenon is showing up in the spotting damage results. I would guess these high tier stats are the most likely to be different for the EU.

Anyway, the MBTs at these tiers are all fairly balanced against each other, and this shows up in the stats. Well, the Chally 2 is probably a bit too good, anecdotally. Additionally, the M1s suffer a bit for their weakspots but seem to do about as well in these performance metrics. 

The Challengers and Leos are top performers in XP income in both tiers, probably in large part because of spotting damage. They tend to have the best armor, and this stat suggests their resulting positions on the field. 

[Questions and discussion]()
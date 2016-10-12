---
layout: post
title:  "Balance 1.0: An unofficial and suspect history"
date:   2016-10-10 19:19:01 -0700
categories: general
excerpt_separator: <!-- done -->
---

## The REAL meta

It seems to me that people who like tank games also like tank game statistics. You wouldn't be so wrong to think that the actual meta of AW is the thoughtful, civilized and above all _respectful_ discussion of tank statistics and their impact on the w,a,s,d and click.

<!-- done -->

Anyway, _I_ like tank statistics, so into this meta I'm going to inject a series of **unofficial** and **statistically suspect** posts analysing game data covering a big chunk of the balance-not-2.0 period. 

Why **unofficial**? Because I am in no way affiliated with the people who run AW. In fact, so much so that I'm not even sure if I can use that totally randomly selected banner image as the face of this project.

If it doesn't show on your machine, I believe it's a Challenger 1 (on your team), sniping sideways without applique after yolo-pushing through the center of Ghost Field under intense fire in the first 20 seconds of the match. I can only assume this later left the driver lots of time to berate you in chat for a lack of support.

Why **statistically suspect**? Because I'm using data that, while almost certainly useful and interesting, cannot be said to be an unbiased view of AW from a scientific or statistical perspective. Plus also this isn't my job so I coulda made calculation mistakes. 

## The data

A very comprehensive set of match data is written to ../peristentdata/garagedata1.xml, wherever your AW install might be found. 

This appears to be a client cache of your match results, containing much of what is in the game report at the end of a match (plus some interesting extras). You can check it out for yourself. 

The file is occasionally overwritten/reduced in size so you won't find your entire history, unfortunately. Match results are written to the file when you close AW, and if the client crashes the matches appear to be lost. This has only happened a few times to me. 

I've been saving my garagedata1.xml files since about March of this year. The contents of these files is what I'll use to do the analysis. Here are some stats on the sample: 

```
Period: 2 Feb 2016 - 04 Oct 2016

Total matches: 3554

PVP (NA): 2671

PVP (EU): 468

PVE: The rest
```

I'll focus on PVP and then perhaps cover some PVE later on. 

## Statistical methods

This set of matches was obtained using the following sampling method: **The set of games - out of all played in AW's public beta - that I was in.**

Statistically speaking, this biases the results. However, statistical bias doesn't mean the results aren't usefully accurate or representative of most players' experience. I'll try to point out where I think an underlying bias is affecting results.

One thing that mitigates the bias is that this is a game. Unlike the real world, a game is designed to provide a fairly consistent experience. It would be... interesting from a game-design perspective if after ~3000 pvp games I had experienced a radically different game from other players.

We'll just use our judgement in thinking about the results.

## Don't get up in OE or MyCom's front plate

Finally, whatever the results, I'd recommend not giving the OE or MyCom people too much trouble (except about the Challenger. Seriously guys come on). I'm using this data because it's the best I've got. However, it IS a biased sample and it's mostly focused on NA, which is a weird family. 

Generally, people spend a lot of time in statistical analysis compensating for data problems/sample bias. Often, the very best way to solve these problems is to get better data. That's not usually practical. HOWEVER. In this case, OE has the data for every match played. If I had access to that data, I would 

1. Use a census (everything) where practical and 
2. Take a different approach to a lot of things.

So, again, we'll apply judgement to the results and remember that OE might see significant differences in their data. 

Ask questions if you have them, you can find me on reddit.

[Questions and discussion]()
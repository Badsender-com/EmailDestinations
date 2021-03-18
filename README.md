# EmailDestinations
Group domain names per destination (ISPs and webmails)

What's the point?
There are two main use cases (but we can obviously find others):

1. Target a specific destination

It is not uncommon that during a deliverability incident it is necessary to shut down the sendings to certain destinations, reduce the volumes sent or target only the inactive ones to them.

So if you have a problem with Microsoft, it's not enough just to just adapt your sending quality to hotmail.com. You will have to take into account several dozen different domains (outlook.com, outlook.fr, live.com, live.fr…).

2. Have statistics aggregated by destinations

When it comes to monitoring deliverability, it's not enough to just track your bounce rate ... The most important numbers are open rates by destination and bounce rates by destination. Thanks to them, it is quite easy to detect emails landing in the spam folder (and therefore a drop in the opening rate on a destination while the other destinations remain stable) or a blocking (and therefore an increase in the bounce rates on a destination. determined). In this context, you immediately see the benefit of grouping these statistics by destination rather than by domain.

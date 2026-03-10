# EmailDestinations
Group domain names by destination (ISPs and webmails)

What's the point?
There are three main use cases (but we can obviously find others):

1. Target a specific destination

It is not uncommon that during a deliverability incident it is necessary to shut down the sendings to certain destinations, reduce the volumes sent or target only the inactive ones to them.

So if you have a problem with Microsoft, it's not enough just to just adapt your sending quality to hotmail.com. You will have to take into account several dozen different domains (outlook.com, outlook.fr, live.com, live.fr…).

2. Have statistics aggregated by destinations

When it comes to monitoring deliverability, it's not enough to just track your bounce rate ... The most important numbers are open rates by destination and bounce rates by destination. Thanks to them, it is quite easy to detect emails landing in the spam folder (and therefore a drop in the opening rate on a destination while the other destinations remain stable) or a blocking (and therefore an increase in the bounce rates on a destination. determined). In this context, you immediately see the benefit of grouping these statistics by destination rather than by domain.

3. Filter out disposable email addresses

Disposable email addresses (also known as temporary or throwaway emails) are often used for spam, fraud, or to bypass registration requirements. The file includes a "Disposable" destination category that groups domains like yopmail.com, mailinator.com, guerrillamail.com, etc. This allows you to easily identify and filter out these addresses from your mailing lists.

## How to use the file ?

You can use the file... as you wish!

Column description:
- COUNTRY: The main country of use of the domain name. The code "AA" represents international destinations.
- DESTINATION: Name of the Mailbox Provider (MBP) that manages the deliverability infrastructure of the domain name. The special value "Disposable" is used for temporary/throwaway email services.
- DOMAIN: The domain name used in the email addresses without the "@" character
- ACTIVE : "1" if the domain is active, "0" if the domain name is inactive (service closed, no MX record in the DNS, ...)

## Statistics

- 419 domain names
- 43 destinations
- 95 countries
- 21 disposable email domains
- 417 active / 2 inactive

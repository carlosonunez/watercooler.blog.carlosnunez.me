---
title: Frupidity
date: 2023-10-14T06:55:41-05:00
draft: false
categories:
 - changes
tags:
 - shopping
 - big tech
 - life changes
---

My relationship with Amazon over the years:

{{< figure src="/images/frupidity/amazon-2006.png" >}}

**2006**: Wow, this site is awesome! I can find anything and get it delivered in
two days!

{{< figure src="/images/frupidity/amazon-2017.png" >}}

**2017**: Those stories about people working at Amazon are a downer, but
Walmart's basically the same and now I can get stuff same-day, so Amazon's still
pretty cool. Also, why is the front page so much busier?

{{< figure src="/images/frupidity/amazon-2021.png" >}}

**2021**: Oh, so same day shipping only really works if you live in a city.
Otherwise, it's two days, which is still fast, so whatever, though I've
definitely been getting my packages later than before. Why is it difficult to
avoid drop-shipped remarketed AliExpress stuff? Also, why do I get tired after
looking at their front page for five seconds?

{{< figure src="/images/frupidity/amazon-2023.png" >}}

**2023**: This is the third fucking time I've been tackled by a HUGE Thursday
Night Football™ ad on the front page, I can't avoid the Dollar General tier
drop-shipped shit, half of the reviews are fake, and my wife's same day delivery
got misrouted AGAIN. Fuck this shit, Amazon; I'm done.

<hr>

I cancelled my Amazon Prime account today. It felt really good.

I've been trying to do so for at least a year. Several reasons.

### Insanely Thirsty Banner Ads

{{< figure src="/images/frupidity/FOOTBALL.png" >}}

I really don't like football. I don't like most sports[^0], but I **REALLY**
don't like football.

Amazon's front-page banner ads have been interactive for some time now. They
usually auto-play content, though, fortunately, they are mute by default.
Sometimes, they'll minimize into a smaller persistent banner that's shown as you
browse the site.

"Sometimes" only applies to Thursday Night Football.

I _**REALLY**_ don't like football.

Ergo prompter hoc, I associate Amazon with football, a thing I spend real,
actual effort trying to avoid.[^1]

### Come for the ads, stay for the Family Tree tier fake shit

Most of the things I buy these days are either not on Amazon (Good cycling
gear, dbrand skins, anything from Patagonia, though this seems to have changed
recently) or are cheaper if
purchased directly from the vendor (almost all toiletries).

This definitely wasn't the case in the past, or at least it didn't _feel_ like
it was.

What _is_ on Amazon, in Costco-sized spades, is mountains and mountains of
cheap, relabeled, drop-shipped items.

{{< figure src="/images/frupidity/just-look-at-this-shit.png" >}}

You know the ones: the brands look like callsigns, the
items look _almost_ like what you were actually looking for, and when they
inevitably break a short while later and you post a bad review in response,
they'll give you the "better one" for free if you delete the review and three
more free items if you replace the review with a positive one.

While this isn't universally the case (Anker batteries and chargers are
top-notch and are almost exclusively sold on Amazon), it's been the default
experience for me and [many
others](https://www.digitalcommerce360.com/2022/01/19/nearly-a-third-of-amazon-shoppers-are-disappointed-by-quality-or-timeliness/)
over the years. I didn't want to be stuck in a cycle of continuing to buy things
from a vendor that disappoints me, so I cancelled.

### Subscribe and Save: The Last Straw

Full screen reminders to watch football like a True American™ and hoardes of
cheap junk were definitely annoying, but I did usually find what I was looking
for and get it quickly.

However, it was the death by a thousand cut that is Amazon's Subscribe and Save
service that finally did me in.

{{< figure src="/images/frupidity/subscribe-and-save.png" >}}

I was a fairly faithful user of Amazon's Subscribe and Save service for several
years. Subscribe and Save enables you to purchase select items at a discount on
a recurring schedule so that you don't have to remember to purchase, say,
Listerine mouthwash, every month. 

I had 33 or so subscriptions that renewed every 1-6 months. Subscribe and Save
does what it says on the till: I get an email when the renewal period arrives,
the item ships shortly after that, and I receive it after a few days of waiting.

Unfortunately, "doing what it says on the till" doesn't tell the full story. In
reality, using Subscribe and Save became an extremely frustrating experience.

#### 10% discount now, `rand(-100,100)`% discount later

Subscribe and Save only guarantees a discount on the _first_ purchase of the
subscribed item. How much you pay for every order after that is essentially a
gamble. There is also no way to set a ceiling on the price of a subscribed item.

#### How much did I pay anyway?

Finding out how much you paid for an item purchased via Subscribe and Save is a
surprisingly difficult endeavor.

Here's a real life example. I want to get a report of the amount I've spent on a
Subscribe and Save item within the last six months.

Let's start with the list of subscriptions I currently have.[^4]

{{< figure src="/images/frupidity/subscribe-and-save-1.png" >}}

As we can see, I only have one item: a two-pack of Vaseline (an excellent
skin moisturizer for my extremely ashy skin that magically turns into dust the
minute it touches water).

Let's click on it.


{{< figure src="/images/frupidity/subscribe-and-save-2.png" >}}

Ignoring the distractions below, we see an option to "View Order History".
That's convenient. Let's click on it.


{{< figure src="/images/frupidity/subscribe-and-save-3.png" >}}

To get the actual amount I spent, I'd have to click on the order number here,
which will take me to the Order Summary for **the order that the Vaseline was
shipped with**. This order might or might not be just the moisturizer, so now
it's on you to dig into the order, break out the cost of just the vaseline (and
taxes, if you need to be that specific).

The actual problem is in the UHHHHHHHHHHHHHHH section.

I actually started this subscription back in 2022.

{{< figure src="/images/frupidity/subscribe-and-save-5.png" >}}

The only way I knew that was by _remembering_ that I had a subscription for this
item for much longer than was reported here.

So now the task of creating a report of your spend on this item for the last six
months becomes a human data pipeline of searching for all of the orders this
subscription _might_ have been a part of, extracting the cost of those items
from the rest of the orders from which they originated, recalculating tax and
shipping costs (if you care), and, finally, saving them into a spreadsheet,
maybe with a total.

#### But email

"But Amazon sends emails whenever you place an order. Couldn't you just search
for references to Vaseline in your email and get totals that way?"

Great idea! No!

{{< figure src="/images/frupidity/subscribe-and-save-sigh.png" >}}

Items purchased via Subscribe and Save look like any other item you purchase.
To prevent Google from building a competitor using Amazon's price data and
their world-class data mining expertise, Amazon hides references to items that you
purchased in the receipts they send you. They look like this.

If you know the order number of what you're looking for, this works, but See
Also: the last section.

Since I track all of my recurring expenses in my money management spreadsheet,
this made simple questions like these nearly impossible to answer.[^2]

#### But Privacy.com

> You have dedicated cards for Subscribe and Save? That's cute. Fuck you.
>
> _Amazon_

I use [Privacy](https://privacy.com) to pay for all of my recurring expenses.
Privacy makes it really easy for me to create virtual cards linked to my bank
account that I can use online for all sorts of stuff.

A winning feature of these cards is being able to set permanent or periodic
spend limits on them. You can set limits as low as $1 and as high as whatever
your monthly allowed spend with Privacy is.

There were two scares where Privacy thought I did something nasty and locked my
account and all of my cards temporarily, but they were resolved quickly enough
and their support is slow, but helpful.

One of those times was because of Subscribe and Save.

Privacy will not allow you to use a single card with multiple _vendors_. Fortunately
for me, the vendor for every Susbscribe and Save purchase is the same:
`AMAZON.COM/BI`. Consequently, you (or Amazon) can totally mix and match these
cards as it sees fit.

However, to prevent scammers from trying to fulfill
purchases with zero-dollar cards and vendors blocking Privacy's issuer
identification numbers in response, Privacy restricts the number of cards you
can create wiht a single vendor.

I had 33 subscriptions. That's 33 Privacy cards. 32 more than Privacy is
comfortable with me having with `AMAZON.COM/BI`. So they sounded the `YOU'RE
PROBABLY DOING SOMETHING NASTY`[^3] alert and temporarily locked my cards and
account.

Ultimately, I had to coalesce all 33 cards into one, which solved the "which
card will Amazon charge this time" problem but brought me back to square zero of
"how the fuck do I budget Subscribe and Save" problem.

### Alternatives

These are the alternatives to Amazon stuff that I'm using or will begin to use.

This doesn't include AWS and AWS-adjacent services like Alexa, though moving
those over to other providers isn't out of the realm of possibility.

#### Cheap, Dollar Tree, Disposable Shit

I still shop Amazon when I need cheap Dollar Tree shit, like a snapback hat
extender because my head is gigantic[^5]. I'll pay a little more for two-day
shipping, but whatever.

#### Shopping

For regular purchases, I try to buy direct from the vendor or from a small
business locally. Shipping speed is slower, but at least I'm more likely to
get it. Worst case, I shop at a big-box store like Target (whose online
ordering systems are surprisingly good while significantly less frustrating than
Amazon's attention-stealing bazaar, and they do same-day shipping!).

#### Groceries

HEB or Kroger for life. I never used Amazon Fresh and rarely shop at Whole
Foods, so no delta here.

#### Music

Amazon Music is a pathetic joke. Unless you want to listen to Top 40 or whatever
you _didn't_ ask for. In that case, Amazon Music is brilliant.

I'll continue using Apple Music.

#### Subscribe and Save

Ugh. This was the one holdout that prevented me from quitting Amazon cold
turkey. As mind-blisteringly annoying as the service is, there aren't really any
alternatives.

So I had to go back in time a little bit. How did I buy stuff on a recurring
basis? Reminders and shopping lists!

Apple Reminders makes creating reminders for every subscription period I used to
have super easy, so that's a solved problem.

Now I just needed a service that allowed me to create a list of things to buy
during each of those periods in one fell swoop.

Surprisingly, Walmart has this.

I was able to create a list for every renewal period I used to have on Subscribe
and Save and add items to those list. Buying everything on that list should be
as easy as adding everything to a cart and checking out.

Since Walmart's logistics is just beneath Amazon's in scale (acutally better,
but also worse, given that you can pick stuff up from their brick and mortar
stores), I'm considering this to be a defcent alternative for now.

In a surprise twist, because household goods on Amazon are more expensive than
at brick and mortars, I even saved a bunch of money (to the tune of $600/year)!

### Footnotes

[^0]: if bowling, cycling or curling is on, though, apologies, but I'm no longer
    paying attention to you.
[^1]: nearly impossible to do in Texas, or at my local gym that has TVs in every
    direction for some reason.
[^2]: "Just use Amazon's Orders API to get these orders and track them
    automatically," is a great idea...if it existed. Amazon doesn't have any
    customer-facing APIs and good luck trying to use their BFF as a workaround.
    Hey; I just remembered another reason why I canceled Amazon this year!
[^3]: https://ithelp.metro.ucdavis.edu/kb/how-fix-remote-host-identification-has-changed-error
[^4]: "Gee, it'd be great if Amazon had a tool that lets you export your order
    history to CSV so you can run reports or feel bad about how much you've
    spent with them over the years," is what you'd _probably_ start with...and
    Amazon had that functionality! Or at least they did until they [took that 
    away earlier this year](https://old.reddit.com/r/DataHoarder/comments/11kbuta/amazon_order_history_reports_ending_march_20_2023/) because apparently maintaining a SQL query to turn your data into CSV
    is too much of a strain on their infinitely vast compute resources.
[^5]: Ironically, I didn't correctly read the listing because it was [a huge-ass
    word
    salad](https://www.amazon.com/dp/B01J6KA4RI?psc=1&ref=ppx_yo2ov_dt_b_product_details),
    very common amongst callsign drop-shipper bullshit, and landed up purchasing
    the right thing from Etsy.

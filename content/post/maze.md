---
title: Maze
date: 2026-02-12T18:45:31-06:00
draft: false
categories: 
  - hacks
tags: 
  - maps
  - ai
  - enshittification
  - luddite
---

> **TL;DWR**: I found a way of using Apple Maps with Google Maps to avoid their
> annoying (to me) "Know Before You Go" AI-powered feature.
>
> [Go here](#maze) if you want to skip the preaching and go straight
> to the solve.

Last November (or so), Google added this to Maps:

{{< figure src="/images/maze/kbyg.jpg" >}}

and, for the first time in my life, had me considering buying a crisp set of
Rand McNally maps for my travel pack. I already daily a hip pack, so I'm
basically halfway there.

I mean, the feature itself is fine. I can't be mad at an app telling me that parking
might be difficult at a spot within the heart of "famously-always-in-traffic"
Chicago, and it doesn't take a large leap to see how others might appreciate
knowing a restaurant's top-selling item without having to trudge through
handfuls of reviews complaining about parking.

It's the _"shoving down your throat"_-ness about this feature that had me mad enough to
potentially buy a nice pocket compass.

(Before you continue, you should know that
[I](https://news.ycombinator.com/item?id=46969337)
[have](https://news.ycombinator.com/item?id=46882422)
[socioethical](https://news.ycombinator.com/item?id=46679645)
[concerns](https://news.ycombinator.com/item?id=45739439) with the AI industry
in its current state, though I'm not
[completely](https://news.ycombinator.com/item?id=46788750) refusing to use
what's on offer. Take that how you will.)

I use Maps through my personal Google Workspace account. I went through
[what I'd call unreasonable
lengths](https://old.reddit.com/r/gsuite/comments/1i3lo46/how_to_turn_off_gemini_for_workspace_the_real_deal/)
to disable Gemini in my tenant, despite me being forced into [paying
more](https://9to5google.com/2025/01/15/google-workspace-price-increase-2025/)
as a result of the "uncontestable value" that the disabled service
hypothetically brings into my life. Yet, "Know Before You Go" is featured
right beneath the business name..._and it can't be disabled._

New features are great. Forcing me to use new features that **I do not not want
and have never asked for** is inconsiderate and disrespectful, **_especially_** when
I'm paying for the ability to explicitly disable this functionality.

You can't turn off AI Overviews in Google Search either without URL hacks, which
is just as roiling, but I've long since switched to [Kagi](https://kagi.com) for
web search that doesn't "airplane the AI into your mouth" despite expending
significant effort into productizing the technology with local LLMs. While Apple
Maps exists and works well enough, with saved
lists, reviews, menus, pictures and the like, switching away from Google Maps is
nowhere nearly as easy. That Google knows this makes this all the more
frustrating.

But Apple Maps does work well, and I'm already locked all the way into the iOS
ecosystem. I've long been impressed with its significantly stronger navigation
UX, but its continued partnership with Yelp (who have mastered anti-consumer
choice and engagement dark patterns) has sullied my desire to use it full time.

What if I could use both, though? Google Maps doesn't (yet) show AI suggestions
in Safari, so maybe I could search for places in the mobile version and have
Apple Maps do the navigating. Could that work?

## Maze

{{< figure src="/images/maze/maze.png" >}}

Does exactly that.

[Maze](https://apps.apple.com/us/app/maze-maps-switcher/id6504451783) routes
links to locations in mapping services to other mapping services. You share a
URL to a place in Google Maps with Maze, and it gives you the ability to start
navigating to it in Apple Maps.

That's all it does, [and it does it
well.](https://en.wikipedia.org/wiki/Unix_philosophy)

It even uses the old pre-iPhoneOS 7.x skeumorphic fever dream design
that looks a bit comical on my huge iPhone Air screen but is a million times
better than [the alternative](https://en.wikipedia.org/wiki/Liquid_Glass) that
we were also one-way opted-into.

## Other Alternatives

So that I'm not accused of shilling, you can also do something like this
with an [iOS
shortcut](https://www.icloud.com/shortcuts/e5648ede493d4fdfa874fa5b3b249bfe) or
[Mapper](https://apps.apple.com/us/app/mapper-for-safari/id1589391989), a Safari
extension that I couldn't get working in the few minutes I tried it due, surely,
to user error.

## But Google gets the last laugh

Because when you visit Google Maps on Safari, it takes you straight to the app
in the App Store, even when you tap "Stay on web". I mean, how else will Google
protect their
[~$4T](https://www.reuters.com/business/alphabet-hits-4-trillion-valuation-ai-refocus-lifts-sentiment-2026-01-12/)
valuation?

There are extensions that neuter this dark pattern, so it's not worth getting
all ruffled about.

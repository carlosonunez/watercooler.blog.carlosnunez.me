---
title: back to mac
date: 2023-12-29T21:38:00-05:00
draft: false
categories:
- technology
- ipad computing
tags:
- ipad
- tablet
- macbook
- computer
- ios
- macos
---

after using an ipad pro 12.9" as my main computing rig for a year in the field,
i finally threw in the towel this past november and got a macbook.

[this isn't my first go at
this](https://old.reddit.com/r/apple/comments/4db0ce/so_i_used_the_129_ipad_pro_as_a_computer_for_two/).
i tried to make the og ipad pro my main machine back in 2016.[^0]

much has changed since then. the magic keyboard is infinitely better than the
original smart keybaord that was available at the time, for example.
unfortunately, much has also stayed the same.

in my first attempt, iOS was extremely limiting. switching apps with ALT-TAB was
flakey, mobile safari was basically unusable for desktop versions of websites
compared to desktop safari, and iOS's aggressive background app suspension made
it difficult to maintain a solid SSH session with my mac at honme.

in this attempt...iOS is _still_ extremely limiting for actual computing.

i knew i would need to ssh into my mac mini at home for any real work and
accepted that (well, mostly; more on this later). but the inconveniences
extended beyond this.

first, ios has a file explorer, but it's not a real file
explorer. it's a sandboxed app that can be a huge pain for other apps to access
as well as a gateway through which other apps store external data through. this
is a real problem with apps like google drive or blink that don't behave well
with Files at all and require you to restart your ipad after a few minutes of
being unable to see or interact with your files.

second, mobile safari still doesn't cut it. while more desktop versions of
websites render properly now, many sites don't understand what to do with a
stylus-like cursor hovering over an element.

finally, window management. you'll never miss overlapping windows more than
trying for the 247th time to make stage manager work and failing because, sorry
y'all, _it just sucks_. while windowing within iOS was a death by a thousand
slow cuts situation, the best way I can describe the experience is this:
traditional windows adapt to your workflow, whereas you need to adapt your
workflow for stage manager. i'm pretty sure i tried to switch spaces at least
once daily while owning the thing.

what finally did me in was the main exception that made this work for me in the
first place: coding/testing/building remotely.

you'll need to ssh into another computer to do any real computing work. there's
no real way around this[^1].. of course, most folks won't just expose their main
computing rig to the internet like that. they'll want ot set up a vpn for the
mac, and potentially only the mac, to connect through.

the issue here? say goodbye to your mac's awesome battery life.

every single vpn implementation will use significantly more energy than working
locally due to per-packet encryption/decryption. i used tailscale for a long
while during this experience, and even they are struggling with getting
battery life under control. i often had to make sure i had  my charger on me,
which is precisely what i came to the ipad to avoid.

meanwhile, the m2 macbook air I'm writing this on is estimating ~19hrs of
battery life on 100% state of charge. _and_ that's  with docker running!
shockingly, it's also way thinner than the iPad with the smart keyboard
attachment and feels much highter.

i'd love to try this again once iOS gains virtualization capabilities and allows
me to run a Linux box on iOS. however, until then, it's the macbook life for me.

## Footnotes

[^0]: the original post was deleted along with all of my other posts on reddit;
    i'll post the original somewhere at some point, but you can find part of it
    in the [internet
    archive](https://web.archive.org/web/20230605081227/https://www.reddit.com/r/apple/comments/4db0ce/so_i_used_the_129_ipad_pro_as_a_computer_for_two/).
[^1]: unless you want to try using the version of Alpine bundled into iSH and
    enjoy super slow performance due to translating syscalls entirely in
    userspace

# Embrace, Extend, Extinguish?

Whenever Microsoft does anything, it falls into two buckets. If it's bad, it's Microsoft being bad. We know this type. If it's *good,* however, this is even worse: it's an example of an insidious strategy Microsoft pursues called Embrace, Extend, and Extinguish, and even though you thought it was good, it's secretly bad.

## Definition

The term refers to a Microsoft market-share acquisition strategy invented by Gates. The standard example is AOL's chat system, AIM. MSN Messenger, when it was first released, Embraced the AIM protocol in order to benefit from the existing network. They then Extended it with new features that only worked in MSN Messenger, like custom profile pictures and emojis. With it distributed for free on Windows systems, users no longer had a reason to download AIM, and AIM was slowly Extinguished.

## This didn't happen

Actually, MSN Messenger was blocked from AIM one day after release. Microsoft kept trying to work around whatever they were doing, but they kept working around the workarounds, and Microsoft stopped trying after a few months in late 1999. AIM popularity didn't start declining until the mid-2000s. It was eaten by other products besides MSN Messenger, like Skype, and via the normal method, i.e. them being better products.

## Was the example cherry-picked?

Wikipedia chooses to list [five examples](https://en.wikipedia.org/wiki/Embrace,_extend,_and_extinguish#Examples_by_Microsoft). This is the only one that alleges every component of the strategy plus success. The others refer to: 

- breaking compatibility with Netscape Navigator, but *not* web standards themselves (for those who are not scholars of ancient history, Netscape essentially [committed suicide](https://www.joelonsoftware.com/2000/04/06/things-you-should-never-do-part-i/) and Microsoft didn't have to try very hard)
- in Office, trying to use one proprietary Microsoft feature to prop up another proprietary Microsoft feature
- *failing* to do anything to Java (in a feature that represented a genuine business need, so much so that they responded by cloning the entire language as C#)
- requiring OAuth2 based authentication when using the IMAP protocol, which through a little bit of textual trickery can be made to sound like blocking off IMAP totally, even though the protocol is open and my client supports it

That Java point is the weakest and it looks really weird defending it. But it's important to understand that Microsoft is supposed to be *notorious*. There's supposed to be a road paved with skulls.

Microsoft's internal *desire* to do these things in the years 1996-1998 is well known, as turned up in documents from their antitrust suit. I won't complain that nothing of the sort ever existed. Java was a genuine danger case, whether or not they failed and whether or not they actually needed to, and there are some real systems they got shuttered like Kerberos. This was an honest-to-goodness business strategy pushed by Gates.

However, nobody can point to any legitimate examples since Gates dropped the reins.

## Economists predicting one billion of the last zero recessions

If a company's core technology platform is suddenly open-sourced, and has every proprietary extension filed off in a breaking change that the company fully commits to going forward, you might call that a good thing! Unless it's Microsoft, whose open-sourcing of .NET Core was obviously an attempt to EEE Mono. It was also EEE when they ported their proprietary debugger to it without open-sourcing it.

If a proprietary OS, well known for doing things very differently than Linux, adds the ability to *really easily* run Linux in parallel, each mounting the other's filesystem and sharing the network interface and so on, that's an incredibly good feature! Unless it's Microsoft, in which case it's an attempt to EEE Linux. Once you've taken WSL for granted and forgotten it made any sense to be mad about it, adding X integration to use windowed software is freshly EEE.

If a company adds Python integration to its spreadsheet software, surely that would be a good thing! Unless it's Microsoft, in which case it's attempting to EEE... their own spreadsheet software? Couldn't be Python, right? Details to be filled in later.

Each of these got about a million upvotes on Hacker News. If you were to ask the people clicking that little upvote button, "Do you think that allowing WSL to use graphical Linux apps is part of an explicitly-spelled-out strategy to convince existing Linux users to use Windows until Linux is fully dead, which is likely to work?", they would most likely say, "well, no, not when you put it like that." Actually it is very hard to imagine Microsoft has *any* strategy for getting you to use Windows at all right now.

## Stop jumping at shadows, or at least jump the correct amount

It is good for products to offer integrations with things you already use. That is probably one of the best features a product can gain.

It is acceptable for products to be anything other than open source. Open source products are kind of hard to make a profit on.

It is *normal* for products around a standard to have nonstandard extensions. This one is very important - I feel like most 'standards-bearers' don't understand that standards committees don't like to be the ones to design software. Proprietary MSVC features can't be an attempt to take control of C++ because the C++ committee literally wants you to do that.

It is bad when platforms deliberately don't support useful things, in an attempt to shore up their own profit margins. *This is not evidence of a corporation-wide conspiracy.* You can just call it "bad", without resorting to "antitrust behavior with the goal of shuttering the other thing entirely", and without beginning a policy of jumping at shadows.

The shadows haven't contained monsters for a full *quarter century.* Around the midpoint of that, Microsoft underwent a staggering sea change and started open-sourcing as many of their things as possible, porting and integrating and adopting and all sorts of things. The company's almost unrecognizable. The specter of EEE persists only in your repeating it: you worry that some event is an example of it, this worry is folded into your general confirmation bias about it, and you become [more likely to worry about the next thing](https://www.astralcodexten.com/p/trapped-priors-as-a-basic-problem), even though you never saw anything at all.

Elevate the level of technical discussions on the internet by evaluating things on their merits.
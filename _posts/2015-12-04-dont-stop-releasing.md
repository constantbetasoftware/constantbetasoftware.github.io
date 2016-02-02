---
layout: post
title: Don't Stop Releasing
---

How did writing about *Feature Parity Between Your Apps is a Bad Idea* turn into this?



### The scenario

You have multiple versions of an app for the different platforms (e.g. web, android, ios) and new features are held back from release until they are implemented in all of them.

There isn't really a good argument for this, it's usually simply caused by [System 1](https://en.wikipedia.org/wiki/Thinking,_Fast_and_Slow#Two_systems) being in charge.

What commonly happens is that the new feature is added to the current sprint of all of the projects and deployment often happens in sync because there will be some dependencies, e.g. apps will need new changes to the backend but the backend project is going to be ready before the apps (it generally moves faster). So the backend will wait for the apps to be ready before deploying those specific changes to production. It's just safer to deploy everything at the same time to easily trace any problem that might arise, instead of having to go back and forth.

So you wait for everyone to be ready before releasing that new feature. Sounds familiar, yeah?



### What's wrong with this process?

While this kind of process might make life easier for Engineering (by reducing the potential amount of back and forth going on - which can be exhausting), you pay a price at the Product level.

What do I mean by this? Well, let's go back to the near past, when you were a scrappy startup and could only afford to hire 1 mobile engineer.
You had to make a choice, even if the Engineer was able to release for all platforms: Android or iOS (or Windows Mobile, ahahahah)?
Life was simple, you just had to decide which mobile features to bet on - pretty straightforward. If the features got adopted by the users, great success! If not, ditch it and let's go for the next one.
And that's exactly how things should be, **learning fast** about what works and what doesn't work.

Fast-forward to today, you've hired a team of Engineers for iOS and Android and you've grown in size in your Backend team.
But things simply stopped feeling like they're moving as fast at the Product level, even with all the people.
You're just not getting the same amount of feedback and knowledge about your users and the product.
In the past, 1 month meant trying out 2-3 new features. Today, if you're lucky, it means 1. You've effectly slowed your product down.[^1] [^2]



### What I'm Really Talking About

That scenario illustrates one way things can get bogged down once you start growing the company.
And that's the actual issue: just as imaginative and playful kids grow up and become boring lawyers (sorry lawyers, j/k), interesting companies grow up to become Twitter (nope, not sorry).

The question is why does this happen and how do you go back to the good ol' days?

You can't simply perform a rollback for things have changed.
You have more users and increased expectations (and maybe you're even making \*gasp\* money!) , more people working on the product and the product itself has grown (more features, larger codebase, larger infrastructure).

![The Magician, The Magus, or The Juggler (I)](http://www.tarot-card.net/tarot-cards/images/2ofpents.jpg)

I like to think about this in terms of balance. In this specific case, I'm referring to Product and Engineering.[^3]<br/>
In the beginning, while searching for Product/Market Fit, it was all about moving as fast as possible and not paying much attention towards how things were being built (and why would you, if you might end up scrapping or having to rewrite the code anyway).<br/>
Then things got stable and counter-culture kicked in with Engineering taking control.<br/>
But now you can't go back into your reckless ways because it'll destroy all the work that has been done.

You have to find a way that allows you to improve the Product quickly and keep learning fast about what works and what doesn't while making sure that everything in Engineering is going well. [^4]

Well, the bad news is that I'm not sure there's a good solution.
When things are a matter of balance, the way to go tends to be about releasing the pressure in one side and increasing the pressure on another side (scaled to N dimensions).
That might manifest itself in rearranging the structure of your organization [^5] or hiring more people for the underperforming areas (ack!) or replacing someone at the top (heh). [^6]



### Back to Black

I believe that the best way to get back on track would be to go back to the roots.
This is when having a *mission* is important, it serves as a guideline for where the company wants to go.
(And I'm also a fan of [Backward Chaining](https://en.wikipedia.org/wiki/Backward_chaining)).

For our scenario, take a step back and look at the current state of things:
Are all platforms equally important? How many users do you have in Android or iOS or Web? How many Engineers are you allocating to each?
Asking these questions should help you decide if it makes sense to drop something. [^7]

With the mission in mind, list all features that'll help the product reach it. Are they possible given existing resources?
Maybe it's time to find a new mission for the company? [^8]

Then build on your Team and the Tech's strengths. All things equal, it should be faster to release for Android than for iOS.
Google Play doesn't have the same kinds of barriers that the App Store has. And the latest versions of Android auto-update apps by default.
This makes Android the perfect mobile platform for trying out new features.

To be honest, this sounds just like what Management Consultants get paid to say to underperforming CEOs: *Streamline the company and focus on your core business.*<br/>
But the difference here is that you should streamline in order to be able to spread out and launch lots of new experiments.
And that's what it comes back to at the end of the day: trying out new things and seeing what sticks.
Trust me, that's what everyone's doing, some with a little bit more intuition than others, but it's mainly a game of not dying before finding the gold mine. [^9]

So Move, Fast and Slowly. Or as they might say in the Valley: Release fast, Release often. But don't die.



[^1]: It's also the case that you were probably just been "Hacking" away. Today you have proper "Engineering", and that takes a lot of manpower to maintain.

[^2]: One could also argue that the slowdown is inevitable but I don't agree. Yes, going depthwise will be harder as the search space for useful features in that particular area will exhaust, but there will be no lack of options breadthwise.

[^3]: On that note, there's usually a dichotomy between Product and Engineering (which I'm also portraying here), but Engineering **is** part of the Product.

[^4]: Seriously, don't disregard the quality of your system. Your Engineers will run away from touching spaghethi code and you'll be buried in "*we need to rewrite that from scratch*" projects. You'll also negatively incentivize people to work on the new projects, because everyone likes shiny new toys, and you'll lose your institutional knowledge when hiring new people to clean up and maintain existing systems.

[^5]: Why a company decides to adopt a different structural organization is not necessarily just because of the Product not moving fast enough, but that might be what makes them jump off from the cliff.

[^6]: None of which I believe fix the actual issue.

[^7]: It doesn't have to mean forever. More like a strategic retreat.

[^8]: Or maybe it's time to quit? That **is** an option.

[^9]: [Yes, everyone is just guessing](https://youtu.be/0871VJfvD1c?t=933).

---
layout: post
title: User Feedback
---

> If you really want to get better at something, it's hard to do that without feedback. [^1]

User feedback provides companies knowledge about how their products are being used, what needs to be improved and what's lacking.
It is, perhaps, the most important resource for guiding your product development. [^2]

If you are serious about building a quality product you need to be doing your utmost to tap into this resource and making sure that you get a constant stream of feedback from your users.

This article tries to be a complete overview of user feedback, hopefully answering any question regarding user feedback.

<br/>



# The importance of user feedback

If you want a successful product, you need user feedback. And odds are that you already receive some kind of feedback.
The mistake is that if you're not conscious of user feedback, you'll tend to overlook it.

What you want to avoid is projecting your bias into the product, the wrong decisions that cause unquantifiable damage, which eventually eat up your time and money and force you to quit.

This should be enough to dedicate your attention to user feedback.

<br/>



# What Is User Feedback

User feedback is any kind of data, from your users, about your product, that can be used to improve its quality.

There are different sources of user feedback, with varying quality and quantity in regards to the data that you can collect and the insights that you can extract from it.
Here's an overview:

![The different sources of user feedback.](/resources/2016-02-29-user-feedback/sources-of-feedback.png)

Having a conversation with your users is perhaps the best way to learn about how your product is being used and what might be wrong (or right) with it. Granted, this needs some preparation so it doesn't become a lost opportunity.
On the other end of the spectrum, basic analytics provide you the most amount of data in regards to the usage of your product. But it won't be able to give you much in terms of insights.

Quantity and quality of the data are not the only dimensions that you can reason in. Some data sources might provide you structured data (e.g. surveys, reviews, behavioral analytics) while others will be pretty informal (e.g. live chat); some sources might tend to give feedback of one specific kind (e.g. helpdesks and bug reports).


While a quality/quantity overview is useful, there are several hidden factors about these data sources that you should have in mind.
Some examples:

- 1-on-1 calls with your users can be very very insightful, but they can also be time intensive and hard to come by (your users will probably have something more useful to do than to talk with you for an hour about your product).
- Product surveys, generally in email form, can be a great way of doing a mass feedback collection. But they can be very biased, since you'll be asking a specific set of questions.
- Behavioral analytics give you the best bang for the buck, but they won't tell you why things are happening, just that they are.

The challenge then becomes of understanding each source of user feedback, what to expect from them and when to deploy them.

<br/>



# When?

For optimal results, different stages of a product should tap into different user feedback sources.  There are also some data sources that can (and should) be monitored throughout the lifetime of the product.

Peter Reinhardt, from <a href="http://segment.io" target="_blank">Segment</a>, [has talked a bit about this](http://firstround.com/review/the-tools-early-stage-startups-actually-need-to-understand-their-customers/):

> **On deciding where to start.** “As far as customer data analytics tools are concerned, by and large startups begin with Google Analytics.
It may seem obvious, but don’t overlook it. It’ll give your startup a basic idea of your visitors, what content they’re viewing and where they are coming from.
It’s free, a pretty good tool and will get you through the first year in terms of analytics for the most part.
>
> **On upleveling analytics tools.** “Start integrating tools for more complex analytics after you get to product-market fit.
When you’re getting more granular and want a deeper understanding of, say, the conversion funnel from the homepage to the innards of your product, expand to a full funnel analysis tool like Amplitude, Mixpanel or Kissmetrics.
You’ll then reach a point — likely around 30 people —- when the questions that you’re asking about your customer data become too complicated for an out-of-the-box tool.
If you’re looking beyond the funnel to a more holistic analysis of your business, start considering Looker, Mode or Periscope to give you SQL Business Intelligence systems to get an operation-wide view.
These tools connect to data warehouses like Redshift.”
>
> **On diving into diagnosis tools.** “There comes a point when you’ve got a sense for where there’s a leak in the funnel, such as when people are signing up, but aren’t activating.
At this point, we’ve found that qualitative feedback is much more interesting and impactful than quantitative analysis, especially when you have a statistically insignificant number of customers.
Consider live chat tools like Olark, Livechat and Intercom.
I'm not sure how you would even get started building a web or mobile product without some sort of really high bandwidth communication mechanism to your customers.”
>
> **On switching on visitor recording.** “Visitor recording can be very helpful with product marketing and life cycle.
It’s a valuable tool for product teams to use to understand what’s happening at the individual user level.
So if there’s only 10% conversion at a specific step in the product activation flow, you can watch recordings of users’ behavior and see that the button is invisible, for example.”
>
> **On pursuing market attribution tools:** “When a consumer startup starts investing in paid acquisition as part of its marketing efforts, the top of the funnel analysis from Google Analytics won’t cut it.
Shop for a marketing attribution tool such as Convertro for web and Kochava or Hasoffers for mobile.
>
> **On introducing drip emails.** “Introduce drip emails at the point when your analytics and diagnosis tools are revealing where users are dropping off, but you can’t yet get to it in the queue of product fixes.
Send them messages to help them plug that hole or get them over a barrier that they might have encountered.”
>
> **On activating sales and support tools.** “These products are truly beneficial after your analytics, diagnosis and drip-email tools are working together and there’s the beginnings of a sales and support team.
So that they can do their job, they need more context about what the customer experience has been so far.
That requires extracting data about funnels and actions customers have taken in the app so that sales and support people can help customers without constantly needing to ask what they’ve been up to.”

I'd like to add some comments from a different perspective. Take the following, very common, scenario:

You've launched on ProductHunt/HN/etc, got some attention and the user count rose a bit. But you know you've hit a ceiling because retention numbers suck.

The question is of course: now what? Maybe you had your roadmap ready and just intend on keep going, maybe you hope to gain some insights from your new users and go from there.

I believe the answer should be both. It's important to have a roadmap ready before jumping into a public launch. And paying attention to what your users are saying will help you validate/dismiss what you had planned. This is perhaps the ideal time to try and book those 1-on-1 calls with your users.

<br/>



# How Everyone Is Doing It

> “If you're building a web or mobile business, the way in which you interact with your customers is often via e-mail, push notifications, SMS or surveys inside or outside the product,”
> (...)
> “The way you discover how easily they're using your product is with an analytics tool that shows you a funnel.

Again, [Peter's post](http://firstround.com/review/the-tools-early-stage-startups-actually-need-to-understand-their-customers/) talks a bit about understanding users:

> **Basic top of the funnel analytics**: Google Analytics.
>
> **Mid-to deep-funnel analytics**: Mixpanel, Amplitude and Kissmetrics. These are especially well-suited as event tracking tools.
>
> **Business-wide analytics**: Looker, Mode and Periscope for SQL business intelligence.
>
> **Diagnosis tools**: Olark, Livechat and Intercom. For the video recording segment of diagnosis tools, Fullstory and Inspectlet are the top choices. They provide the ability to watch what customers are doing, maybe even while talking to them on a live chat tool.
>
> **Drip email**: Customer.io and Autopilot. Mailchimp works well for traditional e-mail list management.
>
> **Sales and support tools**: Zendesk and Salesforce.
>
> **Paid acquisition**: Facebook and Twitter.
>
> **Attribution**: Convertro (web) and Kochava or Hasoffers (mobile).

Something else to think about: a lot of emphasis is given to analytics and A/B testing - they have been all the rage of the past ~10 years - but they lack one important aspect: user sentiment.
How do your users feel about the product? Are they feeling frustrated? Happy? Just "meh"? [^3]

These days, you'll know about how the users are feeling mainly through one of these ways: email, social networks (mainly twitter) and app store/google play reviews.
But the problem with these sources is that they'll usually only capture the most extreme feelings, "*hate*" or "*love*".
That's when a user feels compelled to review your product.

For inspiration, perhaps one should look into products that give emphasis to feedback in their use-flow. Products such as Amazon, Tripadvisor, Yelp, and the like.

<br/>



# Final Thoughts

Remember that getting feedback is not the final step of the pipeline. The final step is to act on the feedback.
You must incorporate the received feedback by implementing features that adress the issues. And of course, be selective on what you pay attention to.
Feedback is just a part of the compass that guides the product development.

Still,

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Startups are better off talking to users than x, for almost all values of x.</p>&mdash; Paul Graham (@paulg) <a href="https://twitter.com/paulg/status/705173853509591040">March 2, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

![\#squadgoals](/resources/2016-02-29-user-feedback/squadgoals.jpg)

\#squadgoals

<br/>



# References

[The Tools Early-Stage Startups Actually Need to Understand Their Customers](http://firstround.com/review/the-tools-early-stage-startups-actually-need-to-understand-their-customers/)





[^1]: [Freakonomics Radio: "When Is a Negative a Positive?"](http://freakonomics.com/2013/03/06/when-is-a-negative-a-positive-a-new-marketplace-podcast/).

[^2]: Other resources for product development: reading, analyzing competitors, observing the world.

[^3]: Coincidentally the new Facebook Reactions are trying to address this in regards to posts?


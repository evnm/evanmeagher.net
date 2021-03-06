---
layout: post
title: Things I Learned From Five Years in Climate Tech
date: 2020-02-24
---

![](/images/energy-startup-lessons/glacier.jpg)

_This post also [appeared on The Next Web](https://thenextweb.com/syndication/2020/03/20/6-things-i-learned-from-working-in-climate-tech-startups/) in March 2020._

Over the past five years, I've worked at two startups in what is now being called the climate tech sector<sup><a id="fn1ref" href="#fn1">1</a></sup>. Given the recent surge in interest in this space, I thought it would be worthwhile to record a handful of lessons that I've learned from this experience. These lessons span business strategy and the realities of the electric utility industry.

## Timeline: What has this guy actually done?

I left Twitter in early 2015 with the goal of finding software opportunities in grid modernization<sup><a id="fn2ref" href="#fn2">2</a></sup>.

Soon thereafter, I met a couple guys who were leaving <abbr title="Lawrence Berkeley National Laboratory">LBNL</abbr> to start a company around [a novel sensing technique](https://pdfs.semanticscholar.org/931c/9a2e7a5843ed077e8564455b551aff74a655.pdf) for monitoring home energy use. I joined them as the first employee of Whisker Labs, where we set about making it cheaper and easier to mine residential energy data. After a handful of successful pilots and an [acquisition](https://venturebeat.com/2016/12/05/earth-networks-acquires-whisker-labs-and-launches-diy-home-energy-monitor/), I parted ways with Whisker Labs in 2018.

I then spent some time developing an idea to address painpoints I’d observed while working with electric utilities at Whisker Labs. I ended up joining [an early-stage team at X](https://blog.x.company/why-the-electric-grid-needs-a-moonshot-6dbac9b8b2c2) that shared my thinking on this specific problem space. I can’t say much of anything about this project, due to the secretive nature of X.

The following unordered and subjective list reflects my thinking about startups in the energy space, particularly those that aim to sell software to utilities.

## 1. Consumers don’t care about energy

The ideal energy system is one that fades into the background. The overwhelming majority of people don’t ever want to think about how electricity is delivered to their homes or how much of it they’re using. No one actually wants to look at time series plots of energy usage. They just want the lights to turn on when they flip a switch or yell at Alexa.

Early adopter types might enjoy seeing in real time how much power their solar panels are generating or their car is drawing, but this is not functionality that will drive user engagement or revenue at scale.

## 2. Exits are different than those for traditional tech startups

To be blunt—you’re probably not going to sell your climate tech startup to Facebook. In the event you _do_ get acquired, a statistically likely buyer is an oil major like Exxon Mobil, an industrial giant like Siemens, or a European utility like E.ON, Enel, or ENGIE. These companies aren’t going to pay $10 MM per employee or cater to your taste in programming languages or productivity software.

This isn’t to say that energy startups can’t have exits that make money for founders and investors. But the scale of these exits and the character of acquiring companies is typically not what you see for software startups in other venture-fueled verticals.

## 3. You live or die by the trust you build in the industry

Energy is the ultimate example of an industry where “build it and they will come” doesn't work. For utilities, downtime is often measured in fatalities and switching costs are massive. There is huge institutional inertia impeding the adoption of new technology.

Overcoming this inertia takes a long time and requires that your team include deep subject matter experts who can speak the language of the industry. As in any other enterprise setting, you need to build real relationships with stakeholders up and down your target customer's org chart.

And realize that the people who write checks are typically not the people who will use your software. As a consequence, the quality or state-of-the-artness of your technology often won't be a primary contributor to your success.

## 4. Energy economics are a poor match for venture capital

Fundamentally, energy is a commodity good. This translates to razor-thin margins for companies whose primary product is electricity or natural gas. If your business involves selling to these companies, then you inherit their commodity-driven nature, making it very difficult to achieve returns that are attractive to investors used to SaaS companies with 80% margins.

The way many successful companies avoid this problem is by changing the nature of the product they offer. By framing your business around something other than energy/savings (e.g. comfort, convenience, automation, luxury), you can escape the razer-thin margin game. Your overarching mission can still be to save energy or reduce emissions, but as a by-product of a valuable service that customers will pay real money for. In consumer settings, this approach can also help work around the fact that most consumers don't care about energy (discussed above).

Examples:

- Instead of batteries, [sell cars](https://www.tesla.com/).
- Instead of home energy efficiency solutions, sell [smart thermostats](https://nest.com/).
- Instead of commercial energy efficiency solutions, sell [employee comfort](https://www.comfyapp.com/).

## 5. Beware the utility sales cycle

The glacial pace of the utility sales cycle has a big impact on cash management and fundraising for startups. Companies aiming to sell to utilities need to be extra mindful of runway and plan far in advance the traction metrics they can realistically raise money on.

Utilities are some of the most-regulated and slowest-moving companies in existence. They plan budgets in multi-year increments and introduce new technologies over the course of decades. Staying alive as a utility vendor or service provider requires minimizing your company’s burn rate and scraping together enough early pilot projects to show traction to the next round's investors.

For instance, say you start a company with money from friends and family to build a product that will help utilities decarbonize the residential sector. In order to raise money in 9–12 months, institutional investors will expect to see one or two signed pilot agreements and demonstrated progress towards the milestones of these pilots.

So you send emails, get on the phone, and rack up airline miles to sell the stuffing out of your idea. You convince a decision-maker at a utility across the country that your product is the perfect fit for a demonstration project they’ve been planning for months. This person introduces you to an executive with “Innovation” in their title and helps you develop a case for why your product is exactly what they’re looking for.

Three months later, you've made it through an <abbr title="Request For Proposals">RFP</abbr> process and landed a $5 MM pilot. The pilot is split into three phases over the course of the next five years, with most of the money coming in the last phase. $500k lands in your bank account for phase zero, which only extends your runway three months once you factor in the people you’ll need to hire. Seven months has passed since your friends-and-family round and you’re losing sleep over the number of parenthesized numbers in your financial spreadsheets.

---

An aside on funding—grants (for instance, from [the Small Business Innovation Research program](https://www.sbir.gov/) or the [Department of Energy](https://www.grants.gov/learn-grants/grant-making-agencies/department-of-energy.html)) can be an alternative source of early stage funding that is better suited to many energy projects than traditional VC. They provide patient capital and, in many cases, don’t take an equity stake. Grants can help get an R&D project off the ground without having to jump on the VC treadmill right out of the gate.

But grants do have downsides. You lock yourself into arbitrary demonstration milestones that tend to quickly diverge from where market opportunities lie. Customer development should always come first, and you run the risk of getting sidetracked with the care and feeding of grant milestones.

## 6. Policy is more important than technology

As far as bending the warming curve towards 1.5° C is concerned, I think policy and regulatory reform is currently a larger source of leverage than technology. In particular, carbon pricing ([if done right](https://www.washingtonpost.com/climate-environment/the-fastest-way-to-cut-carbon-emissions-is-a-fee-and-a-rebate-top-leaders-say/2020/02/13/b63b766c-4cfc-11ea-bf44-f5043eb3918a_story.html)) is the single most effective tool we have to reduce global emissions.

Don’t get me wrong—technology innovation is obviously a primary means to addressing climate change. But I feel more and more that we’re approaching the point at which technology has gone about as far as it can within the confines of a 20th century policy regime. Buying EVs and solar panels make us feel good, but only represents marginal progress while oil subsidies artificially prop up the internal combustion engine and campaign finance laws give incumbent fossil fuel companies undue influence to hamstring the deployment of clean technologies.

Even within an antagonistic policy framework, solar, wind, and batteries are proving to be cost-competitive with fossil fuels in many geographies. Imagine how far they'll go once the rules actually incentivize them at scale.

I don’t believe that we’ll get where we need to go without a global price on carbon. This is why [I volunteer with the Citizens’ Climate Lobby](/2019/03/my-climate-lobby-hobby/) to build political will for a national carbon fee and dividend policy in the US. It seems insurmountable given the current political climate, but you’d be surprised how much progress we’ve made.

## Closing words of encouragement

As I'm sure this essay has made clear, five years of building technologies for sale to utilities has left me rather burnt out by the slow pace and legacy nature of the energy industry. That being said, I remain excited by the incredible work being done throughout the energy/climate startup ecosystem. I don't mean to dissuade anyone from taking the plunge, but founding teams need to know what they're signing up for.

And investors need to know what they're funding. Energy is not the realm of hyper-growth SaaS apps that can scale to 10 million users in the blink of an eye. A utility might only have 20 people in their organization that will meaningfully use a specialized product. And it could take three years of sales and integration legwork to get a product paid for and incorporated into day-to-day work.

So take these lessons with a grain of salt. If you're setting out on a startup journey in the energy sector, your mileage will undoubtedly vary. I'm rooting for you.

---

*Thanks to
[Apoorv Bhargava](https://www.linkedin.com/in/apoorv-bhargava/),
[Nick Clarke](https://www.linkedin.com/in/nickolasclarke/),
[Alexa Rhoads](https://www.linkedin.com/in/alexarhoads/), and
[Oren Schetrit](https://www.linkedin.com/in/oschetrit/) for reading
and providing feedback on drafts of this essay.*

---

<section class="footnotes">
  <ol>
    <li id="fn1">Née energy tech, green tech, clean tech. <a href="#fn1ref">↩</a></li>
    <li id="fn2">By grid modernization, I’m referring to technology often associated with the buzzword “smart grid”. It involves augmenting the electric grid with information technologies in order to make operations safer, cheaper, and more flexible. Modernizing the grid is table stakes if we want to decarbonize the economy, as it's fundamentally not designed for a world of intermittent renewables and massive energy demand spikes from EVs. <a href="#fn2ref">↩</a></li>
  </ol>
</section>

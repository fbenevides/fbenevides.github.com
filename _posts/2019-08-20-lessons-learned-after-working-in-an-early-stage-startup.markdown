---
title:  "Lessons learned after working in an early-stage startup"
date:   2019-08-20 15:18:00
tags:   software-engineering startups teams
---

There’s no glamour on working in early-stage startups. Low budgets, uncertainty environment, and fast product iterations are completely normal on a daily basis. However, there are a lot of amazing (and complex) challenges to face, especially when the company starts a hypergrowth strategy.

On the engineering side, depending on the business domain of the startup, those challenges could be even more complex: teams must scale fast and hiring new engineers and managers is a really difficult task, systems architecture must evolve and be adapted to the new reality, etc.

After working for Yellow — the largest micro-mobility company in LatAm with bikes, scooters and electric bikes — since day one, I’ve reflected on our actions on those situations and what I would or wouldn’t repeat in the future.

To give some context: we’ve started the company with 5 engineers who had already worked together at other companies, scale-up teams to 20 engineers, went through a merger with Grin — a Mexican company with a completely different culture — and reached 10MM rides in our platform in less than one year of operation.

It means that everything I’m pointing here is based on this experience. The idea is to give some inputs to help others with technical decisions on early-stage startups.

## Don’t start with hype technologies
Also known as "don’t use some technology just because other company did."

I think this might be a cliché, but some early-stage startups engineers I’ve been talking to try to replicate some successful recipes from huge companies like Nubank or Netflix, but usually, their companies have a completely different reality.

Early-stage startups must focus on product improvements, and technical decisions must be taken to support those changes rapidly. Manage to have a few technical debts by creating simple implementations.

Don’t be seduced by hype technologies at the beginning, be focused on launch your product in the safest way.

## People come first. Always.
As one of the first engineers of the company, you might think that your teammates are as motivated as you. You might think that they are aligned with the strategy and have a sense of urgency about the things that should be done.

If you think like that, maybe you’re wrong.

Don’t assume everyone is on the same page. Some ceremonies, like one-on-one meetings and a weekly meeting with the whole company, are good to get an alignment and even better to know each other. Remember: providing context is crucial.

Communication is one of the most serious problems in software engineering. Sometimes we neglect that, especially in early-stage startups, because we are so focused on the product launch or in some results.

Try to create an open environment where everyone feels comfortable to exchange feedbacks or give suggestions. This can be vital for the company culture building and retention of talented engineers.

## Data team must work very closely to the engineering
During the development process, a lot of changes are deployed to production every time. Those changes can affect the data structure of the applications and can lead to huge problems if the communication doesn’t fluent across the teams.

Misalignment between engineering and data teams means that the company’s data is not reliable. Simple like that. And it gets worse: all teams can take wrong decisions because of that. "Been there, done that".

Everyone must have a high-level understanding of how the data is produced by the systems and how the indicators are measured, so I’d suggest to include data team on the engineering & product decisions. And vice-versa.

That’s the best way to turn your data into meaningful, useful and successful business decisions.

## If you can use third-party services, use them
One of the most valuable resources in an early-stage startup is time and you don’t have it. More than that, you don’t have enough people working to create and maintain every infrastructure piece.

With third-party services, you can save a huge amount of work and get the benefit of focus only on your core rules. Most of them have special offers for startups, so you can use it almost for free.

Some useful services for most startups: NewRelic, AWS & Metabase.

## Deployments must be easy from day zero
Things change so fast in early-stage startups. Code is not different. We can move quickly and change many things with a good deployment process.

In Yellow, we’ve achieved that by using third-party services — in this case, CodeBuild and CodePipeline on AWS — and brought us a confident way to test new features and fix bugs rapidly. Also, the cost-benefit ratio for development is pretty good, in our case, just one day.

Deployment reliability will help you a lot in the short-term.

Finally, you need to enjoy the ride. Nothing makes sense if you don’t. There’s a bunch of work to do, but see your product being used by early customers is priceless.
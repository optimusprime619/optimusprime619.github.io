---
layout: post
title:  "Committing code on friday - Simple remedy for a classic problem"
date:   2018-10-14 00:11:48 +0530
categories: codinghorror fridaycheckin
---
Ever get that sinking feeling in your stomach that you might have left the tap open or the stove on when you left home in a hurry and when you return to see the streets flooded or civilization burnt to the ground? Disregarding the hyperbole, I think you get the point I'm trying to convey here. Developers have a similar feeling when we check-in code on fridays.

We blame monday for being a developer's worst nightmare but its friday that's truly evil. Monday is like an army of indestructible force marching its way right at you, not witholding its intent to knock you down to the ground. 

Quoting the words of Thanos son of Alars: 

> "Dread it. 
> Run from it. 
> Destiny still arrives" 

seems rather appropriate and pretty much sums it up.You see it a mile away, sense the inevitablity of the situation, get knocked down and then you go about your business. 

But Friday - makes you yearn for it, you look forward to, makes you hope and cherish the fleeting moments in expectation of the weekend. It lowers your defences, makes you vulnerable and before you know it, you are caught up in a web of your own making. It may be the result of a last minute change in the requirement, or slacking off a whole week, never having cared to test your code for anything other than the best case scenario etc., one of many circumstances or happenstance. [Murphy's law] immediately takes effect.

Before you know it, a bunch of e-mails sent all around starting off a deranged sport 
- to state and repeat the obvious, 
- having maximum number of **ASAP** in a single mail 
- using \*\*urgent\*\* and \*\*critical\*\* all over the subject and finally
- unleashing creativity in painting the mail loops red. 

Then begins a series of events of people trying to outcall the guy who either caused the problem in the first place or the one who could fix it, in most cases the same individual, making claims about the potential loss and incurring the wrath of the stakeholders/clients who are painted as pictures of demigods unleashing their wrath upon the top management of your workplace. Your plans (or whatever you call it to spend away the weekend) vanishes like a wisp of smoke into the thin air. 

Once the situation is sorted either by fixing or revoking or placing an ad-hoc fix of circumventing the cause of the problem then begins a familiar set of manoeuvres. This involves and is not limited to having a call with upper management explaining in great technical details to folks who either don't bother to understand or simply can't manage to understand it and ask you to prepare a root cause analysis document for it before end of day. 

Yes!! a single word document has powers that the human mind simply cannot comprehend to understand in such situations. Then begins a retrospective (witch-hunt) of existing processes, a fit-gap analysis and a recommended 10 step (why 10 you ask - because even & divisible by 5) remediation strategy that has nothing to do with fixing anything and only serves to make life more miserable for everyone involved.

So how do we fix this age-old problem that has been plaguing us for so long?

# Don't commit code on a friday and deploy it any place deemed critical.

We as human beings are creatures of emotions and habit than logic. The cause of checking-in code and deploying it on a weekend haphazardously could be attributed as the consequnce of one or many misgivings. 

Self-restraint is a variable attribute across people and affected by multiple external factors and simply cannot be relied upon.

However, the solution to achieve this is rather simple and straightforward. Ladies and gents, without further ado, I present to you the Deus ex machina that will solve this problem.

# Prevent commits on friday using a precommit hook.

[friday-precommit hook]

That's it?

*yep pretty much.*

But this feels like a shameless advertisement for a simplistic shell script.

*Yes, that is exactly what this is.*

This file is the culmination of a single exasperated status message of a fellow acquaintance and developer extrordinaire [xtreak]. Now you know who to blame wasting those few minutes of your life in reading through this :)

As a closing note, I am currently experimenting on the newfound knowledge from a [video] of a bald gentleman playing a ukulele who posed the idea that to learn something new takes around 20 hours and not 10000 hours. The latter is actually the time spent by the best in the field towards attaining the pinnacle of the art or trade. Tl;dr; There will be more such posts where I intend to try this theory out, convey my understanding and make the world a better place..sorry!



[Murphy's law]: https://en.wikipedia.org/wiki/Murphy's_law
[friday-precommit hook]: https://github.com/optimusprime619/friday-pre-commit
[xtreak]: https://tirkarthi.github.io/
[video]: https://www.youtube.com/watch?v=EtJy69cEOtQ
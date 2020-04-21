---
layout: post
title: 21 April 2020 Conflicts of Interest
---
In my opinion, the most difficult problem in open source software development (OSSD) is the incentive structure. 
How do we motivate people to work for free? More importantly: how do we motivate _highly skilled_ developers who 
could otherwise spend their time making buckets of money? The greater good isn't always good enough for good developers.

Take bloomberg guy for example. Clearly, he's super talented. He knows dozens of systems inside and out. But how does he spend his time?
Working for bloomberg. I'm not faulting him on this (I'd take the money too), nor am I bashing on bloomberg (it seems
like an upstanding company despite being in finance). But when it gets down to brass tacks, we've all got limited time,
and he's making bank doing something he loves. And that thing isn't OSSD.<sup>1</sup>

Back to the original problem: _how do we motivate good developers?_.
The most common response: "Easy! Praise the work of the good developers! They can get jobs with all our praise! Everybody wins! Jobs!". 
This is certainly the motivation of many taking this class (myself included). Verizon guy was blatant about the formula:
*contribute to OSSD -> acquire job*. It's simple. And he's right. OSSD contributions are huge in the hiring process because
it shows real world skillz. Verizon guy is just trying to hire the best talent, and the best talent does OSSD. It's a useful signal.

Unfornately, this incentive changes the mindset of the developer. "How do I make meaningful contributions?" becomes "How do I land a job?".
The greater good takes a backseat. _Even more frightening_: the stakes of being wrong get raised to 
astronomical heights. Verizon guy agrees: "Make your github look good or I won't hire you". That isn't a quote,
but he said several times that a presentable github impresses him (the flipside being a bad one does not)<sup>2</sup>. The converse
equation: *not good github -> no job*. When I heard him talk about making a presentable github, I was *this* close to launching into a diatribe 
on corporate america having disproportionate influence on computer science. I didn't because it would've ruined the presentation and
I don't think he would give a talk again.<sup>3</sup> If students are conscious of the fact that employers look at their github,
they won't take risks. What if your OSS project is ideologically opposed to modern advertising practices? What if it
would mean the undoing of a fortune 500 company? What if the founder is a communist nutjob with good intentions?<sup>4</sup>

The corollary to my risk avoidance point is assholery avoidance. It never pays to be an asshole on the internet when you're trying to get a job. 
Sometimes, though, it's necessary. For example, only the most pedantic assholes are capable of finding esoteric security vulnerabilities,
and it's absolutely vital to not shun these people. It needs to be okay to tell someone they're wrong sometimes, 
but if doing so jeopardizes your job or your reputation, nobody is gonna do it. Not even the pedants.

I think the reason this problem is so prevalent in CS and not in similar fields like engineering is twofold.

Firstly, lay people can't see a how program collapses. Civil engineer builds bridge that collapses?<sup>5</sup> It wasn't strong enough. 
Engineer never practices again. Mechanical engineers build car that fakes emissions?<sup>6</sup>  Hit 'em with a fine and fire the engineers. 
Software devs build faulty plane firmware that kills 346 people?<sup>7</sup> Whoops, *something something AI, algorithms, bugs, it's not our fault*. 
My point here isn't that mistakes are more common in software, it's just they're way, way harder for the lay person to understand. For example,
catastrophic mechanical failure is obvious; the car doesn't start. Catastrophic security failure: almost invisible. You get hacked some time in
the future and have no idea why. It's easy to tell a company that the car they designed is gonna explode, because if it does, you're totally vindicated.
It's harder to tell a company/open source project they have a vulnerability because if they get hacked they'll just blame whoever did it and shuck 
responsibility.

Secondly, there's a comical amount of money in software. It's the best paying fields right now, and the result
is that everyone and their mother wants to learn python. Fine, everyone _can_ crank out a full web stack with an online tutorial, but it doesn't mean everyone
_should_. Maybe that's a bit drastic to say. And I'm not trying to gate-keep web development, but I am saying there's an enormous amount of power that goes 
unrecognized.<sup>8</sup>


Let's restate the problem with some changes: _how do we motivate good developers, keep the pedants, and get people jobs?_
I don't actually have a solution to this problem. Academia is frought with people trying to impress each other with clever 
papers that use big words and industry is a bunch of sellouts. Maybe we could do with some kind of hippocratic oath or CS order.<sup>9</sup>
I honestly have no idea.



<sup>1</sup>That's an exageration. He said he spends a small amount of time on ansible.
<sup>2</sup>talent acquisition is a zero sum game.
<sup>3</sup>Also I think he's a hack and there's a reason he works for verizon. His whole presentation
could have been boiled down to: "I work for verizon. I have access to jobs. Open source is cool.
I've never coded a day in my life. I can hire you because I work for verizon. Yeah we don't makes tools at verizon 
but we use the tools other companies make and that's better because reasons. I have no real understanding of the open source tools we
use at verizon but I'm going to list them anyway hoping I don't show my hand. Please use our search engine because there's a pandemic
right now. Open source is cool. I have access to jobs." Despite my blood boiling the entire time, I really did appreciate 
hearing his perspective on open source. He intentions are good, but his incentives are warped.
<sup>4</sup> See lemmy
<sup>5</sup>See [bridge collapse](https://www.constructiondive.com/news/osha-places-blame-for-fiu-bridge-collapse-on-engineer-contractors/556798/) 
<sup>6</sup>See [volkswagen](https://www.bbc.com/news/business-34324772) 
<sup>7</sup>See [boeing](https://www.constructiondive.com/news/osha-places-blame-for-fiu-bridge-collapse-on-engineer-contractors/556798/) 
<sup>8</sup>See [Peter Parker principle](https://youtu.be/DLj988xA08I?t=93)
<sup>9</sup>See [Order of the Engineer](https://en.wikipedia.org/wiki/Order_of_the_Engineer) 


# Designing a great job application process at Exercism

At Exercism, we try hard to do everything as well as we can, espeically when it comes to being fair, kind and inclusive.
On April 27th, our application process came under critisism for posing a time-consuming challenge as the first step.
Various discussion was had - some was vitriolic, but much of it came from people who clearly care about making application processes great for candidates.
It was clear that many people felt the approach we took was wrong.

**We actively want to understand more about why others disagree with the process and how we could fix it.**.
We've therefore created this repository as a space for us to discuss together how to make the application process at Exercism as great as it can be, and in the process hopefully help other organisations like us too.

Further down this README is the original response from our co-founder, Jeremy. 
It outlines some context (much of which was missed in the original discussions) and some of the constraints which we are operating under.
It hopefully adds some colour to the conversation and explains why there's not an obvious solution to how we can make a good hiring process.

## Get involved!

As with everything to do with Exercism, we build it together, exploring and sharing ideas.
We'd love you to contribute to discussions or post your own ideas on how things could be improved. 
Please visit the [Issues tab](https://github.com/exercism/job-application-process/issues) to join in.

When considering the application process for any job at Exercism, please bare in mind three things:
1. We get hundreds of applicants per day for jobs that we push out on channels such as LinkedIn. If we were to spend 10mins on every applicant we get, we'd have 33hrs of work per day.
2. We have no hiring team or manager, and only two of us that work full time are technical.
3. We care about finding people who want to work at Exercism, regardless of their background. The previous opportunities they have been afforded in life should not be indicative of whether we hire them here or not.

Please also take the time to understand what it means for Exercism to be not-for-profit and largely volunteer-built (you can read more below).

With that in mind, your thoughts are welcome. **How do we create a great application process?**

_Please note though that while we love constructive passionate discussion, we strongly enforce Exercism's Code of Conduct here, and do not tolerate abuse._


---

I wanted to take a few minutes to reply to some comments that have occurred over the last 24-hours around Exercism's hiring and provide some clarification on some areas that I feel have maybe been misunderstood or misconstrued. For now, I've put this together as a locked issue so I can get it out quickly, but I might convert it to a blog post later.

This is longer than a Reddit comment because it lays out detail and explains rationales, so I know lots of people won't read it, but I feel its important to have clarity around this subject.

## Background

For the first time in our many-year history, Exercism is hiring. Earlier today, a post when viral on Reddit questioning the ethicalness of our hiring process for a front-end developer, specifically that we ask people to complete a task up-front at the start of the application process. As is often the way with conversations online, there were some well considered comments, a lot of angry vitriol, many half-truths propogated, and some outright lies told. We then started receiving abuse on various channels as a result of the post.

If you're not familiar with Exercism, we're a not-for-profit, open-source educational platform, providing free programming education resources. From day one, we've been almost entirely powered by volunteers. The vast majority of Exercism's codebase is written by volunteers, and volunteers have spent hundreds of thousands of hours mentoring others on the platform for free.

Amongst the numerous comments that I've seen, there are three areas that I feel are valuable to clarify:
- What being a "not for profit" means for Exercism
- That the job post is exploitative
- That the job post is stupid/unethical

## Not for profit

To many people, it seems somewhat disbelievable that people do things for good, for free. I understand this. In a time when people often use the perception of good to make more money off others, it's easy to look at something like Exercism and try to find what's "really" happening.

The (rather boring) truth, though, is that we're just a group of people trying to do something useful and helpful and kind. Katrina and I have created and evolved Exercism not to make money off it, but to try to help others. Exercism doesn't have shares or shareholders - there's no big exit at the end of the rainbow for us. We've turned down millions of investment we've been offered if we "converted" Exercism into a for-profit company. Our whole ethos that we don't want to create a place that exploit our volunteers for our personal gain. There's no big salaries either - both Katrina and I have worked for years for free, and in fact put a lot of our own money into Exercism to get it this far. Now we're hiring and paying staff, we get paid the same amount as everyone else in the team.

In one thread I saw earlier, someone effectively called one of our volunteers a liar for claiming to be a volunteer, arguing that no-one would do what they do for free. Well, the reality is that people do. Exercism is built on the principle that many people like to help others and are willing to give their time doing so. You might not share that belief - you might think volunteering is stupid or for losers - but for many people, it's a positive and valuable way to spend their time, and the success of Exercism is testament to that.

## "Stop exploiting people"

There's been a vocal argument going around that we're asking people to create a production piece of code free as part of the application process.

Let me state clearly that we're not doing this.

I presume that pretty much everyone who's using this argument has never really used Exercism, because if they had they'd realise that all the UI that we're asking people to build already exists. Every component in the project design is a component that lives within Exercism and that is reused in multiple place. Our "mentor testimonials page" is pretty much identical to the page in the design, with the few tweaks that would differentiate it the work of minutes, not hours or days. Therefore the submitted code holds no value to us as a project - it's purely something we can use to compare applicants with. It will never end up in production - we won't ever use it.

I understand people's anger about the concept of exploiting applicants for free work. It's something that happens in the industry and it's appalling. And I understand that it's easy to see something that looks like it might be happening, and feel anger and jump on the bandwagon of vitriol. But rather than send abuse to our team, it would have been so much better to have asked a genuine question and get clarification. Sadly, the internet doesn't lend itself well to this sort of communication and piling in is a lot easier.

## It's stupid/unethical to ask people to create this project.

This one is the most interesting. It's something we've discussed a lot.

I'm pretty willing to accept that maybe it's stupid of us to put a hard challenge up front, but I don't get the "unethical" argument. If you don't want to do the project or apply for the job, then no-one is forcing this on you.
And in fact, we've made a real effort to ensure that if someone puts the work in but doesn't get the role, **we give them feedback**. All applicants receive a ~17 page document analysing their application and giving feedback on how it compares to our own implementation. This feedback has kindly been completed by a volunteer in the community who wants to help us find a great person for the role. (You can spot the people telling the "outright lies" I referred to in the top of this, by those who claimed to have applied and been rejected with one line emails.)

If you were on the community call last week, you'll know we'd already decided the challenge was too big and that we wanted to split into two parts. Nearly everyone that's applied so far has been rejected on the visual (CSS / attention to visual detail) part of the challenge. So we decided to separate out the HTML/CSS part, asking only for that to be submitted, before being put through to the JavaScript "phase" of the application. I hoped that this would reduce the initial barrier of asking someone to commit many hours to the project before getting any feedback.
Sadly, this blew up today before we'd had chance to rewrite things.

The question very few people seem to have asked is why this challenge is here. There are two main answers:
1. Adding some barrier to make it possible to hire.
2. Equaling the playing field

Firstly, we need **some** barrier. We don't have a "hiring manager" or "recruiter" (we don't have the money to hire a hiring manager, and don't want to pay a recruiter who then closes the applicant pool to their network). This means that we need to manually assess each person that applies. The volume of applicants would make it impossible for us to do that without a barrier. For the fundraiser role, we put a single post on LinkedIn, and had 200 applicants per day until we turned the post off. If we spent 10 minutes assessing each applicant, that would take me 33 hours per day to do a first-pass review, so we added a barrier that everyone has to send a video introducing themselves, which reduced the pool dramatically. And we'd expect a lot more applicants for the dev role than the fundraiser role.

So what barrier could we have?

We could ask people to send us samples of their work, but that has two main problems:
1. Visually, we don't know what their work was supposed to look like. Does what they're showing us look like what the designer created? (have they worked with a designer before?) Is the design they implemented ugly to our eyes, but their implementation is perfect. I don't know how we could validly filter based on this.
2. It biases everything towards people's past experience. If they've worked in jobs where they don't have something to show (e.g. in a walled or closed-source system, or as part of a frontend team) they're going to immediately get rejected on that basis. In which case, we'd be asking someone to have contributed to OSS or had hobby projects, before they can apply, which is something also problematic.

We could rely on people sending resumes, but that's hugely problematic too. It biases us towards people who have had the opportunity to have good jobs previously. It doesn't allow for applicants who have built great skills but not yet had the privilege of great jobs.

If you consider some of the best applicants we've had, they'd probably automatically have been rejected on their resumes or past work, but they've got real ability and skill.

We spent a lot of time thinking about this and considering it, and giving everyone the same coding challenge, felt like the fairest way of doing this. I fully think that people could reasonably come to a totally different conclusion here (which is why there's no one set recruiting process in the world). Fundamentally, it's Exercism's decision on how to hire and if it's stupid, that's our loss, but I'm not sure that abusing us for it is helpful.

## Some extra notes
- It's also interesting to see the various different estimates at how long this project would take people, with many people saying it would take them days.
  Most of the good applicants have done the project in 5 or 6 hours from scratch, with the CSS taking about an hour.
  As many people pointed out in Reddit, the CSS is all easily extractable from Figma.
- A few people have said the pay is too cheap.Well, the salary is what we can afford. It's the same salary as the other team members, and the same as I take. It's also the median salary for the role in the UK, where we're based. For some people Exercism's vision, team, and values outweigh the fact that they could earn more elsewhere. For others it won't. That's a decision for individuals to take.
- As well as this job post, we have a second job post up for a Rails Developer at the moment, which has no up-front challenge. We've not promoted either post (yet) and we've had about 20x more applications for the frontend role with the challenge than the backend role without. There's a wealth of reasons that this could be the case, but I don't think the intuitive feeling of "no-one will apply for this because there's a challenge" has evidence to support it at this stage.

## Concluding thoughts

**Is the application too involved?** Probably.We'd already decided to change this by splitting it into two phases, and discussed that with the community before all this blew up today.

**Are we being unethical or exploitative to ask someone to do this challenge?** No, I don't think we are. We're very up-front on the job page about the application process and what's involved. If people don't want to apply, they don't have to. We're not using their work for any production purposes so we're not benefitting from their time, and we're giving them some really "eye-opening" (to quote one good applicant) feedback in return for their effort.

Finally, I'm grateful for everyone in the Exercism community who give up their time for free to help build Exercism and mentor others. I'm sorry for the abuse many of you have recieved and/or witnessed today. Be assured that anyone who has been abusive will be banned from Exercism and our GitHub organisation.

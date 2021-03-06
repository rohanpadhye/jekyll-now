---
layout: post
title: "Equity and Inclusion in International Conference Attendance—What can conference organizers do?"
excerpt_separator: <!--more-->
---

There is no shortage of anecdotes on conference registrants, presenters, volunteers, and organizers being unable to participate due to visa issues [[1](https://www.wired.com/story/african-ai-experts-get-excluded-from-a-conference-again/)][[2](https://twitter.com/timnitGebru/status/1191970600941707265)][[3](https://twitter.com/cestlemieux/status/1188464387662725121)][[4](https://www.the-scientist.com/news-opinion/as-visa-difficulties-persist--scientists-push-for-change-66114)][[5](https://www.insidehighered.com/news/2019/03/28/scholars-complain-visa-problems-ahead-international-conference-canada)]. Further, it has often been pointed out that simply the process of applying for a visa to attend conferences can be [disconcerting](https://twitter.com/vj_chidambaram/status/1165418986445688832), [logistically challenging](https://twitter.com/saniyusuf/status/1178721337688412160), and [dehumanizing](https://twitter.com/timnitGebru/status/1192875890968944640). 


Naturally, visa issues disproportionately affect members of developing nations and underrepresented communities. Visa refusals are also more common for first-time foreign travelers, which means that junior students are likely the most affected group in the population. (I wish I had more comprehensive statistics, but [more on that later](#call-for-data).)

As academics, we cannot easily make sweeping changes in international relations and policy. But perhaps there are steps that we can take in the way we organize and conduct conferences to mitigate biases against national origin and citizenship. 

<!--more-->

I'd like to start by quoting some definitions from the [ICSE 2019 diversity and inclusion plan](https://2019.icse-conferences.org/attending/diversity-and-inclusion):
> **Equity** at its heart is about removing barriers, biases, and obstacles that impede equal access and opportunity to succeed.
> [...]
> **Inclusion** is about creating a conference program and environment that is free from discrimination and where every participant feels welcome, included, respected, and safe.

If these are goals that we all care about, then what can we do to increase equity and inclusion for those affected by barriers such as visa requirements, obstacles such as travel restrictions, and to make international participants feel welcome and included?

To get a better idea, I embarked on an informal study. I scanned the websites of some CS conferences in my field (*programming languages and software engineering*) or in related areas for their policies regarding author attendance and visa issues. If I couldn't find any information on the website, I contacted the general chairs requesting this information. Here's what I found out.

It seems that there are several different inclusive strategies that conference organizers can consider (with overlaps between them):

* **Rotating conference venues around the world**. [ICSE](http://www.icse-conferences.org) is a great example: each year, the conference location rotates between Europe, North America, and either one of the other continents. I was surprised to find that [only two conferences between ICSE 2014 and ICSE 2023](http://www.icse-conferences.org/history.html) were assigned a location in the USA, which is the most common host country for many conferences in this field. 
* **Locating the conference in [a country that is welcoming to visitors](https://www.passportindex.org/byWelcomingRank.php)**. For example, [ICLR 2020](https://iclr.cc/) will be [held in Ethiopia](https://venturebeat.com/2018/11/19/major-ai-conference-is-moving-to-africa-in-2020-due-to-visa-issues/) ([a rank #1 location](https://www.passportindex.org/comparebyDestination.php?p1=et&fl=&s=yes)). *Caveat*: this policy may have important implications for the [carbon cost of conference travel](https://blog.sigplan.org/2019/07/17/acm-conferences-and-the-cost-of-carbon/).
* **Addressing the visa issue explicitly in the *Call for Papers* (CFP)**, and providing means of alternate presentation for affected authors of accepted papers. Of course, there is no doubt that the key value proposition offered by conferences is the ability to meet and interact with others in the community; alternate modes of presentation diminish this value. However, such fallback policies can help potential authors resolve worries about the risk of losing out on publication, should their travel be restricted after paper acceptance. 
	* **Remote presentation**: [OOPSLA](https://www.sigplan.org/Conferences/OOPSLA/) and [POPL](https://www.sigplan.org/Conferences/POPL/) have indicated support for *authors of all nationalities* in their CFPs since 2017 and 2018 respectively. They have recently been joined by another SIGPLAN conference: [PLDI 2020](https://pldi20.sigplan.org/track/pldi-2020-papers#accepted-papers). This option doesn't solve the problem of enabling authors to actually attend the conference, but at least they get the opportunity to present their work to the community.
	* **Delegated presentation**: Allow another conference attendee who is not a co-author to present instead. This prevents the paper from being removed from the program, but does not provide the authors the opportunity to present their own work.
	* **Deferred presentation**: Another strategy is to allow authors to present their work in person at a sister conference, usually held in a different country. [CSCW and ECSCW](https://cscw.acm.org/2019/submit-papers.html) are some of the leaders in this space. This allows the authors to physically attend and present their work to the same (or similar) research community.


The rest of this post outlines, for the conferences that I surveyed, (1) locations for the last 10 years, (2) policy for accepted papers if their authors cannot present in person due to visa issues. Here's a quick summary (detailed results below):

[![Summary of Locations and Policies for ACM SIGPLAN and SIGSOFT conferences](https://blog.padhye.org/images/ConfLocationsPolicies.png?v4)](https://blog.padhye.org/images/ConfLocationsPolicies.png?v4)

If you would like to add to this list (or if you notice any errors), please [send me an email](http://rohan.padhye.org). 

* TOC
{:toc}



## OOPSLA

**Locations 2011–2020**: USA (x7), Greece, Canada, Netherlands. 

OOPSLA appears particularly bad at diversity in conference locations. It has only been held outside of North America *twice* in its 35+ year history, the first one being in 2016!!

However, the [OOPSLA 2017](https://2017.splashcon.org/track/splash-2017-OOPSLA#information-for-authors-of-accepted-papers), [OOPSLA 2018](https://conf.researchr.org/track/splash-2018/splash-2018-OOPSLA#Instructions) and [OOPSLA 2019](https://conf.researchr.org/track/splash-2019/splash-2019-oopsla#information-for-authors-of-accepted-papers) Call for Papers have made strong statements of support for international attendees. I quote the one from 2019 below (emphasis mine):

> We welcome all authors to attend OOPSLA and present accepted papers, **regardless of nationality**. If any author has visa-related difficulties, we will make arrangements to enable **remote participation**.

## POPL

**Locations 2011–2020**: USA (x6), Portugal, France, India, Italy.

The [POPL 2018 Call for Papers](https://popl18.sigplan.org/track/POPL-2018-papers#Call-for-Papers) had a statement similar to that of OOPSLA (emphasis mine):

> POPL welcomes all authors, **regardless of nationality**. If authors are unable despite reasonable effort to obtain visas to travel to the conference, **arrangements to enable remote participation will be made**. In such cases, the general chair, Ranjit Jhala, should be contacted for guidance.

[POPL 2019](https://popl19.sigplan.org/track/POPL-2019-Research-Papers?track=POPL%20Research%20Papers#publication-and-presentation-requirements) and [POPL 2020](https://popl20.sigplan.org/track/POPL-2020-Research-Papers#publication-and-presentation-requirements) have followed suit.

## PLDI

**Locations 2011–2020**: USA (x6), UK (x2), Spain, China.

When I first started collecting data for this post, [PLDI 2020](https://pldi20.sigplan.org/track/pldi-2020-papers) did not have any information about visa-related issues on their website. I used the contact form on the website to ask about this information. The [General Chair](https://pldi20.sigplan.org/profile/alastairdonaldson) and [Program Chair](https://pldi20.sigplan.org/profile/eminatorlak) responded soon: they [updated their CFP](https://pldi20.sigplan.org/track/pldi-2020-papers#accepted-papers) to include the following statement (emphasis mine):

> PLDI welcomes all authors, **regardless of nationality**. If authors are unable despite reasonable effort to obtain visas to travel to the conference, we will make arrangements to enable **remote participation or presentation by another attendee** on behalf of the authors.

I'm glad that my poking around prompted this welcome addition :-).

## ICFP

**Locations 2011–2020**: USA (x3), Germany, UK, Japan (x2), Canada, Sweden, Denmark.


The [CFP for ICFP 2020](https://icfp20.sigplan.org/track/icfp-2020-papers#information-for-authors-of-accepted-papers) (to be held in New Jersey, USA) initially only stated:

> At least one author of each accepted submissions will be expected to attend and present that paper at the conference. 

Since the text said "*expected*" instead of "*required*", I inquired about their policy in case of visa issues preventing authors from meeting this expectation. I sent the General and PC chairs an email on November 3, and I received a response on November 10, exactly one day after this post was published. The CFP was updated to include the following additional text (emphasis in original):

> In extraordinary circumstances, **at the discretion of the principal editor**, alternative presentation methods may be approved for specific papers. The canonical example is where all authors are denied visas to the ICFP host country, in which case a nonauthor may be deputized to present, or various electronic substitutes may be considered. We list these options in the interest of transparency, but please keep in mind that, **most years, no exceptions are granted**. This option is not meant, e.g., to excuse cases where authors find themselves double-booked with other meetings (so, at the time of submitting a paper, please do keep the days of the conference reserved on at least one author’s calendar).

ICFP's locations have clearly been the most diverse among the SIGPLAN conferences that I surveyed.



## ICSE

**Locations 2011–2020**: USA (x3), Korea, Canada, Sweden, Argentina, Italy, India, Switzerland.

Initially, I was pleased to find that ICSE 2020 (to be held in Seoul, South Korea) has a dedicated page on [diversity and inclusion](https://conf.researchr.org/attending/icse-2020/Diversity+and+Inclusion+Plan). However, I was not sure if the stated equity-related goals of "removing barriers, biases, and obstacles that impede equal access and opportunity to succeed" addressed visa issues (*edit: this page has been updated since this post was published*). I therefore sent an email requesting an official policy on the possibility of remote presentations for affected authors of accepted papers. I received a detailed response from an [ICSE 2020 General Co-Chair](https://conf.researchr.org/profile/icse-2020/gregrothermel), who is also currently a member of the [ICSE Steering Committee](http://www.icse-conferences.org/committee.html).

I learned that the visa issue is something that the ICSE Steering Committee is sensitive to and is currently looking into:

> [The] ICSE Steering Committee is going to discuss this issue in it's November meeting, so there may well be an official over-arching position after that.

The rest of the response, concerning only the ICSE 2020 edition in particular, follows (emphasis mine):

> **For 2020, ICSE in general won't support remote presentations**, because we believe that the most powerful thing a conference offers is community and the ability to interact with others directly and in person. Moreover, the costs of running a conference make it important that people attend, as well.  For this reason, ICSE 2020 also does require (and this has been true of all ICSEs in the past decade) that at least one author of a paper register for and attend the entire conference. [...] If no author of a given accepted paper registers for the conference, the paper is withdrawn from the proceedings and does not appear in any digital library.   The same will occur if an author registers, but then, nobody appears in person at the conference to present the paper.
>
>  This all said, [...], if an author of an accepted paper were to register for ICSE 2020, and **due to visa problems could not attend**, and if they could provide evidence that they had made every effort (including acting in a timely manner) to obtain a visa, **we'd likely try to find a way to accommodate them**.

ICSE's trend of rotating conference venues between continents is worth noting, as it reduces the likelihood of members of a particular region being continuously affected. ICSE's locations are probably the most diverse from the conferences surveyed for this post.

## ASE

**Locations 2010–2019**: USA (x5), France, Singapore, Sweden, Germany, Belgium.

Similar to ICSE, I found a page on the [ASE 2019 website](https://2019.ase-conferences.org/) on [Diversity and Inclusion](https://2019.ase-conferences.org/attending/diversity-and-inclusion). I contacted the *Diversity, Inclusion, and Belonging Chairs* inquiring about the possibility of remote presentation for authors who could not attend the conference due to travel restrictions. My email was forwarded to [the General Chair](https://2019.ase-conferences.org/profile/tomzimmermann), who provided the following information (emphasis mine):

> We offer authors two options:
>
> a. **Record a video that we play back for presentation**. We do not allow live remote presentation to minimize the risk of technical issues. We do allow **live Q&amp;A via Skype**. If time zone differences or technical issues prevent a live Q&amp;A, we can collect questions at the end of talks and send to authors for follow-up.
> 
> b. **Presentation by a colleague** can present (who has to be registered; registrations by the non-attending author can be transferred to the presenting colleague). **The colleague does not have to be a co-author**. The colleague can collect questions at the end of the talk and send to the authors for follow up.

The [full response, to four specific questions that I had asked, can be found here](https://blog.padhye.org/ase-2019-response-on-visa-issues).

## ISSTA

**Locations 2011–2020**: USA (x5), China, Netherlands, Germany, Switzerland, Canada

The [ISSTA 2020 CFP](https://conf.researchr.org/track/issta-2020/issta-2020-papers#Call-for-Papers) clearly says:

> At least one author of each accepted paper must register and present the paper at ISSTA 2020 in order for the paper to be published in the proceedings. 

It looks like if none of the co-authors are able to attend, then the paper would be excluded from the proceedings.

I know of at least one student who indicated that she would likely not submit a paper to ISSTA 2020, primarily due to the anticipated hassle of visa issues :-(


## ICST

**Locations 2011–2020**: USA (x2), Portugal, China, Sweden, Japan,  Austria, Luxembourg, Canada, Germany.

Similar to ISSTA, the [ICST 2020 CFP](https://icst2020.info/track/icst-2020-papers#Call-for-Papers) clearly says:

> If a submission is accepted, at least one author of the paper is required to attend the conference and present the paper in person for the paper to be published in the ICST 2020 conference proceedings.

Again, it looks like if none of the co-authors are able to attend in person, then the paper would likely be excluded from the proceedings. 

## CSCW

**Locations 2011–2020**: USA (x8), Canada, China.

Even though CSCW is not my research area, I am including the conference in this list because I have been told by multiple sources that it is a leader in directly addressing visa issues (despite or likely *because* of the fact that it is almost always located in North America).

The [CSCW 2019](https://cscw.acm.org/2019/submit-papers.html) CFP contains probably the most inclusive statements that I have seen. It explicitly addresses (a) paper publication in the proceedings, (b) remote presentation, and (c) presentation at alternate locations. Emphasis mine:

> The conference will find ways to accommodate those who are unable to travel to the United States due to geo-political reasons. **Such papers will be included in the proceedings regardless of the author registration status, and we will seek ways for authors to present their work remotely at the conference**.
>
> The presenting author of an accepted CSCW 2019 paper who is unable to attend due to legal travel barriers (like the US travel ban) **may apply to present at ECSCW 2020 instead**. Please be in touch with the paper chairs if you are eligible and would like to explore this option.
>
> Reciprocally, CSCW 2019 will accommodate presentations of work accepted to ECSCW 2019 in case there are authors prevented from traveling to ECSCW because of legal travel barriers.

[ECSCW](https://ecscw.eusset.eu/) is the European counterpart to CSCW. I think that deferred presentation is quite an innovative solution, and one that ACM SIGSOFT/SIGPLAN conferences might want to consider looking into.


## SOSP / OSDI

**Locations 2011–2020**: USA (x2), Canada, China, Portugal  // SOSP is held every alternate year

**Locations 2011–2020**: USA (x4), Canada  // OSDI is held every alternate year

I was pleased to see that the SOSP 2019 website had a [Diversity, Equity, and Inclusion Plan](https://sosp19.rcs.uwaterloo.ca/dei.html), adapted from that of ICSE. I contacted the general chairs asking about the possibility of alternate presentations for affected authors of accepted papers. However, I was not able to get an official policy to include in this post. 

The [OSDI 2020 CFP](https://www.usenix.org/conference/osdi20/call-for-papers) addresses author attendance and visa requirements, but not what happens if authors are unable to obtain a visa:

> By submitting a paper, you agree that at least one of the authors will attend the conference to present it. [...]
>
> If your paper is accepted and you need an invitation letter to apply for a visa to attend the conference, please contact conference@usenix.org as soon as possible. (Visa applications can take at least 30 working days to process.) Please identify yourself as a presenter and include your mailing address in your email.


## Call For Data!

For us to be able to better study the impact of visa issues on the academic community, I urge conference-organizing bodies to collect and publicly report visa statistics for their attendees. In particular, it would be good to have the following data from each conference: 

1. How many registrants required a visa to attend the conference (even if they had a valid visa from before)?
2. How many registrants had to apply for a visa specifically to travel to the conference?
3. How many registrants had to cancel attendance due to the inability to acquire a visa?

A break-down of this data by country of origin would also be insightful (as long as it does not violate any privacy issues). 

I suspect that ACM already has some data in the form of how many visa support letters were issued and whether any of the recepients subsequently cancelled registration; however, I am not sure how to get hold of this data. 

My hope is that by publicly reporting these statistics in every conference, the community will be better informed to make decisions when choosing a location for a conference, or when deciding on inclusive policies for travel-restricted authors of accepted papers.

----

Changelog:

1. (November 10, 2019): Updated to include OSDI along with SOSP.
2. (November 10, 2019): Updated to include [additional information](https://icfp20.sigplan.org/track/icfp-2020-papers#information-for-authors-of-accepted-papers) provided by ICFP chairs.
3. (November 14, 2019): Updated to indicate that the [ICSE 2020 Diversity and Inclusion Plan](https://conf.researchr.org/attending/icse-2020/Diversity+and+Inclusion+Plan) has been updated to discuss visa issues.

## Join the discussion!

<blockquote class="twitter-tweet" data-theme="light"><p lang="en" dir="ltr">Wrote a new blog post on visa issues and what conference organizers can do to be more inclusive. Includes survey of some recent PL/SE conferences. <a href="https://t.co/BBUaWEG2AW">https://t.co/BBUaWEG2AW</a></p>&mdash; Rohan Padhye (@moarbugs) <a href="https://twitter.com/moarbugs/status/1193332318254985216?ref_src=twsrc%5Etfw">November 10, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

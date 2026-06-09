---
# try also 'default' to start simple
theme: rockdove
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides (markdown enabled)
title: Developers, Assemble! Community is Your Team’s Superpower
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply UnoCSS classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# duration of the presentation
duration: 15min
layout: intro
---

<div class="wrapper">

# ¸Developers Assemble!
Community is Your Team’s Superpower

</div>

<style>
.slidev-layout {
  --color-text: white;
}

.wrapper {
  position: relative;
  z-index: 0;
   /* width: 100%;
   left: 0;
   right: 0; */
}

h1 {
  font-size: 6rem!important;
  line-height: initial;
  font-family: var(--font-family-header-highlight);
  background-color: #adadad;
  background-image: linear-gradient(-40deg, transparent 0%, transparent 40%, #fff 50%, transparent 60%, transparent 100%);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradient 5s ease infinite;
  background-size: 400%;
  padding: 3% 0;
}

h1:before {
  content: '¸Developers Assemble!';
  position: absolute;
  color: transparent;
  background: initial;
   -webkit-background-clip: initial;
  background-clip: initial;
  -webkit-text-fill-color: initial;
  animation: initial;
  text-shadow: 0 0 1em rgba(0,0,0,0.75);
  z-index: -1;
}

@keyframes gradient {
  0% {
    background-position: 0% 50%;
  }
  100% {
    background-position: 100% 50%;
  }
}
</style>

<!--
Today I'm going to be exploring how software communities can **empower your development team** as well as how community involvement could be **crucial to professional growth** and how you as an **employer** or a team can **take advantage of that**.
-->

---
layout: bio
image: /images/Unicorn-transparent.png
tagline: I am where I am today because of software communities
---

- <solar-medal-ribbons-star-bold-duotone /> 6&times; Umbraco MVP
- <solar-presentation-graph-bold-duotone/> umBristol Meetup Organiser
- <solar-case-minimalistic-bold-duotone/> Senior Developer at Bump

<br />

- <logos-mastodon-icon /> [@joe@umbraco&#8239;community.social](https://umbracocommunity.social/joe)
- <logos-bluesky /> [@joe.gl](https://bsky.app/profile/joe.gl)

<!--
But who am I and why does what I say matter?

I'm Joe Glombek. I'm a **6-time Umbraco MVP**, an organizer of the **umBristol Meetup** and a **Senior Developer** at Bump.

And I think it's fair to say that I got **here thanks to software communities**, I certianly have my **current job** because of my involvement in the community.
-->

---
layout: icons-header
cols: 3
---

# <solar-hand-heart-bold-duotone/> What is a software community?

According to [The Open Source Way](https://guidebook.theopensourceway.org/getting-started/community-101)

<!-- The Umbraco Community is made up of over 200,000 talented users and passionate people who make sure Umbraco stays up-to-date, sturdy and level for you.

The Umbraco Community is a part of the Umbraco ecosystem, which through action, involvement and co-operation, makes Umbraco what it is today! -->

::icons::

<v-clicks>

- <solar-sidebar-code-bold-duotone/> Developing
- <solar-minimalistic-magnifer-bug-line-duotone/> Maintaining
- <solar-volume-bold-duotone/> Promoting
- <solar-eye-bold-duotone/> Common vision
- <solar-users-group-two-rounded-bold-duotone/> Camaradarie

</v-clicks>

<!--
Let's start by defining what a software community is. According to **The Open Source Way** it's:

"A **group of people united by** the shared purpose of **developing**,[Click] **maintaining**,[Click] extending, and **promoting**[Click] a specific body of **open source software**. \[...\]

"What unites them is their **common vision**[Click] for the open source software project—as well as the spirit of **camaraderie**[Click] and collective identity that participating in the community affords them."

But what does that look like? ...

-->

---
layout: icons-header
cols: 3
---

# <solar-hand-heart-bold-duotone/> What is a software community?

::icons::

- <solar-minimalistic-magnifer-bug-line-duotone/> Code contributions
- <solar-chat-line-bold-duotone/> Online discussions
- <solar-pen-new-square-bold-duotone/> Blogging
- <solar-presentation-graph-bold-duotone/> Conferences
- <solar-map-point-favourite-bold-duotone/> Meetups

::footer::

https://community.umbraco.com/get-involved/

<!--  Community involvement can involve various activities such as **code contributions**, **online discussions**, **blogging**, **conferences**, and **meetups**.

For ideas of how **Umbraco** likes people to contribute, you can check out how to get involved at the community site at **community.umbraco.com/get-involved**

I've mentioned **meetups** a few times now, but what are those? I'm sure Meetup.com has a good definition...
-->

---
layout: icons-header
cols: 2
hide: true
---

# <solar-hand-heart-bold-duotone/> My software communities

::icons::

- <simple-icons-umbraco/> **Umbraco** A .NET Content Management System
- <logos-dotnet/> **.NET** Microsoft development platform (mostly C#)


---
layout: image
image: /images/meetup-desc.png
backgroundSize: contain
---

<!--
"The people platform where interests become friendships."

[Awkward expression]

Ahh, maybe not...

I like to describe Meetups as like **mini-conferences**...
-->

---
layout: image-right
image: /images/rich-talks-cropped.jpg
---

# <solar-map-point-favourite-bold-duotone/> Your Friendly Neighbourhood Meetup

Like a mini-conference that's free to attend!

- <solar-hand-shake-bold-duotone/> Socializing
- <solar-presentation-graph-bold-duotone/> Tech Talks
- <solar-info-square-bold-duotone/> News
- <ph-pizza-duotone/> Refreshments

<!--

I like to describe Meetups as like **mini-conferences** that are **free** to attend. In fact, meetups often contain the **same talks** as at conferences

A meetup will usually involve an element of **socializing**, some **tech talks**, **news** about the subject area (Umbraco in our case) and some **refreshments** (usually pizza).
-->

---
layout: cover
---

# <ph-pizza-duotone/> Pizza as Professional Development

<p style="font-size: 2em; text-align:center; margin-top:2em;" v-click>
<ph-pizza-duotone/> + <solar-user-rounded-bold-duotone/> = <solar-lightbulb-bolt-line-duotone/> 
</p>

<!--
My first argument involves using Pizza as a **Professional Development** tool

Because what happens when your team spends **work time eating pizza** with **strangers**?[Click]

They come back with **solutions**, **shortcuts**, and a **spark** you can’t buy in a training budget.

I'm here to show you why meetups work, backed by research as well as my own experience.

The problems can all start by working inside the **bubble of your team**.
-->

---
layout: icons-header
---

# <solar-circle-top-up-bold-duotone/> Breaking out the bubble

:: icons ::

- <solar-wheel-bold-duotone/> Reinventing the wheel
- <gravity-ui-snail/> Slow adoption of new practices
- <solar-confounded-square-bold-duotone/> Technical debt accumulating quietly
- <material-symbols-verified-off-rounded/> Risky decisions made without external validation

[Pop!]{v-click .pow}

<!--
Teams operate in closed loops: **same codebase, same colleagues, same assumptions**.

Which can lead to **Reinventing the wheel**, **Slow adoption of new practices**, **Technical debt** accumulating quietly and Risky decisions made **without external validation**

So we need to burst that bubble [Click]
-->

---
layout: image
image: /images/jonathan-shares.webp
---

[💡]{v-click .pow}

<!--
This was a photo taken at one of our **recent meetups** where Jonathan shared a project he'd been working on recently. I think **everyone** (audience and speaker!) **took something away** from that session! [Click]
Whether it was a previously unknown Umbraco **feature**, an **architecture** technique or tips for using **Visual Studio** (or just that unrestrained Jonathan can talk for hours about local councils!)

But that's anecdotal, let's look at the numbers...
  -->

---
layout: icons-header
cols: 2
---

# <solar-pie-chart-2-bold-duotone/> Show me the statistics!

::icons::

<v-clicks>

- [80]{.pct} acquired information from a meeting that they later followed up
- [69]{.pct} obtained knowledge that allowed them to make improvements to their practice
- [45]{.pct} obtained knowledge that solved a technical problem they had
- [62]{.pct} like to ask questions tailored to them

</v-clicks>

[Holy data, Batman!]{v-click .pow}

::footer::

Ingram, C., & Drachen, A. (2020). *How do Software Professionals Use Local Informal Meetups?*

<!--
Let me show you some statistics from this paper by **Ingram and Drachen** in 2020.

- [Click] 80% acquired information from a meeting that they later followed up
- [Click] 69% obtained knowledge that allowed them to make improvements to their practice
- [Click] 45% obtained knowledge that solved a technical problem they *already* had (that's free problem-solving!)
- [Click] 62% like to ask questions tailored to them (AKA tailored to their work)

[Click] On contibuting to open source a second study, by Hametsberger and Reinhardt (2006) says...
-->

---
layout: quote
---

We found participative practice, collective reflection and virtual experimentation processes to be explanatory with respect to knowledge-building

::cite::

Hemetsberger, A., & Reinhardt, C. (2006). *Learning and Knowledge-building in Open-source Communities: A Social-experiential Approach.*<br>
on contributing to open source

<!--
"We found participative practice, collective reflection and virtual experimentation processes to be explanatory with respect to knowledge-building"

Simplified: **Contributing** to open source communities, **receiving feedback** and **trying new things** **increased knowledge**
-->

---
layout: quote
---

it’s an opportunity to \[...\] come back with strategies that make a real difference for your team and organisation

::cite::

Carl Sargunar, DDD South West Conference Organiser<br>
on Codegarden conference

<!--
Bearing in mind I'm saying meetups are **like mini-conferences**, on the Codegarden conference, **Carl Sargunar**, DDD South West Conference Organiser says

"it’s an opportunity to come back with strategies that make a real difference for your team and organisation"

But Carl isn't alone...
-->

---
layout: quote
---

If you \[...\] want to grow in your role, this is the place to learn, connect, and be inspired

::cite::

Joke Van Hamme, CEO at 3SIGN and Team Lead at AGConsult<br>
on Codegarden conference

<!--
Another one on Codegarden, Joke Van Hamme, CEO at 3SIGN and Team Lead at AGConsult says:

"If you want to grow in your role, this is the place to learn, connect, and be inspired"

But community is more than just a personal development opportunity...
 -->

---
layout: cover
---

# <solar-water-bold-duotone/> Don\'t let the <ins>open</ins> source run dry

Contibuting to open source strengthens your business

<!--
...contibuting to open source strengthens your business
-->

---
layout: icons-header
cols: 4
---

# <solar-water-bold-duotone/> Don\'t let the <ins>open</ins> source run dry

::icons::

<v-clicks>

- <solar-users-group-two-rounded-bold-duotone/> Open source isn't "free"
- <solar-hand-heart-bold-duotone/> Not just the "ethical" argument
- <solar-dumbbell-small-bold-duotone/> Strengthens the tools you depends on
- <solar-like-bold-duotone/> Reduces long‑term risk

</v-clicks>
<!--
Open source **isn't "free"**, it's a **shared responsibility**,[Click] and I don't mean that as in the **"ethical" argument**.[Click] It's not just you *should* contribute back *because* its open source, there are **business cases** too.

Contributing strengthens the **tools your business depends on**[Click] and supporting maintainers **reduces your long-term risk**.[Click]

I chatted to **Rich McCloskey**, Managing Director at True and he put it very nicely...
-->

---
layout: image
image: /images/jonathan-bean-tb1JFTlse20-unsplash.jpg
---

<!-- We can’t keep draining from a pool and expect it to remain full

::cite::

Rich McCloskey, Managing Director at True<br>
on open source communities -->

<!--
"We can’t keep draining from a pool and expect it to remain full"

We have to refill the reservoir before we continue draining water from it. -->

---
layout: cover
---

# <solar-users-group-rounded-bold-duotone/> Why Superheroes Want Sidekicks

How community can keep your team happier and healthier

<!--
Another strength of community is its ability to support the people in it.
-->

---
layout: icons-header
---

# <solar-users-group-rounded-bold-duotone/> Why Superheroes Want Sidekicks


::icons::

<v-clicks>

- <solar-chat-square-check-bold-duotone/> A place to share
- <solar-verified-check-bold-duotone/> A sense of identity and belonging
- <solar-square-academic-cap-2-bold-duotone/> Opportunities to teach, mentor, and feel valued
- <solar-users-group-two-rounded-bold-duotone/> Reduces isolation
- <solar-question-square-bold-duotone/> Safe space to ask “silly” questions

</v-clicks>

<!--

A community can provide many benefits to employees.[Click]

A place to share **wins, frustrations, and "is it just me?"** moments[Click]

A sense of **identity** and **belonging** beyond their job title or company[Click]

Opportunities to **teach, mentor**, and feel valued where these may not be available in a commercial setting[Click]

Reduces **isolation**, especially in remote/hybrid teams[Click]

Provides a **safe space to** ask "silly" questions without feeling you're being judged by more senior team members and affecting promotion prospects

This also came up in my discussion with Rich...
-->

---
layout: quote
---

\[Developers\] want to be involved in the community

::cite::

Rich McCloskey, Managing Director at True<br>
on open source communities

<!--
His team of **"Developers want to be involved in the community"**

And that study from earlier also had a lot to say about this...
-->

---
layout: icons-header
---

# <solar-pie-chart-2-bold-duotone/> Show me *more* statistics!

::icons::

<v-clicks>

- [68]{.pct} find talking to other technologists reassuring
- [59]{.pct} say it's important to feel part of a community
- [57]{.pct} attend to find friends with shared interests

</v-clicks>

<small>Ingram, C., & Drachen, A. (2020). *How do Software Professionals Use Local Informal Meetups?*</small>

<!--

[Click] **68% find talking to other technologists reassuring**

[Click] **59% say it's important to feel part of a community**

[Click] **57% attend to find friends with shared interests** - easy to forget that for some developers coding is a hobby and interest beyond just work

Those numbers actually seem quite low to me, but the paper clarified...
-->

---
layout: quote
---

Almost every interviewee made comments about the importance of socialising, making friends and
establishing a rapport

::cite::

Ingram, C., & Drachen, A. (2020). 

*How do Software Professionals Use Local Informal Meetups?*

<!--
"Almost every interviewee made comments about the importance of socialising, making friends and establishing a rapport"

To take our compassionate hats of for a minute...
-->

---
layout: icons
---

Happy employees benefits business too:

- <solar-stopwatch-play-bold-duotone/> Higher retention
- <solar-hand-money-line-duotone/> Feel valued
- <solar-emoji-funny-circle-bold-duotone/> Burnout

<!--
...happy employees benefits business directly:

**Higher retention**, people stay where they feel connected

Employees place a **higher value on an employer who supports** what they want to do and if taking part in a community is **what they want** to do and they're **supported** in that they'll **value that employer** more

These benefits can aloso help reduce then risk of **burnout**.

**Mitchell Nortje (Nor-kya)** wrote a fantastic article about his experience at Umbraco Spark and had this to say about burnout...
-->

---
layout: quote
---

Community is not a cure for burnout, but it is a reminder that your enthusiasm was never really gone.

::cite::

Mitchell Nortje, Senior Software Developer at Spinbox<br>
[Finding my Spark through Community](https://www.linkedin.com/pulse/finding-my-spark-through-community-spinbox-digital-q5sme/)

<!-- 
"Community is not a cure for burnout, but it is a reminder that your enthusiasm was never really gone."

And another quote from Rich, when talking about Umbraco Community training days...
 -->

---
layout: quote
---

\[Attending\] creates a positive effect more than the cost of a train ticket

::cite::

Rich McCloskey, Managing Director at True<br>
on Umbraco community training days

<!--"\[Attending\] creates a positive effect more than the cost of a train ticket" -->

---
layout: cover
---

# <solar-shield-star-bold-duotone/> Superpower your team
How to encourage community involvement in your team

<!--
Because open source communities can be so powerful to your team let's look at how you can **encourage** your team to get involved - if they want to!

To do that, first we need to know what might be **holding your team back**.
-->

---
layout: icons-header
---

# <solar-user-block-rounded-bold-duotone/> Community Kryptonite
Barriers to getting involved in communities

::icons::

<v-clicks>

- <solar-eye-closed-line-duotone/> Awareness
- <solar-map-point-add-bold-duotone/> Location
- <solar-clock-circle-bold-duotone/> Time
- <solar-hand-money-line-duotone/> Cost
- <solar-shield-cross-bold-duotone/> Employer hostility

</v-clicks>

<!--
It's entirely possible they **don't know** they can get involved or how to get involved [Click]

**Location** has an impact too, whether that's **travelling abroad** for conferences, to **another city** or even **into the city** if they work remote or office is located outside a city [Click]

Taking **time** out to attend a meetup or contribute when it's in a person's free time, whether they need to consider **child care** or simply **value their free time**[Click]

The **cost** of travelling to a meetup or extending childcare [Click]

Some employers can even be seen to be hostile towards contributing to open source.[Click]

The "they **might get recruited** at meetups" argument is a common one. In my experience, they almost certainly won't, (unless they're thinking of leaving anyway). I find it funny that having a strong **LinkedIn** presence is seen as a good thing - which is where the recruiters actually are - but attending meetups isn't!

But also, some contracts technically forbid contributing code to open source in a non-compete clause.
-->

---
layout: icons-header
---
# <solar-shield-star-bold-duotone/> Superpower your team

::icons::
<v-clicks>

- <solar-hand-stars-line-duotone/> Encourage participation
- <solar-clock-circle-bold-duotone/> Offer time back
- <solar-hand-money-line-duotone/> Cover expenses
- <solar-map-point-add-bold-duotone/> Host a meetup
- <solar-presentation-graph-bold-duotone/> Send to conferences
- <solar-dumbbell-large-bold-duotone/> Remove the pressure
- <solar-minimalistic-magnifer-bug-line-duotone/> Contribute code to open source

</v-clicks>

[KERPOW!]{v-click .pow}

<!--
How can we overcome some of these obstacles? [Click]

**Encourage** community participation: **let your team know its an option** and **how you can support them** and signal behaviour by **attending events yourself**! [Click]

Offer **time back** to attend meetups or **partial time** (head off early, come in late). If there's a daytime meetup you can allow attending **during work time**.
If it'd be usefull ask your local meetup to **host during work hours** (and offer to host it!)[Click]

Cover **bus or train fares** to attend meetups [Click]

**Host or sponsor** a meetup - a company's attendance always shoots up when its hosted at their office [Click]

Send **all seniorities** to **conferences**
I've heard employers say "I don't think we can justify sending a junior dev to a conference" - how on earth can they improve with that attitude?! [Click]

**Removing the pressure** can help an employee make the most of an event. Mitchell Nortje (Nor-kya) also mentioned this in his article:

**"If there is one piece of advice for businesses or managers is don’t put expectations or pressures on developers that go to these events. Let them enjoy the day! Or in my boss’s words, “Just go there and have fun”."**[Click]

Finally you can **make open source part of what you do** by allowing (and **making it clear** that you allow) **contributing back code** for **work projects in work hours**.

Like I said before, I had a contract for a company that worked with open source all the time that (strictly speaking) prohibited contributing! [Click]

I asked **Joe Kepley, CTO at Blend Interactive**, if he'd mind me quoting a video he made, but it was all too relevent so in the end I asked if I could just include the whole thing...

-->


---
layout: default
---

<SlidevVideo autoplay controls style="max-height: 96%">
  <!-- Anything that can go in an HTML video element. -->
  <source src="/video/joe-kepley-in-person.mp4" type="video/mp4" />
  <p>
    Your browser does not support videos. You may download it
    <a href="/video/joe-kepley-in-person.mp4">here</a>.
  </p>
</SlidevVideo>


Joe Kepley, Founder and CTO, Blend Interactive [on LinkedIn](https://www.linkedin.com/posts/joekepley_as-more-and-more-things-happen-online-people-ugcPost-7444522882975555584-6mXX/)

---
layout: icons-header
hide: true
---

# <solar-map-point-favourite-bold-duotone/> The Umbraco Community & Bristol

::icons::


<v-clicks>

- <solar-star-shine-bold-duotone/> **Home to Umbraco Spark and Umbraco's UK HQ!**
- <solar-chat-square-code-bold-duotone/> **Talks meetup every other month**
- <solar-chat-line-bold-duotone/> **"Social" meetup every other month**
- <solar-buildings-bold-duotone/> **In various offices** A company will host and provide pizza and drinks
- <solar-users-group-two-rounded-bold-duotone/> **10-20 attendees**
- <solar-user-id-bold-duotone/> **From various companies & agencies** Typically freelancers and employees from ~5 agencies

</v-clicks>

<v-click>

There are Umbraco Meetups all over the UK, and some virtual ones too. https://www.meetup.com/pro/umbraco/

</v-click>

<!--

-->

---
layout: icons-header
hide: true
---

# <solar-map-point-favourite-bold-duotone/> The .NET Community & Bristol

::icons::


<v-clicks>

- <ph-cow-duotone/> Home to DDD South West!
- <solar-chat-square-code-bold-duotone/> Meetup every month or two*
- <solar-buildings-bold-duotone/> Hosted in central Bristol
- <ph-pizza-duotone/> With pizza and drinks
- <solar-users-group-two-rounded-bold-duotone/> 20-50 attendees
- <solar-user-id-bold-duotone/> From various companies

</v-clicks>

<v-click>

https://meetup.com/dotnetsouthwest &middot; https://meetup.com/umbristol

It's not just .NET and not just here! There are tech Meetups all over the UK, and some virtual ones too. https://www.meetup.com

</v-click>

<!--

-->

---
hide: true
---

<style>
  ul:has(> li > .slidev-icon) {
    margin: 0;
    padding: 0;
    list-style: none;

    > li {
        margin: 0;

        .slidev-icon {
            color: var(--icon-color);
        }
    }
  }
  </style>

# <solar-link-square-bold-duotone/> In the same thematic universe . . .

- <solar-hand-heart-bold-duotone/> https://www.meetup.com/pro/umbraco/
- <solar-link-square-bold-duotone/> https://codegarden.umbraco.com/convince-your-boss/
- <solar-link-square-bold-duotone/> [Ingram, C., & Drachen, A. (2020). *How do Software Professionals Use Local Informal Meetups?*](https://pure.york.ac.uk/portal/en/publications/how-do-software-professionals-use-local-informal-meetups/)
- <solar-link-square-bold-duotone/> [Hemetsberger, A., & Reinhardt, C. (2006). *Learning and Knowledge-building in Open-source Communities: A Social-experiential Approach.*](https://journals.sagepub.com/doi/10.1177/1350507606063442) [(Free)](https://www.researchgate.net/publication/240281996_Learning_and_Knowledge-Building_in_Open-Source_Communities_A_Social-Experiential_Approach)

All these links available at https://joe.gl/ombek/links/devs-assemble

<!--
All the links from all the slides are available at joe.gl/ombek/links/devs-assemble, which is also on the next page...
-->

---
layout: bio
image: /images/Unicorn-transparent.png
name: Thank you!
---

- <logos-mastodon-icon /> [@joe@umbraco&#8239;community.social](https://umbracocommunity.social/joe)
- <logos-bluesky /> [@joe.gl](https://bsky.app/profile/joe.gl)
- <logos-linkedin-icon /> https://linkedin.com/in/glombek/

<br/>

- <solar-global-bold-duotone /> https://joe.gl/ombek
- <solar-link-square-bold-duotone/> https://joe.gl/ombek/links/devs-assemble

<!--
All the **links** from all the slides, as well as a **recording** of an earlier version of this talk are available at **joe.gl/ombek/links/devs-assemble**

Please do come and talk to me if you'd like to learn more, and thank you for listening.
-->
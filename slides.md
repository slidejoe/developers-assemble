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
- Explore how software communities can empower your development team.
- Community involvement is crucial for professional growth.
- How you can take advantage of that
-->

---
layout: bio
image: /images/Unicorn-transparent.png
tagline: I am where I am today because of software communities
---

- <solar-medal-ribbons-star-bold-duotone /> 5&times; Umbraco MVP
- <solar-presentation-graph-bold-duotone/> umBristol Meetup Organiser
- <solar-case-minimalistic-bold-duotone/> Senior Developer at Bump

<br />

- <logos-mastodon-icon /> [@joe@umbraco&#8239;community.social](https://umbracocommunity.social/joe)
- <logos-bluesky />  [@joe.gl](https://bsky.app/profile/joe.gl)

<!--
But who am I and why does what I say matter?

- I'm Joe Glombek.
- 5-time Umbraco MVP
- Organizer of the umBristol Meetup
- and a Senior Developer at Bump.
- I got here thanks to software communities
- I certianly have my current job because of my involvement in the community
-->

---
class: quote
---

# <solar-hand-heart-bold-duotone/> What is a software community?

<!-- The Umbraco Community is made up of over 200,000 talented ysers and passionate people who make sure Umbraco stays up-to-date, sturdy and level for you.

The Umbraco Community is a part of the Umbraco ecosystem, which through action, involvement and co-operation, makes Umbraco what it is today! -->

<blockquote class="big-quote">

  A group of people united by the shared purpose of developing, maintaining, extending, and promoting a specific body of open source software. \[...\]

  What unites them is their common vision for the open source software project—as well as the spirit of camaraderie and collective identity that participating in the community affords them.

  <cite class="big-quote-cite"> [The Open Source Way](https://guidebook.theopensourceway.org/getting-started/community-101) </cite>
</blockquote>

<!-- - Let's start by defining what a software community is.
- According to The Open Source Way, it's a group united by developing, maintaining, and promoting open source software.
- They share a common vision and camaraderie. -->

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

<!-- - Communities involve various activities.
- Like code contributions, online discussions, blogging, conferences, and meetups.
- For Umbraco, check out how to get involved at the community site. -->

---
layout: image-right
image: /images/rich-talks-cropped.jpg
---

# <solar-map-point-favourite-bold-duotone/> Your Friendly Neighbourhood Meetup

The <solar-user-bold-duotone style="color: var(--color-carolina-blue)" /> people platform.<br />
Where <solar-football-bold-duotone style="color: var(--color-bud-green)" /> interests<br />
become <solar-heart-bold-duotone style="color: var(--color-mandarin)" /> friendships.

<style>
  p {
    font-size: 2em;
  }  
</style>

<!--
According to Meetup.com
- The people platform where interests become friendships.
- But what does that actually mean?

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
- Meetups are like mini-conferences, and they're free to attend.
- Usually involve:
  - socializing
  - tech talks
  - news
  - refreshments
-->

---
layout: cover
---

# <ph-pizza-duotone/> Pizza as Professional Development

<!--
My first argument involves using Pizza as a Professional Development tool
-->

---
layout: icons-header
---

# <ph-pizza-duotone/> Pizza as Professional Development

::icons::

<v-clicks>

- <ph-pizza-duotone/> What happens when your team spends work time eating pizza with strangers?
- <solar-lightbulb-bolt-line-duotone/> They come back with solutions, shortcuts, and a spark you can’t buy in a training budget.

</v-clicks>

<!--
- [Click] What happens when your team spends work time eating pizza with strangers?
- [Click] They come back with solutions, shortcuts, and a spark you can’t buy in a training budget.
- This talk shows why meetups work, backed by research and my own experience.
-->

---
layout: icons-header
---

# <solar-circle-top-up-bold-duotone/> Breaking out the bubble

Teams operating in isolation can lead to:

:: icons ::

- <solar-wheel-bold-duotone/> Reinventing the wheel
- <gravity-ui-snail/> Slow adoption of new practices
- <solar-confounded-square-bold-duotone/> Technical debt accumulating quietly
- <material-symbols-verified-off-rounded/> Risky decisions made without external validation

[Pop!]{v-click .pow}

<!--
Teams operate in closed loops: same codebase, same colleagues, same assumptions.
- Can lead to:
- Reinventing the wheel
- Slow adoption of new practices
- Technical debt accumulating quietly
- Risky decisions made without external validation
-->

---
layout: image
image: /images/jonathan-shares.webp
---

[💡]{v-click .pow}

<!--
- Photo taken at one of our recent meetups
- Jonathan shared a project he'd been working on recently
- I think everyone (audience and speaker!) took something away from that session!
- Whether it was a
  - previously unknown Umbraco feature
  - an architecture technique
  - tips for using Visual Studio
  - (or just that unrestrained Jonathan can talk for hours about local councils!)

  But that's anecdotal...
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
let me show you some statistics from this paper by Ingram and Drachen in 2020.

- [Click] 80% acquired information from a meeting that they later followed up
- [Click] 69% obtained knowledge that allowed them to make improvements to their practice
- [Click] 45% obtained knowledge that solved a technical problem they *already* had (that's free problem-solving!)
- [Click] 62% like to ask questions tailored to them (AKA tailored to their work)
-->

---
layout: quote
---

We found participative practice, collective reflection and virtual experimentation processes to be explanatory with respect to knowledge-building

::cite::

Hemetsberger, A., & Reinhardt, C. (2006). *Learning and Knowledge-building in Open-source Communities: A Social-experiential Approach.*<br>
on contributing to open source

<!--
On contibuting to open source Hemetsberger and Reinhardt (2006) say:
- Read the quote: "We found participative practice, collective reflection and virtual experimentation processes to be explanatory with respect to knowledge-building"
- Simplified: Contributing to open source communities, receiving feedback and trying new things increased knowledge
-->

---
layout: quote
---

it’s an opportunity to \[...\] come back with strategies that make a real difference for your team and organisation

::cite::

Carl Sargunar, DDD South West Conference Organiser<br>
on Codegarden conference

<!--
On the Codegarden conference, Carl Sargunar, DDD South West Conference Organiser Says
 - Read the quote: "it’s an opportunity to come back with strategies that make a real difference for your team and organisation"
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
- Read the quote: "If you want to grow in your role, this is the place to learn, connect, and be inspired"
 -->

---
layout: cover
---

# <solar-water-bold-duotone/> Don\'t let the <ins>open</ins> source run dry

Contibuting to open source strengthens your business

<!--
But it's not just personal development.
-->

---
layout: icons-header
cols: 4
---

# <solar-water-bold-duotone/> Don\'t let the <ins>open</ins> source run dry

::icons::

- <solar-users-group-two-rounded-bold-duotone/> Open source isn't "free", it's shared.
- <solar-hand-heart-bold-duotone/> Not just the "ethical" argument.
- <solar-dumbbell-small-bold-duotone/> Contributing strengthens the tools your business depends on.
- <solar-like-bold-duotone/> Supporting maintainers reduces your long‑term risk.

<!--
- Open source isn't "free", it's shared.
- Not just the "ethical" argument
  - not just you *should* contribute back because its open source
  - there are business cases too
- Contributing strengthens the tools your business depends on.
- Supporting maintainers reduces your long-term risk. -->

---
layout: quote
---

We can’t keep draining from a pool and expect it to remain full

::cite::

Rich McCloskey, Managing Director at True<br>
on open source communities

<!--
I chatted to Rich McCloskey, Managing Director at True
- Read the quote: "We can’t keep draining from a pool and expect it to remain full"
- Refill what you rely on. -->

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

- <solar-chat-square-check-bold-duotone/> A place to share wins, frustrations, and “is it just me?” moments
- <solar-verified-check-bold-duotone/> A sense of identity and belonging beyond their job title or company
- <solar-square-academic-cap-2-bold-duotone/> Opportunities to teach, mentor, and feel valued
- <solar-users-group-two-rounded-bold-duotone/> Reduces isolation, especially in remote/hybrid teams
- <solar-question-square-bold-duotone/> Provides a safe space to ask “silly” questions

<!--

- A place to share wins, frustrations, and "is it just me?" moments
- A sense of identity and belonging beyond their job title or company
- Opportunities to teach, mentor, and feel valued (where these may not be available in a commercial setting)
- Reduces isolation, especially in remote/hybrid teams
- Provides a safe space to ask "silly" questions (without feeling you're being judged by more senior team members)
-->

---
layout: quote
---

\[Developers\] want to be involved in the community

::cite::

Rich McCloskey, Managing Director at True<br>
on open source communities

<!--
Something that came up in my chat with Rich is that his team of "Developers want to be involved in the community" 
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
In fact, in that same study:
- [Click] 68% find talking to other technologists reassuring
- [Click] 59% say it's important to feel part of a community
- [Click] 57% attend to find friends with shared interests - easy to forget that for some developers coding is a hobby and interest beyond just work
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
The study made specific reference to this "Almost every interviewee made comments about the importance of socialising, making friends and establishing a rapport"
-->

---
layout: icons
---

Happy employees benefits business too:

- <solar-stopwatch-play-bold-duotone/> Higher retention, people stay where they feel connected
- <solar-hand-money-line-duotone/> Employees place a higher value on an employer who supports what they want to do
- <solar-emoji-funny-circle-bold-duotone/> Reduce risk of burnout

<!--
To take our compassionate hats off for a moment, happy employees benefits business directly:
- Higher retention, people stay where they feel connected
- Employees place a higher value on an employer who supports what they want to do
  - and if taking part in a community is what they want to do 
  - and they're supported in that
  - they'll value that employer
- Reduce risk of burnout
-->

---
layout: quote
---

Community is not a cure for burnout, but it is a reminder that your enthusiasm was never really gone.

::cite::

Mitchell Nortje, Senior Software Developer at Spinbox<br>
[Finding my Spark through Community](https://www.linkedin.com/pulse/finding-my-spark-through-community-spinbox-digital-q5sme/)

<!--  -->

---
layout: quote
---

\[Attending\] creates a positive effect more than the cost of a train ticket

::cite::

Rich McCloskey, Managing Director at True<br>
on community training days

<!-- When talking about community training days, Rich also mentioned that "\[Attending\] creates a positive effect more than the cost of a train ticket" -->

---
layout: cover
---

# <solar-shield-star-bold-duotone/> Superpower your team
How to encourage community involvement in your team

<!--
- Because open source communities can be so powerful to yoir team
- let's look at how you can encourage your team to get involved
- if they want to!
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
What might be preventing people from being involved [Click]
- Entirely possible they don't know they can get involved
  - or how to get involved [Click]
- Location has an impact too
  - travelling abroad for conferences
  - to another city
  - or into the city if they work remote/office is located outside a city [Click]
- Taking time out to attend a meetup or contribute when it's in a person's free time
  - child care
  - valuing free time [Click]
- The cost of travelling to a meetup or extending childcare [Click]
- Some employers are seen to fear sending employees to a meetup
  - "might get recruited" (they almost certainly won't, unless they're thinking of leaving anyway, LinkedIn)
  - Some contracts technically forbid contributing to open source in a non-compete clause
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
- <solar-minimalistic-magnifer-bug-line-duotone/> Contribute to open source

</v-clicks>

[KERPOW!]{v-click .pow}

<!--
How can we overcome some of these obstacles? [Click]
- Encourage community participation
  - Let your team know its an option and how you can support them
  - Attend yourself! [Click]
- Offer time back to attend meetups
  - or partial time (head off early, come in late)
  - or allow atteding meetups during work time (lunchtime virtual)
  - ask your local meetup to host during work hours (and offer to host it!)[Click]
- Cover bus or train fares to attend meetups [Click]
- Host or sponsor a meetup - a company's attendance always shoots up when its hosted at their office [Click]
- Send **all seniorities** to conferences
  - "I don't think we can justify sending a junior dev to a conference" - how will they improve?! [Click]
- Remove the pressure
  - "If there is one piece of advice for businesses or managers is don’t put expectations or pressures on developers that go to these events. Let them enjoy the day! Or in my boss’s words, “Just go there and have fun”." - Mitchell Nortje[Click]
- Make open source what you do
  - I had a contract for a company that worked with open source all the time that (strictly speaking) prohibited contributing!
  - Allow contributing back code for work projects in work hours
-->


---
layout: icons-header
---

# <solar-map-point-favourite-bold-duotone/> The Umbraco Community & Bristol

::icons::


<v-clicks>

- <solar-star-shine-bold-duotone/> **Home to Umbraco Spark and Umbraco's UK HQ!**
- <solar-chat-square-code-bold-duotone/> **Talks meetup every other month**
- <solar-chat-line-bold-duotone/> **Social meetup every other month**
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

- <solar-link-square-bold-duotone/> https://codegarden.umbraco.com/convince-your-boss/
- <solar-link-square-bold-duotone/> [Ingram, C., & Drachen, A. (2020). *How do Software Professionals Use Local Informal Meetups?*](https://pure.york.ac.uk/portal/en/publications/how-do-software-professionals-use-local-informal-meetups/)
- <solar-link-square-bold-duotone/> [Hemetsberger, A., & Reinhardt, C. (2006). *Learning and Knowledge-building in Open-source Communities: A Social-experiential Approach.*](https://journals.sagepub.com/doi/10.1177/1350507606063442) [(Free)](https://www.researchgate.net/publication/240281996_Learning_and_Knowledge-Building_in_Open-Source_Communities_A_Social-Experiential_Approach)

All these links available at https://joe.gl/ombek/links/devs-assemble

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
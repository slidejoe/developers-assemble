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
duration: 10min
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

---
layout: image-right
image: /images/rich-talks-cropped.jpg
---

# <solar-map-point-favourite-bold-duotone/> Your Friendly Neighbourhood Meetup

Like a mini-conference thats free to attend!

- <solar-hand-shake-bold-duotone/> Socializing
- <solar-presentation-graph-bold-duotone/> Tech Talks
- <solar-info-square-bold-duotone/> News
- <ph-pizza-duotone/> Refreshments


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
this talk shows why meetups work, backed by research and your own experience
-->

---
layout: icons-header
---

# <solar-circle-top-up-bold-duotone/> Breaking out the bubble

Teams operating in isolation can lead  to:

:: icons ::

- <solar-wheel-bold-duotone/> Reinventing the wheel
- <gravity-ui-snail/> Slow adoption of new practices
- <solar-confounded-square-bold-duotone/> Technical debt accumulating quietly
- <material-symbols-verified-off-rounded/> Risky decisions made without external validation

[Pop!]{v-click .pow}

<!-- Teams operate in closed loops — same codebase, same colleagues, same assumptions. -->

---
layout: image
image: /images/jonathan-shares.webp
---

[💡]{v-click .pow}

<!-- Quick anecdote from Bristol Umbraco Meetup:
A moment where someone said “Wait, you can do that?” and changed their approach the next day. -->

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

---
layout: quote
---

We found participative practice, collective reflection and virtual experimentation processes to be explanatory with respect to knowledge-building

::cite::

Hemetsberger, A., & Reinhardt, C. (2006). *Learning and Knowledge-building in Open-source Communities: A Social-experiential Approach.*<br>
on contributing to open source

---
layout: quote
---

it’s an opportunity to \[...\] come back with strategies that make a real difference for your team and organisation

::cite::

Carl Sargunar, DDD South West Conference Organiser<br>
on Codegarden conference

---
layout: quote
---

If you \[...\] want to grow in your role, this is the place to learn, connect, and be inspired

::cite::

Joke Van Hamme, CEO at 3SIGN and Team Lead at AGConsult<br>
on Codegarden conference

---
layout: icons-header
cols: 4
---

# <solar-water-bold-duotone/> Don\'t let the <ins>open</ins> source run dry

::icons::

- <solar-users-group-two-rounded-bold-duotone/> Open source isn’t “free” — it’s shared.
- <solar-hand-heart-bold-duotone/> Not just the "ethical" argument.
- <solar-dumbbell-small-bold-duotone/> Contributing strengthens the tools your business depends on.
- <solar-like-bold-duotone/> Supporting maintainers reduces your long‑term risk.

---
layout: quote
---

We can’t keep draining from a pool and expect it to remain full

::cite::

Rich McCloskey, Managing Director at True<br>
on open source communities

<!--
Refill What You Rely On
-->

---
layout: icons-header
---

# <solar-users-group-rounded-bold-duotone/> Why Superheroes Want Sidekicks


::icons::

- <solar-chat-square-check-bold-duotone/> A place to share wins, frustrations, and “is it just me?” moments
- <solar-verified-check-bold-duotone/> A sense of identity and belonging beyond their job title or company
- <solar-square-academic-cap-2-bold-duotone/> Opportunities to teach, mentor, and feel valued
- <solar-users-group-two-rounded-bold-duotone/> Reduces isolation — especially in remote/hybrid teams
- <solar-question-square-bold-duotone/> Provides a safe space to ask “silly” questions

---
layout: quote
---

\[Developers\] want to be involved in the community

::cite::

Rich McCloskey, Managing Director at True<br>
on open source communities

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

---
layout: quote
---

Almost every interviewee made comments about the importance of socialising, making friends and
establishing a rapport

::cite::

Ingram, C., & Drachen, A. (2020). 

*How do Software Professionals Use Local Informal Meetups?*

---
layout: icons
---

Happy employees benefits business too:

- <solar-stopwatch-play-bold-duotone/> Higher retention — people stay where they feel connected
- <solar-emoji-funny-circle-bold-duotone/> Reduce risk of burnout
- <solar-hand-money-line-duotone/> Employees place a higher value on an employer who supports what they want to do

---
layout: quote
---

\[Attending\] creates a positive effect more than the cost of a train ticket

::cite::

Rich McCloskey, Managing Director at True<br>
on community training days

---

# <solar-map-point-favourite-bold-duotone/> The Umbraco Community & Bristol

---
layout: icons-header
---

# <solar-user-block-rounded-bold-duotone/> Barriers to community

::icons::

<v-clicks>

- <solar-eye-closed-line-duotone/> Awareness
- <solar-map-point-add-bold-duotone/> Location
- <solar-clock-circle-bold-duotone/> Time
- <solar-hand-money-line-duotone/> Cost
- <solar-shield-cross-bold-duotone/> Employer hostility

</v-clicks>

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
- <solar-minimalistic-magnifer-bug-line-duotone/> Contribute to open source

</v-clicks>

[KERPOW!]{v-click .pow}

<!--
- Encourage community participation
- Offer time back to attend meetups
- Cover bus or train fares to attend meetups
- Host or sponsor a meetup - a company's attendance always shoots up when its hosted at their office
- Send **all seniorities** to conferences "I don't think we can justify sending a junior dev to a conference" - how will they improve?!
- Make open source what you do - I had a contract for a company that worked with open source all the time that (strictly speaking) prohibited contributing!
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
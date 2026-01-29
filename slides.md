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

# What is a software community?

---

# What is a meetup?

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
---

# Show me the statistics!

::icons::

<v-clicks>

- [80]{.pct} acquired information from a meeting that they later followed up
- [69]{.pct} obtained knowledge that allowed them to make improvements to their practice
- [45]{.pct} obtained knowledge that solved a technical problem they had
- [68]{.pct} find talking to other technologists reassuring
- [62]{.pct} like to ask questions tailored to them

</v-clicks>

[Holy data, Batman!]{v-click .pow}

https://pure.york.ac.uk/portal/en/publications/how-do-software-professionals-use-local-informal-meetups/

---
layout: quote
---

it’s an opportunity to \[...\] come back with strategies that make a real difference for your team and organisation

::cite::

Carl Sargunar on Codegarden conference

---
layout: quote
---

If you \[...\] want to grow in your role, this is the place to learn, connect, and be inspired

::cite::

Joke Van Hamme on Codegarden conference

---

# The Umbraco Community & umBristol

---

# Barriers to attending meetups

---
layout: icons-header
---
# Superpower your team

::icons::
- <solar-hand-stars-line-duotone/> Encourage participation
- <solar-clock-circle-bold-duotone/> Offer time back
- <solar-hand-money-line-duotone/> Cover expenses
- <solar-map-point-add-bold-duotone/> Host a meetup
- <solar-presentation-graph-bold-duotone/> Send to conferences
- <solar-minimalistic-magnifer-bug-line-duotone/> Contribute to open source
<!-- - <ph-plant-duotone/> Watch your team grow -->

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
- <solar-link-square-bold-duotone/> https://pure.york.ac.uk/portal/en/publications/how-do-software-professionals-use-local-informal-meetups/

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
- <solar-link-square-bold-duotone/> https://joe.gl/ombek/links/t4s
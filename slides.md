---
theme: apple-basic
title: Agentic AI Melbourne — November 2026
info: |
  MC slides for Agentic AI Melbourne, 5 November 2026.
  Licensed under Creative Commons Attribution 4.0 International.
author: Ryan Djurovich
colorSchema: light
exportFilename: agentic-ai-melbourne-november-2026
transition: slide-left
mdc: true
---

# Win a conference ticket

<div class="qr-layout">
  <div>
    <img class="outlook-title" src="/conferences/outlook-ai-wordmark.png" alt="Outlook: AI" />
    <p><strong>2 tickets to win · Valued at $600 each</strong></p>
    <p>Thursday 12 November 2026<br />Collins Square Events Centre<br />Docklands, Melbourne</p>
    <a href="https://theoutlook.io/events/outlook-ai">Conference details → theoutlook.io</a>
  </div>
  <div class="conference-qr">
    <ProjectQr value="https://docs.google.com/forms/d/e/1FAIpQLScSI5oXBLl56lDNj3B0C12GOPQ80cxCmxBDA-NfH_3omIvuDg/viewform?usp=publish-editor" :size="260" />
    <span>Scan to enter the competition</span>
  </div>
</div>

<!--
We're giving away two tickets to Outlook: AI, valued at $600 each, on Thursday 12 November at Collins Square Events Centre in Docklands, Melbourne.

Scan the QR code and complete the form for your chance to win.
-->

---

<div class="hero hero-with-image">
  <div class="eyebrow">Agentic AI Melbourne · November 2026</div>
  <h1 style="padding-top: 4rem">G'Day</h1>
  <div class="hero-meta">
    <span>5 November 2026</span>
    <span>Iress · Melbourne</span>
  </div>
</div>

<div class="hero-art">
  <img src="/tech-trio-555-collins-st.png" alt="Three AI mascots using laptops outside 555 Collins Street, Melbourne" />
</div>

<!--
G'day everyone, and welcome to Agentic AI Melbourne.

I'm Gajan Kugamoorthy, one of the AAIF community event organisers here in Melbourne, and I'll be your MC tonight.

Thank you for making the time to be here.

Before we get into the talks, I want to give a little context about this community, why we've brought this room together, and how we hope tonight will work.

First, I just want to call out that our aim for this event is progress over perfection. This is a new community and, and we're hoping to learn from tonight. 

So if you have feedback after tonight, please let us know. And of course, we'll be asking for it!
-->

---

# What is the AAIF?

<p class="text-md !leading-[1.4] pt-2">The Agentic AI Foundation is the Linux Foundation’s neutral home for open standards and projects that power AI agents.</p>

<div class="foundation-map">
  <div class="foundation-root logo-node">
    <img src="/logos/linux-foundation.svg" alt="The Linux Foundation" />
  </div>
  <div class="foundation-branches">
    <div class="foundation-lane cloud-native-lane">
      <div class="foundation-label">Cloud native ecosystem</div>
      <div class="logo-node foundation-node">
        <img src="/logos/cncf.svg" alt="Cloud Native Computing Foundation" />
      </div>
      <div class="map-arrow">↓</div>
      <div class="ecosystem-projects">
        <div class="logo-node project-node">
          <img src="/logos/kubernetes.svg" alt="Kubernetes" />
        </div>
        <div class="logo-node project-node">
          <img src="/logos/cilium.svg" alt="Cilium" />
        </div>
        <div class="logo-node project-node">
          <img src="/logos/flux.svg" alt="Flux CD" />
        </div>
        <div class="logo-node project-node">
          <img src="/logos/fluent-bit.svg" alt="Fluent Bit" />
        </div>
      </div>
    </div>
    <div class="foundation-lane agentic-lane">
      <div class="foundation-label">Agentic AI ecosystem</div>
      <div class="logo-node foundation-node">
        <img src="/logos/aaif.svg" alt="Agentic AI Foundation" />
      </div>
      <div class="map-arrow">↓</div>
      <div class="ecosystem-projects">
        <div class="logo-node project-node mcp-node">
          <img src="/logos/mcp.svg" alt="Model Context Protocol" />
        </div>
        <div class="logo-node project-node agents-node">
          <img src="/logos/agents-md.png" alt="AGENTS.md" />
          <strong>AGENTS.md</strong>
        </div>
        <div class="logo-node project-node named-project-node">
          <img src="/logos/goose.png" alt="goose" />
          <strong>goose</strong>
        </div>
        <div class="logo-node project-node named-project-node">
          <img src="/logos/agentgateway.png" alt="agentgateway" />
          <strong>agentgateway</strong>
        </div>
      </div>
    </div>
  </div>
</div>

<!--
You've probably seen the AAIF name everywhere around this event, and because it's relatively new, there's a chance you might not have heard of it before or don't know anythign about it.

The AAIF is the Agentic AI Foundation. It is a non-profit, vendor-neutral foundation under the Linux Foundation.

This diagram shows the relationship relative to a more well known sibling, the CNCF. The Linux Foundation provides the umbrella and neutral governance. The CNCF is home to projects including Kubernetes, Cilium, Flux, and Fluent Bit. In a similar way, the AAIF is home to MCP, AGENTS.md, goose, and agentgateway.

For those not familiar, the CNCF became a neutral home for important cloud-native projects and helped an ecosystem form around Kubernetes. It's my understand that the AAIF aims to play a similar role for agentic AI: stewarding shared standards and open source infrastructure so the ecosystem can develop in the open.
-->

---

# Who is in the room?

<div class="audience-grid">
  <div class="audience-card">
    <div class="audience-number">01</div>
    <strong>Engineers</strong>
    <p>Software experience, demonstrated use of AI agents, and a habit of building things.</p>
  </div>
  <div class="audience-card accent-card">
    <div class="audience-number">02</div>
    <strong>Builders</strong>
    <p>Different background, exceptional use of AI agents, and something real to show for it.</p>
  </div>
</div>

<p class="text-center pt-4 !leading-10">
Our goal for tonight:<br /><strong>Bring people together who are building with AI agents.</strong>
</p>

<!--
As you all know, this event required registration which needed approval.

Every registration was hand reviewed, because this event is deliberately for engineers and builders.

Roughly, our entry requirements were one of two things.

First: engineers — people with a history of work as a developer or software engineer, who also demonstrate that they're using AI agents and building things.

Or second: builders — people who might not have that traditional work history, but who demonstrate exceptional use of AI agents to build something.

The common thread is merit. We want people in this room primarily because of what they're building, learning, and contributing — not their title, their employer, or the size of their following.
-->

---

# What do expect of you?

<div class="expectation-grid">
  <div class="expectation-card kindness-card">
    <div class="expectation-heading"><span>01</span><strong>Kindness</strong></div>
    <div class="expectation-actions">
      <div><strong>Introduce yourself</strong><span>Start with hello.</span></div>
      <div><strong>Be friendly</strong><span>Assume good intent.</span></div>
      <div><strong>Welcome others</strong><span>Make room in the conversation.</span></div>
    </div>
  </div>
  <div class="expectation-card curiosity-card">
    <div class="expectation-heading"><span>02</span><strong>Curiosity</strong></div>
    <div class="expectation-actions">
      <div><strong>Ask questions</strong><span>Explore ideas together.</span></div>
      <div><strong>Share</strong><span>Offer what you know.</span></div>
      <div><strong>Learn</strong><span>Stay open to new answers.</span></div>
    </div>
  </div>
</div>

<!--
Now, there are two things we'd like to see from everyone here tonight: kindness and curiosity.

Kindness means introducing yourself to somebody you don't know, being friendly, and actively welcoming other people into the conversation.

Curiosity means asking questions in good faith, sharing what you know, and being ready to learn from the experience around you.

There is a huge range of experience in this room, and the field itself is moving incredibly quickly. None of us have all the answers.

So please learn generously and share generously. The conversations before, between, and after the talks are as important as what happens on stage.
-->

---

# Say hi to our event team

<div class="organiser-grid">
  <div class="organiser">
    <img src="/organisers/chris-rickard.png" alt="Chris Rickard" />
    <div class="organiser-details">
      <strong>Chris Rickard</strong>
      <a href="https://www.linkedin.com/in/chrickard/" target="_blank"><carbon-logo-linkedin />@chrickard</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/gajan-kugamoorthy.png" alt="Gajan Kugamoorthy" />
    <div class="organiser-details">
      <strong>Gajan Kugamoorthy</strong>
      <a href="https://www.linkedin.com/in/kgajananan/" target="_blank"><carbon-logo-linkedin />@kgajananan</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/iman-yusuf.png" alt="Iman Yusuf" />
    <div class="organiser-details">
      <strong>Iman Yusuf</strong>
      <a href="https://www.linkedin.com/in/imanyusuf/" target="_blank"><carbon-logo-linkedin />@imanyusuf</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/phil-nash.png" alt="Phil Nash" />
    <div class="organiser-details">
      <strong>Phil Nash</strong>
      <a href="https://www.linkedin.com/in/philnash/" target="_blank"><carbon-logo-linkedin />@philnash</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/prem-pillai.png" alt="Prem Pillai" />
    <div class="organiser-details">
      <strong>Prem Pillai</strong>
      <a href="https://www.linkedin.com/in/cloud-on-prem/" target="_blank"><carbon-logo-linkedin />@cloud-on-prem</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/rob-kenefeck.png" alt="Rob Kenefeck" />
    <div class="organiser-details">
      <strong>Rob Kenefeck</strong>
      <a href="https://www.linkedin.com/in/robkenefeck/" target="_blank"><carbon-logo-linkedin />@robkenefeck</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/ryan-djurovich.jpg" alt="Ryan Djurovich" />
    <div class="organiser-details">
      <strong>Ryan Djurovich</strong>
      <a href="https://www.linkedin.com/in/ryandjurovich/" target="_blank"><carbon-logo-linkedin />@ryandjurovich</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/dr-sam.png" alt="Dr Sam Donegan" />
    <div class="organiser-details">
      <strong>Dr Sam Donegan</strong>
      <a href="https://www.linkedin.com/in/samueldonegan/" target="_blank"><carbon-logo-linkedin />@samueldonegan</a>
    </div>
  </div>
  <div class="organiser">
    <img src="/organisers/yann-vigara.png" alt="Yann Vigara" />
    <div class="organiser-details">
      <strong>Yann Vigara</strong>
      <a href="https://www.linkedin.com/in/yvigara/" target="_blank"><carbon-logo-linkedin />@yvigara</a>
    </div>
  </div>
</div>

<!--
A quick introduction to the people who've signed up to be community organisers for this event.

They are Chris Rickard, Gajan Kugamoorthy, Iman Yusuf, Phil Nash, Prem Pillai, Rob Kenefeck, Ryan Djurovich, Dr Sam Donegan, and Yann Vigara.

Events like this take a surprising amount of work behind the scenes. Please say hello to us, and please tell us what would make the next one better.
-->

---

# Thank you to our sponsor

<div class="sponsor-grid single-sponsor">
  <div class="sponsor-group venue-sponsors">
    <span class="sponsor-label">Venue, food & drinks</span>
    <div class="sponsor-list">
      <a class="sponsor-logo" href="https://www.iress.com/"><img src="/sponsors/iress.svg" alt="Iress" /></a>
    </div>
  </div>
</div>

<!--
Tonight would not be possible without the support of Iress.

Thank you to Iress for providing tonight's venue, food, and drinks.

Their support gives this community a place to meet, learn, and share what we're building.

One ask for everyone: please be respectful of the venue and clean up after yourselves before you leave.
-->

---

# Tonight's line-up

<div class="agenda">
  <div class="agenda-item featured">
    <img class="agenda-speaker" src="/speakers/doug-english.jpeg" alt="Doug English" />
    <span class="agenda-kind">Main Talk</span><strong>Our Agentic Coding Journey With 200 Engineers</strong><span>Doug English · Co-Founder & CTO @ CultureAmp</span>
  </div>
  <div class="agenda-item">
    <img class="agenda-speaker" src="/speakers/ben-hudson.png" alt="Ben Hudson" />
    <span class="agenda-kind">Lightning<br />Talk</span><strong>Measuring User Value for MCP Servers</strong><span>Ben Hudson · Head of Open Source & Product Lead @ Atlan</span>
  </div>
  <div class="agenda-item">
    <img class="agenda-speaker" src="/speakers/scott-van-kalken.jpeg" alt="Scott van Kalken" />
    <span class="agenda-kind">Lightning<br />Talk</span><strong>How To Break A High Level Goal Into Executable Steps</strong><span>Scott van Kalken · Sr Solutions Engineer @ LaunchDarkly</span>
  </div>
  <div class="agenda-item">
    <img class="agenda-speaker" src="/speakers/jonathan-gomez.jpeg" alt="Jonathan Gomez" />
    <span class="agenda-kind">Lightning<br />Talk</span><strong>Growing A Software Factory</strong><span>Jonathan Gomez · Head of Data Platforms @ OneDigital</span>
  </div>
</div>

<div class="timeline"><span>Doors 5:30</span><i></i><span>Talks from 6:00</span><i></i><span>Social 8:30pm</span></div>

<!--
Here's our line-up for tonight.

Doug is giving our main talk, followed by lightning talks from Ben, Scott, and Jonathan.

Doug will share CultureAmp's agentic coding journey with 200 engineers.

Ben will cover measuring user value for MCP servers.

Scott will explain how to break a high level goal into executable steps.

And Jonathan will share lessons on growing a software factory.

Our after-event community social starts at 8:30pm.
-->

---
class: blank-slide
---

<!--
INTENTIONAL SECTION BREAK.

Leave this slide displayed during the talk programme if a neutral screen is needed.

The following slides are the outro section.
-->

---
class: closing-slide
---

# Thank you to our speakers

<div class="speaker-thanks">
  <div><strong>Doug English</strong><span>CultureAmp</span></div>
  <div><strong>Ben Hudson</strong><span>Atlan</span></div>
  <div><strong>Scott van Kalken</strong><span>LaunchDarkly</span></div>
  <div><strong>Jonathan Gomez</strong><span>OneDigital</span></div>
</div>

<div class="applause">One more round of applause.</div>

<!--
What a fantastic set of talks.

Please join me in thanking Doug, Ben, Scott, and Jonathan — for the preparation, the candour, and the ideas they shared with us tonight.

Speaking takes work. Sharing unfinished lessons and real failures takes courage. The quality of this community depends on people being willing to do both.

Let's give all four speakers one more round of applause.
-->

---
class: closing-slide
---

# How did we do?

<div class="qr-layout">
  <div>
    <div class="statement">Help us make the next event better.</div>
    <p>Just 5 short questions.<br />It should take one minute.</p>
    <a style="display: inline-block; line-height: 1.4; overflow-wrap: anywhere;" href="https://docs.google.com/forms/d/e/1FAIpQLScg3QYGmUBnWaOaMw8E6cEwW-3AX0ZOKvkCv9gjKDXf57i3MA/viewform?usp=dialog">https://docs.google.com/forms/d/e/1FAIpQLScg3QYGmUBnWaOaMw8E6cEwW-3AX0ZOKvkCv9gjKDXf57i3MA/viewform?usp=dialog</a>
  </div>
  <ProjectQr value="https://docs.google.com/forms/d/e/1FAIpQLScg3QYGmUBnWaOaMw8E6cEwW-3AX0ZOKvkCv9gjKDXf57i3MA/viewform?usp=dialog" :size="260" />
</div>

<!--
Before we wrap up, we'd really value your feedback on tonight's event.

It's just five short questions and should take one minute. Please scan the QR code and let us know what worked and what we could make better next time.
-->

---
class: closing-slide
---

# What are you building?

<div class="qr-layout">
  <div>
    <div class="statement">Speak at our next event.</div>
    <p>Practical lessons. Honest failures.<br />Things that other builders can use.</p>
    <a href="https://forms.gle/yeyvhsizE1f6oqAX8">forms.gle/yeyvhsizE1f6oqAX8</a>
  </div>
  <ProjectQr value="https://forms.gle/yeyvhsizE1f6oqAX8" :size="260" />
</div>

<!--
With that said, we're a new event and we're looking to build our list of potential speakers.

If you're building something interesting, learning something the hard way, or have a practical technique others can use, we'd love to hear from you.

You do not need a polished keynote. In fact, practical lessons and honest failures are exactly what we want.

So please scan the QR code to submit to our call for papers. If you're unsure whether an idea is ready, come and talk to us tonight.
-->

---
class: closing-slide
---

# Next month

<div class="qr-layout">
  <div>
    <div class="statement">Save the date.</div>
    <p class="event-date">Thursday 3 December 2026</p>
    <a href="https://luma.com/30lmni6n">luma.com/30lmni6n</a>
    <p>Follow the Melbourne community Luma page<br />to be notified of all future events.</p>
    <a href="https://aimelb.org">aimelb.org</a>
  </div>
  <ProjectQr value="https://luma.com/30lmni6n" :size="260" />
</div>

<!--
Our next Agentic AI Melbourne event will be on Thursday, the third of December 2026.

Scan this QR code to open the event page, and follow the Melbourne community Luma page for future events.
-->

---
class: closing-slide
---

# Win a conference ticket

<div class="qr-layout">
  <div>
    <img class="outlook-title" src="/conferences/outlook-ai-wordmark.png" alt="Outlook: AI" />
    <p><strong>2 tickets to win · Valued at $600 each</strong></p>
    <p>Thursday 12 November 2026<br />Collins Square Events Centre<br />Docklands, Melbourne</p>
    <a href="https://theoutlook.io/events/outlook-ai">Conference details → theoutlook.io</a>
  </div>
  <div class="conference-qr">
    <ProjectQr value="https://docs.google.com/forms/d/e/1FAIpQLScSI5oXBLl56lDNj3B0C12GOPQ80cxCmxBDA-NfH_3omIvuDg/viewform?usp=publish-editor" :size="260" />
    <span>Scan to enter the competition</span>
  </div>
</div>

<!--
We're giving away two tickets to Outlook: AI, valued at $600 each, on Thursday 12 November at Collins Square Events Centre in Docklands, Melbourne.

Scan the QR code and complete the form for your chance to win.
-->

---
class: closing-slide
---

# Thank you to our sponsor

<div class="sponsor-grid single-sponsor outro-sponsors">
  <div class="sponsor-group venue-sponsors">
    <span class="sponsor-label">Venue, food & drinks</span>
    <div class="sponsor-list">
      <a class="sponsor-logo" href="https://www.iress.com/"><img src="/sponsors/iress.svg" alt="Iress" /></a>
    </div>
  </div>
</div>

<!--
Before we wrap up, one more thank you to our sponsor, Iress.

Thank you to Iress for the venue, food, and drinks.

Please help us leave the venue as we found it, and take a moment to thank our hosts if you see them tonight.
-->

---
class: closing-slide
---

# Keep the conversation going

<div class="social-callout">
  <div class="time-block"><strong>8:30pm</strong></div>
  <div class="social-copy">After-event<br /><span>community social</span></div>
</div>

<!--
[ANNOUNCE THE CONFIRMED SOCIAL VENUE AND DIRECTIONS VERBALLY]
-->

---
class: aaif-banner-slide
---

<img class="aaif-banner-content" src="./aaif-banner.svg" alt="Agentic AI Foundation Community Event" />

<a class="aaif-qr" href="https://aimelb.org" aria-label="Visit aimelb.org">
  <ProjectQr value="https://aimelb.org" :size="96" foreground="#fff" background="transparent" />
</a>

<!--
Leave this final banner on screen as people depart.
-->

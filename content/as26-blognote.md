---
title: "Orchestrating the AI Revolution: Airflow Summit 2026 Recap from Austin"
date: 2026-09-22T14:09:52-06:00
url: relive-airflow-summit-2026
draft: false
---

<img src="/images/blog/2026/note/1.jpg" class="img-fluid mx-auto d-block">
<br>

Airflow Summit 2026 has come to a close, and what a gathering it was. From August 31 to September 2, the Apache Airflow community came together at the Hyatt Regency in Austin, Texas, for three days that showed just how central orchestration has become in the AI era. This is our recap, and our thank you to everyone who made it happen.

### Three days in Austin

The scale set the tone right away:

* Three days of talks, workshops, and hallway conversations.
* Over 100 sessions across three tracks.
* A truly international community, with attendees traveling in from many countries.
* One clear theme, "Orchestrating the AI Revolution".

The theme was not just a banner; it was the thread running through almost every session. Airflow has always been the backbone of data engineering, but this year the conversation moved somewhere new: orchestration is now being treated as the foundation for AI agents and for the pipelines that feed data and memory to large language models.

<img src="/images/blog/2026/note/2.jpg" class="img-fluid mx-auto d-block">
<br>

### Open source, right in the middle of the AI wave

One of the clearest takeaways from the summit was how naturally Airflow has joined the technologies shaping this new era. This is not a legacy tool adding an "AI" sticker on top. The community has been shipping real support for AI and agents, in the open, including a new official package that connects Airflow directly with the major model providers.


### Orchestration as the backbone for AI agents

If one idea tied the whole summit together, it was this, orchestration is what makes AI agents reliable enough to actually run in production. Several speakers reached that same point from very different angles.

Vikram Koka, from Astronomer and a member of the Airflow project committee, set the frame in his keynote "The State of Airflow." His message was simple and reassuring, the classic strengths of Airflow, coordinating work, handling dependencies, recovering from failures, running at scale, matter even more once you add AI into the mix.

That idea got concrete in "Agentic Pipelines on Airflow: From Thesis to Production," which challenged a common assumption, the industry likes to treat agents and pipelines as opposites, and that framing is wrong. Most agent work, when you look closely, already has a pipeline shape, gather data, process each piece, put it together, check the result.

Constance Martineau's keynote, "Data Engineers Already Solved Agentic AI's Reliability Problem," offered one of the sharpest reframes of the event, the reliability issues everyone is discovering in AI agents are problems data engineers solved years ago, just under different names.

<img src="/images/blog/2026/note/3.jpg" class="img-fluid mx-auto d-block">
<br>

### The "harness" idea, and Astronomer's take

A word that came up again and again was harness. In the AI world, the harness is everything around the model, the tools it can use, the guardrails, the safety nets, the feedback loops, and all the things that decide whether a model can work reliably. The Airflow version of this idea is powerful, a pipeline becomes exactly that, every step is a named, logged, retryable task instead of a hidden move inside a black box.

Astronomer made this tangible with Otto, their data engineering agent built specifically for Airflow, along with a customer session on building self-healing pipelines with it. The message across their sessions and their booth was consistent, Airflow is becoming the operational backbone that connects data, AI, and the business.

<img src="/images/blog/2026/note/4.jpg" class="img-fluid mx-auto d-block">
<br>

### A look at where Airflow is heading

Some of the best moments came from the people steering Apache Airflow itself. Vikram Koka, from Astronomer and a member of the Airflow PMC, shared his read on where the project is going as it moves further into the AI era.

It was also a good reminder of how much of this still rests on open source and the community that keeps it moving. One perspective that stood out came from Jarek Potiuk, longtime PMC member and open-source contributor. His take on where a project like Airflow is heading was simple and very human, that what maintainers really bring is their intent, the judgment built up over years, and that more and more of the work is about writing that intent down in plain language so both people and AI agents can follow it.

<img src="/images/blog/2026/note/5.jpg" class="img-fluid mx-auto d-block">
<br>

### Austin, the food, and the community
Austin was the perfect host city. There is something about the Texan vibe, warm, relaxed, a little playful, that matched the community perfectly. Some of the best moments happened between sessions, over coffee, over really good local barbecue and Tex-Mex, and in the hallway conversations about pipeline design and agent guardrails. The welcome reception, presented by BMC, set the tone from the first night, bringing together people who, until then, had only known each other as GitHub handles or LinkedIn photos.

This is the part that matters most to us. Airflow Summit brought together data engineers, ML practitioners, and open-source contributors from all over the world, and the energy in the room was a reminder of how strong this community has become.

<img src="/images/blog/2026/note/6.jpg" class="img-fluid mx-auto d-block">
<br>

### Thank you to the people who made it happen
Events like this do not organize themselves. Our deepest thanks go to the entire organizing team, and to all the volunteers and community members whose work behind the scenes made everything run so smoothly- the logistics, the venue, and every small touch that made the experience what it was.

Thank you as well to the Apache Airflow project committee members and community representatives who showed up and gave their time so generously. It means a great deal to attendees to be able to talk directly with the people stewarding the project. A special thank you to the PMC members present, Amogh Desai, Elad Kalif, Jarek Potiuk, and Vikram Koka, along with the wider content committee who helped shape the program.

None of this would be possible without the sponsors, whose support and perspective made the program so rich. Our thanks go to Astronomer, Google Cloud, AWS, BMC, Broadcom, Databricks, IBM, Agor, Databricks, Dataflint, Datadog, Incredibuild, and Islo. They did not just show up to exhibit; they showed up to share where they think orchestration is going.


### Final thoughts

Airflow Summit 2026 leaves one clear conviction: orchestration is having its moment, and Apache Airflow is right at the heart of it. Whether it is feeding data and memory to language models, providing the harness that makes agents reliable, or coordinating whole teams of agents the way Agor imagines, the same idea holds: the future of AI will be orchestrated, and it will be built in the open.

Thank you to the organizers, the committee, the speakers, the sponsors, and every attendee who joined us in Austin. We are already looking forward to the next one.

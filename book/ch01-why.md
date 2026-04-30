# Chapter 1: Dispatching 19 Trucks and Losing Faith in the Cloud

*Part 1: Why I Had to Build My Own*

---

My alarm goes off at 4 a.m.

By 4:15 I already know it's going to be a hard day. One driver texted at midnight saying his truck is pulling right. Another one hasn't confirmed his first load. The plant in Harvest is running an hour behind because of a maintenance issue that got reported at 3 a.m. and somehow nobody told the customer. I know all of this before I've had coffee because I've been dispatching long enough that I run a mental model of 19 trucks and 19 drivers even when I'm sleeping.

That's the job. It never completely stops.

I'm Shane Brazelton. I live in Hazel Green, Alabama, about fifteen minutes from Huntsville. I run concrete dispatch — stone, dirt, sand, asphalt — for real construction jobs with real deadlines. If a concrete pour starts and my trucks aren't there, the whole site stops. That's money. That's my reputation. That's my drivers' paychecks.

I am telling you this because I want you to understand what "AI" means to me. It doesn't mean a chatbot for writing emails. It doesn't mean a demo someone built for a conference. It means: something that actually helps me run a more reliable operation, costs less than what I was already spending, and works when the internet goes down because sometimes out here, the internet goes down.

---

## The Cloud Promise

A few years ago I started paying for things.

Scheduling software. Weather apps. Route optimization tools. AI assistants. Each one came with a monthly bill and a promise that it would make my life easier. Some of them did, a little. Most of them added complexity in exchange for convenience. All of them had one thing in common: the moment I stopped paying, everything I'd built inside their system disappeared.

I don't own anything when I rent.

That took me too long to understand, but once I understood it I couldn't un-understand it. Every time I handed my operational data to a cloud service, I was renting the ability to use my own information. Every time a service changed its pricing — and they all change their pricing eventually — I had to decide whether to pay more, rebuild somewhere else, or just stop using it. The knowledge I'd accumulated in that tool, the workflows I'd configured, the history of my operation: all of it was held hostage to a subscription.

For a dispatcher running on narrow margins, that's not a feature. That's a trap.

---

## The Thing That Changed My Thinking

It was a Tuesday. I don't remember the exact date but I remember the feeling. I was on the phone with a customer whose loads were two hours late because the routing software I was paying for had gone offline during a maintenance window. No warning. I'm standing there trying to manually calculate which driver is closest to which plant, doing math in my head that software was supposed to be doing, and I'm paying for the privilege of being let down.

That was the day I started asking a different question.

I'd been asking: *Which service should I use?*

The new question was: *What if I just ran it myself?*

I didn't know how. I'm not a programmer. I never went to school for computers. I grew up watching my dad work hard with his hands and I work hard with mine — just with a radio and a spreadsheet instead of tools. But I knew that computers had gotten cheap enough and AI had gotten open enough that someone, somewhere, had figured out how to run it without paying cloud companies forever.

It turned out that someone was right. And it turned out to be simpler than I expected.

---

## What I Discovered

Ollama is free software. You download it, you run it, and it lets you run AI language models on your own hardware. Llama 3.2 is a model — it's the actual AI brain — and it's also free. Between the two of them, I could run a real, capable AI assistant on my own computer with no monthly bill, no data leaving my network, no dependency on someone else's servers staying up.

I put it on a Raspberry Pi 5. The Pi 5 is a small computer — about the size of a paperback book — that costs around $80. I added two NVMe storage drives and set them up in RAID, which means if one drive fails, I don't lose anything. Total cost: roughly $250 for the whole setup, hardware included.

That was it. That was the foundation.

From there I built:
- A dispatch intelligence system that knows my drivers, my plants, my regular customers
- Weather integration that flags bad conditions before I have to check
- Voice input so I can talk to it instead of type when I'm on the radio
- A scheduling assistant that syncs with Google Calendar and tells me conflicts before they happen

None of this costs me anything per month. All of it runs on a computer on my desk. When the internet goes down — and it does — my core system still works.

---

## Who This Chapter Is For

If you're reading this and you dispatch trucks, I'm glad you're here. But this book isn't just for dispatchers.

It's for anyone who runs something real — a crew, a shop, a household, a small business — and keeps paying cloud subscriptions for tools that feel like they should just be owned. It's for people who got told, over and over, that AI is complicated and expensive and you need experts for it. It's for the people who are about to lose Windows 10 security support and are staring at a crossroads: pay Microsoft, pay someone else, or figure out something better.

I don't have a CS degree. I have dispatch experience, five sons, and a stubborn belief that if something is worth building it's worth understanding. That's all you need to follow along.

The next chapter is about what "local AI" actually means in plain English — not a tech explanation, but a real one. Why it matters. What it protects. What it costs.

If November 16, 2025 is the day I write down as the breakthrough, the chapters that follow are the map of how I got there and where I went after.

Let's go.

---

*Next: [Chapter 2 — What Local AI Actually Means (and Why It Matters to You)](./ch02-local-ai.md)*

*Back: [Table of Contents](./outline.md)*

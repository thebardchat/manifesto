# Chapter 5: What Sobriety Taught Me About Designing Software

*Part 2: The Foundation*

---

I know exactly what I would have built before November 27, 2023.

A bar.

Not a metaphor. An actual bar. I understood bars. I understood what made them work — not from the outside, from the stool. The lighting is ambient and warm because fluorescents make you aware of time and time makes you want to leave. There are no clocks on the walls for the same reason. The music is at a specific tempo — not too fast, not too slow — because the right tempo keeps your body comfortable and your guard down. The seats are built for settling in, not sitting up. The bartender remembers your name and your drink because being remembered feels like being loved, and feeling loved makes you come back. The next round is always a little cheaper than leaving.

A bar is engineered. Every choice in it is a design decision made to keep you there, spending money, past the point where you would have chosen to leave on your own.

I know this because I was a very good customer.

---

## The Engineering Behind the Addiction

Here is the thing about getting sober that nobody tells you: you don't stop understanding how the trap works. You just stop falling into it.

I know the exact feeling a bar is designed to produce. The warmth. The belonging. The sense that the problems outside the door are smaller than the beer in your hand. I know that feeling the way a lock knows a key.

What I also now know — after November 27, 2023, after working to stay clear-eyed every single day — is that this engineering is not special to bars.

It is everywhere in software.

The infinite scroll was designed by someone who understood that stopping requires a decision and starting doesn't. Variable reward loops — the likes, the notifications, the "you have a new message" — were borrowed directly from slot machine psychology. The streak counter that makes you feel like you've lost something if you skip a day. The dark pattern that puts the cancel button three menus deep. The free trial that doesn't remind you it's ending.

All of it is the bar. The details are different. The design intention is identical: keep you there, past the point where you would have chosen to leave on your own.

Before November 27, 2023, I might have built something like that. I would have called it engagement. I would have called it product-market fit. I would have called it good business.

---

## The Constitutional Requirement

The ShaneBrain Constitution — Article I, Pillar 3 — reads:

> *Every tool in this ecosystem must reinforce clarity and health — never undermine it. No feature will be designed to exploit, addict, or manipulate users or the builder.*

That's not a preference. It's a governing law. And it has teeth because I know exactly what I'm legislating against.

What does it mean to build software that doesn't exploit?

It means no infinite scroll. If you've reached the end of the content, you've reached the end. The platform doesn't manufacture more to keep you scrolling.

It means no dark patterns. The exit is as easy to find as the entrance. The unsubscribe link is one click. The cancel option is on the first page.

It means no variable reward loops designed to manufacture anxiety. No streaks that punish you for living your life. No notifications engineered to create a feeling of loss if you don't respond immediately.

It means building time-awareness in. If someone has been using the platform for three hours, the platform knows. The bar removed the clocks. Sober design puts them back.

It means the crisis detection doesn't wait to be asked. If someone types words that signal they are not okay — hopelessness, self-harm, crisis — the system sees it, logs it, and responds. Not with engagement optimization. With real resources. The 988 number. A path toward help. A witness.

---

## What Sober Design Looks Like in Practice

The Angel Cloud crisis detection system watches for keywords. Not to flag users for advertisers. To protect them from the moment when they most need protecting. When the detection fires, it logs to a dedicated CrisisLog, it flags the conversation for review, it surfaces the National Suicide Prevention Lifeline — 988 — and the Crisis Text Line (text HOME to 741741). It doesn't optimize for session length in that moment. It optimizes for the person staying alive.

That's what sober design looks like.

The ShaneBrain dispatch tools are built with clear exit states — every workflow has an end. The voice interface doesn't keep you talking when the task is done. The local-first architecture means your data isn't being analyzed by someone building a profile of you to sell something. You're not the product. You're the operator.

None of this is complicated to build. What it requires is the decision — made before writing a line of code — that the goal of the software is not to maximize the time you spend inside it.

The bar wants your time. Sober design respects it.

---

## Why I'm Telling You This

I'm not writing this chapter to tell you to get sober. That's your business and I know better than anyone that no chapter in any book is what changes that.

I'm writing it because most software gets designed by people who have no particular reason to think hard about exploitation. Not because they're bad people. Because they've never sat on the stool and watched the engineering work on them from the inside.

I have. And I carry that with me into every design decision now.

When I write a feature, the question isn't just "does it work?" It's "does it respect the person using it?" Does it leave them clearer than when they came in? Does it give them back their time or take it? Does it tell the truth about what it's doing?

These are not philosophical questions for me. They are engineering requirements. They are in the constitution.

If you're building anything — software, a business, a system for your family — I'd encourage you to write your own version of Pillar 3 before you start. Because the bar is not the only thing you could accidentally build. It's just the most honest version of what happens when you don't decide what you're building against.

---

*Next: [Chapter 6 — PSB: Done Beats Perfect](./ch06-psb.md)*

*Previous: [Chapter 4 — Faith First](./ch04-faith.md)*

*Back: [Table of Contents](./outline.md)*

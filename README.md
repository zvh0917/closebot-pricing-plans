# ai chatbot appointment setter: how to pick one that actually books calls, what CloseBot charges, and which plan matches your lead volume

Most AI appointment setter demos are impressive for about eleven minutes. The agent greets the lead, asks two qualifying questions, offers a couple of time slots, and everyone in the room nods. Then it goes live on a real inbox, someone replies "how much is it tho" at 11:40pm, and the whole thing falls over.

The gap between a good demo and a working setter isn't the model. It's everything around it: whether the agent can see your calendar, whether it knows what happens when a booking fails, and whether you're being charged per message, per segment, or per "resolution" you can't define. This guide covers the mechanics that matter, then walks through what CloseBot actually does, what every one of its plans costs, and where it's the wrong tool.

## What an AI chatbot appointment setter is, in plain terms

A chatbot follows a decision tree. Someone types something the tree didn't anticipate, and the conversation dies in a button.

An AI appointment setter runs on a language model. It reads the reply, adapts, qualifies the lead through actual conversation, and puts a time on your calendar. Some tools do this over SMS, some over Instagram DMs, some over voice calls. CloseBot is in the text camp: it handles the conversations already flowing through your CRM's inboxes and books from there.

One expectation to kill early: the setter does not close. It qualifies and books. The close still happens on the call, with a human. Any vendor implying otherwise is selling you a story, not software.

## Four checks that decide whether it books anything

**Does it book inside the conversation, or hand over a link?** Plenty of tools collect a phone number and fire off a Calendly link. Every extra step between "interested" and "on the calendar" leaks leads. In-conversation booking, where the agent checks real availability and creates the event, is a different category of useful.

**Where does it live?** Channel-native setters plug straight into Instagram or WhatsApp. CRM-native setters sit on top of GoHighLevel, HubSpot, or a custom system and answer whatever channels are connected there. Both are legitimate; they're just not interchangeable. If your leads arrive as Instagram DMs and you have no CRM, a CRM-native agent means buying two products to do one job.

**What counts as a "message"?** This is where budgets quietly break. One vendor's message is one reply. Another counts tokens, so a single reply with a lot of instructions attached can drain several. Ask for the billing unit in writing before you commit.

**What happens when the model fails?** A primary provider outage, a calendar that doesn't respond, an answer the agent isn't confident about. Good products retry, tag the contact, or route to a fallback model. Bad products invent a discount code and apologise later.

## Where CloseBot sits in this picture

CloseBot is an agentic conversational AI built for lead qualification and booking, and it's aimed squarely at agencies and businesses already running a CRM. It connects natively to HighLevel, HubSpot, LeadConnector, and custom CRMs, and it can also run standalone through its own chat widget if you don't have a CRM.

You build agents with objectives rather than rigid scripts, wire them together in a drag-and-drop job flow, and attach personas that control tone, timing, and quirks like typos or emoji. Agents can update unlimited custom contact fields, pull from an uploaded knowledge library, read images, reply over email as well as SMS and chat, and route to a different LLM provider if the primary one fails. A "smart FAQ" flags you when the agent hits a question it can't answer rather than guessing.

The vendor's published numbers are 1M+ booked appointments and around 150,000 messages a day across 1,000+ agencies. Treat those as marketing figures, but they're at least consistent with a product that's been shipping for years. On G2 it holds 4.8 out of 5 across 175+ reviews, and the same review summaries list "limited customization," "difficult setup," and "complexity" among the recurring complaints. Both things can be true at once: powerful builder, real learning curve.

### How the booking step actually works

This is the part worth testing yourself. When a contact reaches a booking action, CloseBot pings the connected calendar, pulls availability, and offers slots the agent and the lead can agree on. You can point it at a calendar by name or by permanent calendar ID, which matters if you want one agent to book into different calendars depending on the conversation.

Time zones are handled in a specific order: the contact's time zone if it exists on their record, otherwise your source's time zone. If you take bookings from across the country, you need an objective before the booking step that collects and updates the contact's time zone. Skip it, and you'll be sending people to 6am appointments.

Two defaults to know about. Conversational rescheduling is **off** by default and has to be switched on in the job flow settings, which means an agent won't touch appointments it didn't create unless you enable it. And you can tag the contact when a booking fails, whether that's because the CRM didn't respond or the calendar had nothing open. That tag is how you build a follow-up path for the leads the agent couldn't place.

### What CloseBot won't do

- **No native Instagram or WhatsApp connection.** CloseBot answers the text channels inside your CRM. If Instagram is connected to your HighLevel Conversations inbox, it can reply there. If you don't run a CRM, that's a CRM purchase first.
- **No bring-your-own API key.** CloseBot manages model routing itself and blocks this on security grounds.
- **No refunds.** There's a free-forever plan and a 7-day trial on paid plans, but once you're billed, you're billed.
- **No voice.** It's text-based. Voice agents are a separate product category.
- **Business plans don't include rebilling or white labeling.** Those live on the Agency plan, which is the whole reason it exists.

## CloseBot pricing: every plan currently on the page

CloseBot splits into an all-inclusive business track and an agency track with rebilling, plus a custom Growth tier for compliance and volume. Here's the current lineup.

| Plan | Best for | What you get | Price | Billing | Get started |
| --- | --- | --- | --- | --- | --- |
| **Free** | Testing the builder, low lead volume, one-person operations | 1 agent, 1 user seat, 100 messages/month, 1 MB upload storage, unlimited account connections. No live chat support; job flows capped at 5 actions | $0 | Always free; overage at $0.08/message | [Start on the free plan](https://app.closebot.com/register?fpr=li87) |
| **Core (Business)** | Businesses qualifying and booking their own leads | Message costs included in the base price, 500 messages included, 15+ templates, human support, unlimited account connections, add-on users ($5/seat), add-on storage and agents | From $64/mo monthly; $53/mo on annual billing, billed as $640/yr | Monthly or annual, no contract | [See the Business plan](https://app.closebot.com/settings?tab=subscription&plan=business&toggle=monthly&fpr=li87) |
| **Core (Agency)** | Agencies building and reselling AI setters for clients | Unlimited agents across unlimited accounts, white-label client portal, rebill all costs, unlimited messages at $0.012/message rebillable, client wallets, $5 seats you can mark up | $397/mo monthly (around $331/mo equivalent on annual billing) | Monthly or annual, no contract | [See the Agency plan](https://app.closebot.com/settings?tab=subscription&plan=agency&toggle=monthly&fpr=li87) |
| **Growth** | Teams needing SLAs, HIPAA compliance, audits, or very high volume | 50+ templates, HIPAA compliance with signed BAAs, quarterly audits, 99.99% priority uptime, priority support | Custom quote | Contracted | [Talk to sales about Growth](https://app.closebot.com/a?fpr=li87) |

### The business track scales with your message ceiling

The $64 entry price covers 500 messages a month, and message costs are baked in rather than metered on top. Raising the ceiling raises the price and improves bulk pricing, and the slider on the plans page runs from 100 messages up to 100K+. A third-party review logged the business track around $84/mo at 1,000 messages, $109 at 2,000, $176 at 5,000, and into the hundreds at 20,000 and beyond. Volume pricing moves; check the live page before you budget from someone else's screenshot.

If you blow past your ceiling, overage is charged per message at a 2x rate drawn from your wallet. That's a safety net, not a punishment, but it's worth watching in a month where a campaign goes well.

Add-ons are separate line items: extra user seats run $5 each, extra storage runs roughly $0.10 to $3.00 per MB per month depending on how much you need, and additional agents for additional niches cost extra. Annual billing effectively bills ten months for twelve and unlocks the larger 50+ template library. The 1 MB of included storage is about 1,000 pages of text, so most businesses won't touch the storage line at all.

### The agency track is a different calculation

The Agency plan is $397/month, or roughly $331/month equivalent if you pay annually, and the flat rate per message drops to $0.012 with rebilling built in. You set your own markup. Clients top up a wallet that pays you through your Stripe account; you keep the difference between the marked-up rate and CloseBot's cost. Seats and storage can be marked up the same way.

Run the arithmetic on a realistic account. A client at 20,000 messages a month costs you $240 in message fees at $0.012. Bill that client at $0.05 a message and the same volume produces $1,000. That's the entire pitch, and it's why agency owners treat this plan as a product line rather than an expense. CloseBot's own comparison page lists agencies billing anywhere from $100 to $10k+ per month per client, which is a reminder that the margin is set by your offer, not by the software.

HIPAA doesn't come with it, though. Compliance lives on the Growth tier, and CloseBot is direct about that: no bring-your-own-key setups, signed BAAs on file, and compliance questions answered on the plans page rather than buried.

## Which plan actually fits you

If you're a single business with a few hundred conversations a month, the free plan is a real test environment, not a teaser: one agent, 100 messages, the full builder. Outgrow it, and the Core business plan at $64 with 500 included messages is the natural next step. Most small operations never need the agency tier.

If you're selling AI setting as a service, the agency plan pays for itself on one or two clients. Two clients at $500/month and you're past the base cost with margin left over. Below that, you're subsidising the plan out of your own pocket, and a business-tier plan with rebilling done manually would be cheaper.

Growth is a different conversation entirely. If you need HIPAA, quarterly audits, or an SLA, custom pricing is the norm in that segment, and the compliance work is the product.

## How it compares to the alternatives

Against native CRM AI, the honest comparison is billing model plus quality. CloseBot's published breakdown puts HighLevel's conversational AI at $0.02/message pay-as-you-go, or bundled into AI Employee at $97 per sub-account per month, with CloseBot at $0.012/message on the agency plan. Run 100,000 messages a month and the difference stops being academic. Whether the extra quality justifies it depends on your close rate, not on the price difference alone.

Against DM-native setters, architecture decides it. Tools like SetSmart and Appointwise are built to live directly on Instagram, WhatsApp, and Messenger, and they generally work without a CRM. Third-party reviews put Appointwise around $297/month and SetSmart around $97/month with 1,000 messages included, both of which are cheaper than CloseBot plus a CRM subscription if your leads only ever arrive as DMs. If your pipeline runs on forms, SMS, and a CRM inbox, CloseBot is the better shape.

If you need an agent that answers the phone, none of these replace a voice product. Voice AI is a separate purchase in every stack.

## A 7-day test that tells you something

Because CloseBot doesn't refund after billing, structure the trial so you never have to ask.

**Days 1 and 2:** build one agent with a single objective and attach it to a real calendar. Don't build three. The most common setup failure is a job flow doing too much.

**Day 3:** break it on purpose. Ask about pricing, ask for a time slot three weeks out, send an image, reply in a different language, answer "maybe" four times in a row. Note where it stalls and whether it flags the gap instead of inventing an answer.

**Day 4:** check the boring failure paths. If your CRM doesn't respond, does the booking failure tag fire? Is the contact's time zone set before the booking step? Turn on conversational rescheduling only if you actually want the agent touching existing appointments.

**Days 5 and 6:** measure messages per booked appointment, not bookings alone. The number that decides your bill is what a booking costs you in messages.

**Day 7:** compare that cost against your average deal value. A booking that costs you $4 in messages is trivial on a $3,000 job and fatal on a $40 one.

You can run all of this on the free plan plus a trial of the paid tier, which is exactly what the free-forever tier is for. 👉 [Start with the free plan and build a real agent](https://app.closebot.com/register?fpr=li87)

## FAQ

**Do I need a CRM to use CloseBot?**
In practice for most setups, yes. It connects to HighLevel, HubSpot, LeadConnector, and custom systems, and it answers the text channels inside them. There's a standalone option using CloseBot's own chat widget if you want booking on your website without a CRM, but the full omni-channel story runs through your CRM.

**Does it book appointments directly, or send a link?**
Directly. The booking action checks calendar availability and creates the event in the conversation. Availability is calculated from the contact's time zone when your CRM has it, otherwise your source time zone.

**Can it handle Instagram or WhatsApp DMs?**
Only through your CRM. CloseBot has no native Instagram or WhatsApp connection of its own, so those channels need to be wired into your CRM inbox first.

**What happens if I go over my message limit?**
On the free plan, overage runs $0.08 per message. On paid business plans you raise your ceiling, and anything above it is charged at a 2x per-message rate from your wallet. On the agency plan you're paying $0.012 per message and can pass it on.

**Is there a free trial?**
Two things, actually. A free plan capped at 100 messages a month with no credit card required, and a 7-day trial of any paid plan before billing starts. Refunds aren't offered, so the trial is where the testing happens.

**What's the cheapest way to start?**
Build on the free plan first. If your volume is genuinely under 100 conversations a month, you may never need to pay anything. If you're between 500 and a few thousand messages and you're booking your own leads, the Core business plan at $64 with 500 included messages is the realistic entry point. Agencies should look at the plan that gives them rebilling and white labeling rather than trying to scale a business plan into a client offer. 👉 [Compare the current plans and pick your tier](https://app.closebot.com/a?fpr=li87)

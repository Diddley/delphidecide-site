**Technology · 5 min read**
# AI Agents and the Temptation of Autopilot

A new phrase has entered the modern technology lexicon with suspicious speed: *agentic AI*.

Not long ago, most businesses were experimenting with AI as a kind of very clever assistant. It drafted emails, summarised documents, cleaned up copy, wrote bits of code, and answered questions in a remarkably polished tone. Now the ambition has expanded. We no longer want the machine merely to answer. We want it to *do*.

Book the meeting.
Compare the vendors.
Reorder the stock.
Reply to the customer.
Monitor the systems.
Escalate only if necessary.

In other words, we are moving from AI as adviser to AI as actor.

This is not a trivial shift. I say that as someone who has lived it. Years before "agentic" was a buzzword, I was responsible for decisioning at a lending business where our models approved or declined loans in real time. Every day, software took actions with real money attached — and my job was to decide exactly how much authority it had, and where that authority stopped. Most of what I believe about autonomous systems was learned there, not in a demo.

## From tool to proxy

A calculator does not decide what matters. A spreadsheet does not choose which trade-off is acceptable. Even a predictive model, left in its proper place, still sits one step removed from action. It informs a decision. Someone, somewhere, remains visibly accountable.

Agents blur that line.

An AI agent is, broadly speaking, a system that can pursue a goal across multiple steps with some degree of autonomy. It may gather information, use software tools, make intermediate choices, and take actions in sequence. The promise is obvious: less manual work, faster execution, lower operating cost, and the ability for small teams to perform like much larger ones.

The seduction is equally obvious: once a system appears competent across ten small decisions, it becomes tempting to trust it with the eleventh.

That is where things get interesting.

## Autonomy compounds both value and error

The appeal of automation has always been straightforward. If a task is repetitive, rules-based, and tedious, machines are usually better candidates than humans. They do not get bored, distracted, or resentful. They scale nicely. They are available at odd hours.

But autonomous systems introduce a different kind of risk. A bad answer is one thing. A bad action is another.

If a chatbot drafts an awkward customer email, a human can amend it. If an agent sends that email, promises a refund, updates the CRM, triggers a warehouse return, and logs the case as resolved — all incorrectly — the error has already spread through the organisation before anyone notices.

In lending, we understood this viscerally. A model that misjudges a loan application hasn't produced a wrong opinion; it has moved money. By the time a pattern of bad decisions is visible in the numbers, the decisions have already been made, at machine speed, hundreds of times.

Autonomy does not merely increase efficiency. It increases the radius of consequence.

One poor judgment, multiplied by speed and permission, becomes process.

## The demo is not the job

Part of the difficulty is that AI agents often look more reliable in demonstration than in production.

In a demo, the task is tidy. The tools are connected. The edge cases are politely absent. The success criterion is obvious. Everyone in the room wants the thing to work.

Real businesses are less cooperative. Customers are vague. Data is missing. Systems disagree. Exceptions pile up. Policies conflict. And a large proportion of useful work consists precisely in handling the awkward cases that do not fit the script.

The more freedom an agent has, the more opportunity reality has to embarrass it.

## Agency without judgment

There is also a conceptual problem. To act is not the same as to judge.

An agent may be able to complete a workflow. That does not mean it understands the significance of the workflow. It may optimise for the target it has been given while remaining oblivious to the surrounding human context.

A support agent told to minimise resolution time may rush cases closed.
A procurement agent told to reduce cost may favour the cheapest supplier while ignoring reputational risk.
A scheduling agent told to maximise utilisation may exhaust the very people it is meant to help coordinate.

These are not exotic failures. They are ordinary examples of Goodhart's Law in modern dress: when a measure becomes a target, it ceases to be a good measure.

Humans fall into this trap often enough. Machines simply do it faster, more literally, and with less embarrassment.

## Where agents genuinely help

All that said, this is not a case against AI agents. It is a case against using them carelessly.

Used well, agents can be extremely valuable. They are excellent in environments where:

- the objective is narrow and clearly defined
- the downside of error is limited and reversible
- the rules are stable
- human review exists at sensible checkpoints
- tool access is tightly scoped
- performance can be monitored against real outcomes rather than vibes

This makes them useful for things like internal research triage, software testing routines, basic reconciliation tasks, document routing, controlled IT workflows, and first-pass operational support.

In such settings, the agent is less like a manager and more like a diligent junior: quick, tireless, occasionally impressive, and very much in need of supervision.

That is a promising arrangement.

## The governance question

The real question for organisations is not whether they *can* deploy agents, but how responsibility is preserved once they do.

This is not a hypothetical gap. The UK government's latest Cyber Security Breaches Survey found that of the businesses using or adopting AI, only around a quarter have any process in place to manage the risks it creates. Three quarters are running the experiment with no house rules at all.

Every autonomous workflow should have clear answers to a few unglamorous questions:

- What exactly is this system allowed to do?
- What is it not allowed to do?
- What happens when confidence is low or information is missing?
- Who reviews failures? How are mistakes detected?
- Can actions be reversed?
- Which metrics are being optimised, and what might those metrics distort?
- At what point must a human intervene?

Before our lending models could decide anything unattended, we had to answer every one of these. Not because a framework demanded it, but because the alternative was finding out the answers from our losses.

These are not bureaucratic annoyances. They are the infrastructure of trust. A system that acts without clear ownership is not advanced. It is simply convenient in a dangerous way.

## A useful rule of thumb

A sensible rule is this: automate execution before you automate discretion.

If a task is clear, repetitive, and low-stakes, automation is usually a gift. If a task depends on nuance, tacit knowledge, conflicting objectives, or context that is hard to formalise, autonomy should be introduced with enormous caution.

The most expensive mistake is often not using AI too little. It is using it in places where competence is easy to imitate and hard to verify. Modern systems can appear capable long before they are dependable. They can mimic understanding without grasping consequence.

## The discipline ahead

The future will contain more agents, not fewer. Costs will fall, tooling will improve, and businesses under competitive pressure will keep pushing toward greater autonomy.

So the task is not resistance for its own sake. It is disciplined adoption.

Use agents where speed matters and harm is containable.
Constrain them where context is thin.
Audit them where incentives are distorted.
Stop pretending that a completed workflow is the same thing as a wise outcome.

A machine that can act is a powerful tool.

A machine that can act *unchecked* is a management failure.

The temptation of autopilot is not that it looks reckless. It is that it looks efficient.

And that is why, in the age of AI agents, the oldest technological principle still applies: just because a system can run on its own does not mean it should be left alone.

---

**Steve Solomon**
Founder of Delphi Decide. Thirty years across quantitative finance and running real businesses — building tools that turn data into decisions. [More about Steve →](/about/)

<!-- PUBLISHING NOTES (remove before publish)
- Suggested slug: the-temptation-of-autopilot
- Word count: ~1,150 (within 600–1,200 house range)
- Stat source: Cyber Security Breaches Survey 2025/26 — of UK businesses using/adopting AI, only ~24% have any process to manage AI-related risks. Consider linking to gov.uk source page in the published version.
- LinkedIn UTM: ?utm_source=linkedin&utm_medium=social&utm_campaign=the-temptation-of-autopilot
- Add to sitemap.xml + insights listing card on publish per standard flow.
-->

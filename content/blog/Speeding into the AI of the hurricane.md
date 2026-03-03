---
title: "2025-09-30: Speeding into the AI of the hurricane"
date: 2025-09-30
draft: false
---
Substack: [We're speeding directly into the AI of the hurricane](https://valstechblog.substack.com/p/were-speeding-directly-into-the-ai)

In three words, yesterday was wild.

In three launch announcements:

- Anthropic dropped [Claude Sonnet 4.5](https://www.anthropic.com/news/claude-sonnet-4-5), featuring a 20% performance improvement in computer use and “telecom agent tool use” (see [tau2-bench tasks](https://github.com/sierra-research/tau2-bench/blob/main/data/tau2/domains/telecom/tasks.json): things like debugging cell service issues) over Opus 4.1. They also highlighted model improvements in financial analysis, law, medicine, and engineering, with feedback from human experts. More notable to me personally was the explicit announcement of “our most aligned frontier model yet” (“reducing concerning behaviors like sycophancy, deception, power-seeking, and the tendency to encourage delusional thinking”), the [Claude Agent SDK](https://www.anthropic.com/engineering/building-agents-with-the-claude-agent-sdk) to build agents, and a research preview of a hybrid infrastructure-agent UI experiment called [Imagine with Claude](https://claude.ai/imagine/), **“software that generates itself in response to what you need”.**
    
- Microsoft also released [Agent Mode](https://www.microsoft.com/en-us/microsoft-365/blog/2025/09/29/vibe-working-introducing-agent-mode-and-office-agent-in-microsoft-365-copilot/) (using OpenAI GPT-5, although Office Agent in Copilot uses Anthropic models, and a Microsoft Office SVP is quoted saying Microsoft is exploring other model providers outside of OpenAI), **“bringing vibe working” to Excel, Word, and soon PowerPoint**, achieving 57.2% accuracy in the SpreadsheetBench Excel benchmark (human score: 71.3%):
    
    > _“It’s work, quite frankly, that a first-year consultant would do, delivered in minutes.” —_ [Sumit Chauhan](https://www.theverge.com/news/787076/microsoft-office-agent-mode-office-agent-anthropic-models)
    
- OpenAI announced [Instant Checkout in ChatGPT](https://openai.com/index/buy-it-in-chatgpt/) allowing **ChatGPT users to buy directly from Etsy and “over a million Shopify merchants”** (Glossier! Spanx! Vuori!) and open sourced the [Agentic Commerce Protocol](https://www.agenticcommerce.dev/) developed with Stripe. Nathan Lambert [tweeted](https://x.com/natolambert/status/1972711460683026769): “This is a way bigger deal than the Claude release.”
    

### Eyes bigger than stomach. AIs bigger than wallet

Three things Bain first-years are definitely texting each other right now:

- bruhhh my associate just asked me about microsoft agent mode. i’m so cooked
    
- pls god don’t let my bf find out about instant checkout in chatgpt. i caught him whispering to chatgpt the other day and i don’t want to wake up to a hundred tubs of protein powder and a thousand dollar credit card bill 💀
    
- babe wake up new claude just dropped
    

Okay, maybe just me to myself for the last one (me n who fr 😩), but as I also [tweeted](https://x.com/valstechblog/status/1972850308071186816), one of the biggest milestones of Amazon’s early e-commerce strategy was [one-click checkout](https://knowledge.wharton.upenn.edu/podcast/knowledge-at-wharton-podcast/amazons-1-click-goes-off-patent/). A single click to buy. No re-entering billing, shipping, payment. Amazon held the patent for almost 20 years, and only then in 2017 did Shopify launch its one-click Shop Pay solution.

Instant Checkout in ChatGPT smells really similar to OG one-click checkout. It appears OpenAI is trying to capture more of the public consumer market while Anthropic is going the enterprise route. Yesterday I wrote about the [Anthropic Economic Index](https://www.valstech.blog/i/174754379/the-latest-anthropic-economic-index-report-raises-far-more-questions-than-it-answers) which analyzed Claude usage patterns globally; OpenAI published a [ChatGPT usage study](https://cdn.openai.com/pdf/a253471f-8260-40c6-a2cc-aa93fe9f142e/economic-research-chatgpt-usage-paper.pdf) on the same day as Anthropic published their update, highlighting **faster growth in non-work-related messages.** Although alignment and safety have been less publicly central to OpenAI’s research agenda relative to Anthropic’s, I take small solace in _[Chain of Thought Monitorability](https://arxiv.org/pdf/2507.11473v1)_ (2025), with contributors from DeepMind (including one of my favorite bloggers [Neel Nanda](https://www.neelnanda.io/)), OpenAI, Anthropic, [METR](https://metr.org/), endorsed by the “Godfather of AI” Geoffrey Hinton. I discovered this paper via a tweet by [Miles Brundage](https://x.com/Miles_Brundage/status/1972839873620091323):

> _chain of thought reasoning… Improves almost everything (sycophancy, hallucination, obvious misuse, etc.) [in language models] if you don’t screw up RL, and many things even if you do… not to even mention the benefits in terms of **monitoring the chain of thought** to detect shenanigans - I was just talking about improving the outputs themselves_

The paper asks researchers to “study what makes models monitorable”, e.g. measuring readability, reasoning and task capability on “single forward pass”, and “track [chain of thought] monitorability of their models and treat it as a contributor to model safety”. They also call out, just as economists are begging researchers and policymakers to get ahead of measuring and guard-railing the socioeconomic impact of AI, that frontier researchers need to proceed with caution when weighting chain of thought monitoring as factors to assessing safety:

> _more advanced, situationally aware models… may become able to avoid detection by overriding their propensity to think out loud, and, when reasoning is required, to deliberately obfuscate it_
> 
> _We find it plausible, though far from clear, that some forms of process supervision could substantially improve model alignment by effectively intervening on model reasoning. Research strategies that aim to unconditionally preserve [chain of thought] monitorability in its current forms may miss productive safety opportunities of this kind_
> 
> _safety measures for future AI agents will likely need to employ **multiple monitoring layers that hopefully have uncorrelated failure modes**_

### What Would Claude Do? (WWCD)

My biggest fear in all of this is that AI safety and alignment will simply fall to the wayside as influential labs start openly driving their research to serve more consumer-altering, consumption-enabling behavior.

Of course, there are time-saving benefits to automating away the decisions involved in making mundane, routine purchases. A hundred years ago, [supermarkets where you could find fresh produce and dry goods in the same place](https://www.groceteria.com/about/a-quick-history-of-the-supermarket/) didn’t exist; in the past seven years Amazon Go has [tried and largely failed](https://www.nytimes.com/2018/01/21/technology/inside-amazon-go-a-store-of-the-future.html) to remove even the cashiers from supermarkets, while Instacart, Thrive Market, Walmart, and Amazon Fresh survive in the “groceries delivered directly to your door” space.

But this type of shopping isn’t what I’m worried about with ChatGPT Instant Checkout and the Agentic Commerce Protocol. We should be concerned that we’re rolling out agents that can encourage and enable people to make purchases while _**simultaneously setting model development goals to become more competent at entry-level professional tasks** —_ while there are exciting avenues to bridging economic gaps here, perhaps diversifying and driving more business across Etsy and Shopify merchants, there is also staggering, immeasurable risk to exposing this infrastructure to scammers and fraudsters undoubtedly hard at work figuring out how to capture the eyes and wallets of unsuspecting ChatGPT shoppers.

I’m curious to see if and how Anthropic responds to OpenAI’s shopping integrations. I’m betting we won’t see such changes to Claude, at least not too soon. The romantic in me wants to believe it’s because Anthropic is so committed to its safety-first mission that they’d feel the need to invest a lot more into solidifying consumer-protecting model behavior before releasing something like this, but the realist in me understands that Anthropic has also placed a lot of weight on alignment and safety for research credibility, and that Claude’s piece of the AI pie is looking more and more like enterprise.

Regarding external influences to our behaviors and personalities, [near](https://x.com/nearcyan) puts the tension well in a blog post [“Personality Basins”](https://near.blog/personality-basins/) I found via [maja](https://x.com/majamediaco):

> _One interesting way to frame personality capture is by combining it with the concept of [attention economics](https://en.wikipedia.org/wiki/Attention_economy). All of the apps on your phone want to turn you into the type of person that uses them all day because that is beneficial for their revenue models. **In many cases this is mutually beneficial, but it’s nonetheless clear that the cat and mouse game is starting to favor the felines more and more** over the last two decades as they have learned to perfect their craft of user acquisition, [retention](https://userpilot.com/blog/user-retention/), and [ARPU](https://www.investopedia.com/terms/a/arpu.asp) maximization._

near also quotes [Dario Amodei on Dwarkesh Podcast](https://www.dwarkesh.com/p/dario-amodei):

> _“I’ve just seen cases with a number of people I’ve worked with, where attaching your incentives very strongly to the approval or cheering of a crowd can destroy your mind, and in some cases, it can destroy your soul.”_

On forming [independent views on AI safety](https://www.neelnanda.io/blog/47-inside-views), Neel writes:

> _**Don’t be a monk** - you form an inside view by going out in the world and doing things - not just by hiding away and thinking really hard_
> 
> _**Inside vs outside views is a spectrum** - there’s no clear division between thinking for yourself and deferring. Forming inside views starts out by deferring, and then slowly forming more and more detailed models of where I’m deferring and why over time… Getting here looks like downloading other people’s gears level models into your head, and slowly combining them, deleting parts you disagree with, adding ideas of your own, etc_

### The AI of the tiger, [the thrill of the fight](https://www.youtube.com/watch?v=btPJPFnesV4)

Storm chasers cite curiosity and adrenaline as primary motivators to why they continue to race towards the danger. As we learned from the 1996 classic _[Twister](https://www.rottentomatoes.com/m/1071167-twister)_, there’s a complex human bond formed in the shared, high-stakes endeavor to get as close as possible to something much bigger and more powerful than any of us, to hold it close enough to appreciate the stillness at the center, while constantly trying to predict and sidestep its violent edges.

That’s how the AI race feels to me right now. The hurricane is huge and looming. It’s moving and growing so quickly we won’t be able to outrun it entirely, and we can’t guarantee that our shelters will protect us. Storm chasers are driving and flying at it from all directions. There’s an eye in there, a central place of calmness and peace, which some of us might be lucky enough to experience, but most of us will have to avoid entirely.

There is already, and will continue to be, destruction in the path of the storm. The difference here is that it’s of our own making. We increase our chances of survival as a society by building and enforcing socioeconomic and cultural shelters in the form of technological model guardrails, social incentives to develop and retain independent thought, forging more personal connections and stronger communities.

And, if we can accelerate the passage of the unpredictable, unforgiving elements of the storm, we’ll be rewarded with fresh rain, nutrients in the soil, and a foundation on which to construct something stronger and healthier.

---

[Dusty](https://www.imdb.com/name/nm0000450/?ref_=ttqu_qu): Jo! Bill! Did you see that explosion?

[Jo](https://www.imdb.com/name/nm0000166/?ref_=ttqu_qu): [_having just driven through the exploding petroleum truck with Bill_] Yeah, we saw it.

— [Twister](https://www.imdb.com/title/tt0117998/) (1996)
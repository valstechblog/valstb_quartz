---
title: On the Anthropic Economic Index
date: 2025-03-14
draft: false
---
Substack: [The Anthropic Economic Index is a microscopic lens with incredible potential](https://valstechblog.substack.com/p/the-anthropic-economic-index-is-a)

This week I went to the dentist for a standard six-month cleaning and annual x-ray. My dentist uses [Pearl](https://www.hellopearl.com/), “the only dental AI company with FDA clearance for patient-facing detection of numerous common dental conditions”.

“What’s this software?” I asked him, noticing how Pearl visually highlighted sections of the x-ray and made them clickable. “Oh, it points out possible problem spots, like this tiny one,” he said, pointing at what would have looked like a smudge on the screen without the software’s overlay. “It helps me remember to monitor these over time. This one looks like it’s not bigger than it was last year, so I’m not too worried about it for you.”

“Nice,” I nodded. “Yeah,” he said, “AI is everywhere now.”

I’ve seen a noticeable uptick in AI bubble speculation in conversations with friends and coworkers recently. [Dave Friedman](https://substack.com/@davefriedman) just published some useful notes [on the current state of the AI industry as compared to dotcom and telecom](https://substack.com/home/post/p-159067950):

> - _If today’s AI boom follows historical tech bubbles, **many AI startups will go bankrupt**, valuations will crash, and only a few dominant players will remain. The hyperscalers will use their balance sheets and distribution channels to consolidate much of the AI market._
>     
> - _However, AI differs from dotcom/telecom in that it **already has commercial utility, is bottlenecked by supply constraints, and is primarily backed by tech giants rather than startups and venture capitalists**._
>     

Last month Anthropic launched the [Anthropic Economic Index](https://www.anthropic.com/news/the-anthropic-economic-index) (not to be confused with the [OpenAI Economic Blueprint](https://openai.com/global-affairs/openais-economic-blueprint/)) and an [initial report](https://arxiv.org/pdf/2503.04761) presenting “a novel framework for measuring AI usage patterns across the economy”. Their analysis mapped 4+ million Claude conversations to tasks by US Department of Labor defined occupations and generated a few interesting plots I want to highlight.

[Anthropic [open sourced their data and Jupyter notebook](https://huggingface.co/datasets/Anthropic/EconomicIndex) supporting this initial report and invited [public feedback](https://docs.google.com/forms/d/e/1FAIpQLSfDEdY-mT5lcXPaDSv-0Ci1rSXGlbIJierxkUbNB7_07-kddw/viewform), so I went in and ran the analyses myself on my local machine to see how easy it would to be to do this. It’s incredibly easy and I like the locally generated color scheme better so I will be using plots from my own local run.]

**Disproportionately high usage of Claude in computer and mathematical sciences, entertainment and media, life and social science, and education relative to US worker population in those areas; disproportionately low usage in transportation, sales, administrative, and food service.** Caveat: “the occupational classification of a conversation does not necessarily mean the user was a professional in that field.” Even so, this is consistent with my own recent empirical evidence that software engineers, teachers, media marketers, and students are increasingly turning to AI assistants to answer questions and help them write, while specialized and physical skills like transportation, construction, and food service either have less need for these types of outputs and/or do not find Claude as effective to assist tasks.

![](https://substackcdn.com/image/fetch/$s_!VtDp!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F9b88458d-4ccc-4b30-865a-a9c3deac3ecb_1976x1176.png)

**Software ranks high on the wage-Claude density spectrum, but OB/GYNs (by task classification) are the highest paid, least frequent Claude users.** Of course my initial reaction to this was “What types of prompts would be classified as OB/GYN tasks?” but the data is produced by “privacy-preserving platform” [Clio](https://arxiv.org/pdf/2412.13678) (Claude insights and observations) so I could only find a meta-level view of occupational tasks in the data, which is good for building customer trust (your personal interactions with Claude will not be released in an open-source dataset) but insufficient to answer questions like this, and other questions I have such as demographic (e.g. age, education level, geographical location) patterns in Claude usage.

![](https://substackcdn.com/image/fetch/$s_!t4M5!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F17ad4610-23e3-40f2-991a-f8b10b13c93a_2362x1176.png)

I adjusted the plotting thresholds to provide a little more color (sacrificing cleanliness of the graph). Waitstaff and orthodontists join shampooers and OB/GYNs at the salary extremes for low frequency Claude usage by task; technical writers and more software-related occupations join the ranks of higher usage; notably, tutors emerge as a higher usage occupation on the lower end of the wage spectrum.

![](https://substackcdn.com/image/fetch/$s_!dSv6!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Ffbd94a7d-6e25-4ab6-a4bd-10b0b184b6f3_2362x1176.png)

For the final point to highlight from this paper, I will use the original graphic from the paper. **“AI use leans more toward augmentation (57%), where AI collaborates with and enhances human capabilities, compared to automation (43%), where AI directly performs tasks.”** In other words, users still ask Claude more “help me do X” and “optimize Y” type tasks (augmentation) over “do Z” (automation).

![](https://substackcdn.com/image/fetch/$s_!LEmb!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2Fb4f26951-b288-4e57-bad7-8241d26959d8_1048x634.png)

Of course, the authors themselves are most aware of the limitations of their analysis (task classification vs. occupation, limited occupational dataset, limited context into user workflows) and future directions (task subsets within occupations, broader impact of the work). I find their final words consistent with my own thoughts around these general trends:

> _While these patterns are informative, they capture just the beginning of AI’s integration into work. As AI systems expand beyond text to handle video, speech, and physical actions through robotics, and as AI agents become more capable of carrying out extended tasks autonomously, the nature of human-AI collaboration is poised to transform dramatically. **New tasks and even entirely new occupations may emerge around these capabilities. Empirical frameworks that track these changes dynamically will be crucial for anticipating and preparing for the evolving landscape of work.** **The challenge ahead lies not just in measuring these changes, but in using our understanding of them to help shape a better future.**_

While I actually found the dataset and analysis a little underwhelming, I realize that isn’t the point of this paper. The point is to establish some methods of thinking through these patterns and to get researchers and economists talking, which Anthropic is well-suited to do.

### Pull request: Anthropic Green / Anthropic Environmental Index

This is going to be a less corporate-friendly take on something that would be valuable to study and measure over time: an environmental impact index to save on the environmental cost of prompts to Claude and other technologies.

An openly AI skeptic friend sent me this [CJR study ripping apart generative search tools in news citation capabilities](https://www.cjr.org/tow_center/we-compared-eight-ai-search-engines-theyre-all-bad-at-citing-news.php) which was doubly hilarious to me because I have no shortage of Bad Experiences with Gemini.

![](https://substackcdn.com/image/fetch/$s_!zR6J!,w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F953585d8-6c0b-41cf-91e1-57015042659a_1017x525.png)

She also raised a very valid point: even setting aside the inaccuracies we see often in generative search, what of the environmental impact?

We already know [AI research is energy-intensive but also that AI has the potential (if used responsibly) to streamline and recharacterize much of the global economy](https://www.law.georgetown.edu/denny-center/blog/artificial-intelligence-esg/). This is the core dichotomy / trade-off I’d like to see much more investment in understanding, especially if it can be deployed to frontline users to guide their behaviors and interactions with the assistive techology itself. I am imagining a combined AI/ESG Index that goes far beyond the current measures which might be basically [market cap weighted averages of AI companies](https://www.marketvector.com/indexes/sector/marketvector-artificial-intelligence-esg). I’d like to see something akin to Anthropic’s recently released token-saving updates ([optimizing throughput and reducing token usage with Claude 3.7 Sonnet](https://www.anthropic.com/news/token-saving-updates)) e.g. explicitly balancing environmental impact of queries in console, IDE, or at the search application layer.

Just as Uber allows a Green option to select a certain vehicle class or wait / share a ride for marginally lower environment impact at the price of time and cost, I could imagine Anthropic Green (or Cursor, VSCode, or any other tool serving the highest-use occupations from this study) providing a similar service. Understandably, the best of intentions will struggle to scale in the face of economic and investor pressures — we do need to make sure Anthropic and other big players continue to make good money to see the biggest possible lift to influence customer behavior here — and I’m under no pretense that ESG investing and corporate environmental commitments are of completely pure and good intentions (naturally, it may also be driven by regulation, marketing, and involve questionable actual environmental impact analysis) but I also can believe that something like this at global scale could still encourage and enforce better, more informed user patterns.

I can’t believe I’m writing this into a blog post, but here goes — I am just a member of the software occupational class, standing in front of the behemoths of the AI industry, asking them to consider popularizing environmental impact analysis frameworks on top of the economic analyses they’ve already published.
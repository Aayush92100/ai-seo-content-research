# AI Writing at Scale: Ahrefs' Step-by-Step Workflow | Ryan Law (Ahrefs)

**Research Priority:** High
**Content Type:** Podcast / YouTube Video (Interview)
**Research Category:** AI Content Operations / B2B SaaS Content Marketing

**Author:** Ryan Law (Director of Content Marketing, Ahrefs), interviewed by Tim Soulo (CMO, Ahrefs)
**Source URL:** https://www.youtube.com/watch?v=D7LBx8RFOcQ (also published as Ahrefs Podcast episode; companion article at https://ahrefs.com/blog/my-complete-ai-content-process-for-ahrefs)
**Date Published:** August 5, 2025
**Duration:** 45 minutes

## Why This Content Was Selected

This episode is one of Ryan Law's most operationally detailed contributions to AI content production research because it is a direct walkthrough of a real, named, repeatable system — not a general opinion piece about AI in marketing. Law explains the exact stages of Ahrefs' AI content workflow (brief → outline → draft → edit → internal links → metadata → shortcodes), the specific ChatGPT Project setup and custom instructions he uses, and the editorial guardrails that keep a human in control of quality. It was selected over more opinion-driven content because it satisfies the priority criterion of explaining a process/framework/workflow directly, and because it is corroborated by a detailed companion written article from Ryan Law himself, increasing confidence in accuracy.

## Key Takeaways

1. The workflow originated from Ahrefs' existing human editorial process: Law broke the team's standard end-to-end writing process (topic selection, briefing, outlining, structural editing, drafting, incorporating Ahrefs products, line editing, internal linking, metadata, WordPress shortcodes) into discrete Markdown documents that an LLM could follow step-by-step.
2. These process documents were uploaded into a ChatGPT "Project," along with custom instructions that direct the model to act as "a senior content strategist at Ahrefs, writing under the editorial direction of Ryan Law," always consult the project documentation, and follow the steps in sequential order.
3. Law deliberately front-loads human input at the start of the process via a content brief (target keyword, working title, key points/anecdotes to include, subtopics from Ahrefs' AI Content Helper tool, and specific Ahrefs products to mention) rather than relying on heavy editing of a finished draft, because he finds it easier and more enjoyable to guide generation than to rewrite a completed article.
4. He uses Ahrefs' "AI Content Helper" to analyze top-ranking SERP content and extract competitive subtopics, which get folded directly into the content brief to ensure topical competitiveness.
5. For some topics he runs a ChatGPT "deep research" request first (e.g., to check whether major LLM providers had publicly endorsed the llms.txt protocol) and incorporates the synthesized findings into the brief.
6. During drafting, Law uses ChatGPT Canvas specifically (over Claude, which he says has a "consensus" reputation for better long-form writing) because Canvas lets him leave inline editorial comments the same way he would for a human writer — flagging vague language, requesting real examples, correcting wrong ideas, trimming or expanding sections.
7. ChatGPT reliably hallucinates internal link URLs when asked to insert ~10 internal links to other Ahrefs blog posts; Law currently catches these with Ahrefs Site Audit (to find broken links) and plans to fix the root cause by supplying the model a real list of URLs with descriptions to choose from instead of letting it generate links freely.
8. Images are explicitly excluded from the AI process — screenshots, custom graphics, and data-based graphs are still added manually because generative AI was not considered capable of producing them to the required standard at the time.
9. Ahrefs' own research found a correlation of approximately 0.011 (effectively zero) between AI-content usage and Google search ranking position, supporting the claim that Google does not penalize AI-assisted content as long as it isn't mass-produced spam.
10. Every piece of content, AI-assisted or fully human-written, is still personally read, reviewed, edited, and approved by Law before publication — he frames this as the non-negotiable editorial guardrail that prevents the process from becoming "push-button" content automation.

## Important Frameworks Mentioned

* **The 7-Stage Ahrefs AI Content Workflow:** Content brief → Outline → Structural editing → Drafting → Mention Ahrefs product → Line editing → Internal linking → Metadata → WordPress shortcodes (as encoded into the ChatGPT Project's custom instructions).
* **"Pareto Prompting"** — Law's ongoing effort to identify the roughly 20% of instructions responsible for 80% of output quality; the three elements he currently considers most important are (a) instructing the model to always consult the project documentation and proceed sequentially, (b) including a fixed summary of the target audience, and (c) instructing the model to roleplay as someone with "in-the-trenches experience," which he says is what produces first-person anecdotes and concrete examples in the output.
* **Front-Loaded Editorial Input Model** — concentrating human expertise/direction at the brief stage rather than at the end-of-process editing stage, based on Law's view that substantial edits to an already-completed AI draft are harder and less enjoyable than shaping a brief and outline upfront.
* **Topic-Suitability Filter** — Law's rule that this AI process is only used for simple informational topics where he has enough subject-matter familiarity to judge quality, explicitly excluding opinion pieces, original research content, and new or rapidly changing topics.
* Referenced (but not Ahrefs-specific) writing/structuring frameworks mentioned in the episode: the PAS formula (Problem–Agitate–Solution), the MECE principle (Mutually Exclusive, Collectively Exhaustive), and the Pyramid Principle (Barbara Minto) — used as structural models the AI is directed toward when building outlines.

## Tools Mentioned

* ChatGPT (Projects feature, Canvas feature, Deep Research feature)
* Claude (mentioned as having a reputation for stronger long-form writing, but not the primary tool used due to lacking ChatGPT Canvas's inline-comment workflow)
* Ahrefs AI Content Helper (SERP/subtopic analysis tool used to build content briefs)
* Ahrefs Site Audit (used to catch broken/hallucinated internal links)
* Ahrefs Portfolios (used to track keyword rankings, backlinks, and traffic for AI-generated articles as a group)
* Ahrefs Web Analytics (used to monitor traffic sources and on-page metrics for individual articles)
* WordPress (the Ahrefs blog's CMS, including custom shortcodes inserted via the AI workflow)
* Google Docs (referenced as part of the broader tool/workflow ecosystem)

## Actionable Lessons For B2B SaaS

1. Convert your team's existing human editorial process into discrete, step-by-step Markdown documents (brief → outline → draft → edit → links → metadata) before attempting to automate any part of it with AI — Law's system works because it formalizes a process that already existed, rather than inventing a new one from scratch.
2. Invest editorial time at the brief/outline stage rather than at the end-of-process editing stage: a detailed content brief (target keyword, key anecdotes/examples, competitive subtopics pulled from a content-optimization tool, and specific product use cases to mention) produces a better starting draft than asking AI to write freely and fixing it afterward.
3. Treat AI-generated internal links and citations as unverified by default — build a verification step (e.g., a site-audit/broken-link check, or supplying the model a real, pre-approved list of URLs) into the workflow rather than trusting AI-suggested links to be accurate.
4. Restrict AI-assisted drafting to topics where an in-house editor has enough subject-matter knowledge to judge quality — avoid using this kind of workflow for opinion content, original research, or fast-changing/contested topics where hallucination risk is harder to catch.
5. Track AI-assisted content as a distinct portfolio/cohort (rankings, backlinks, traffic, AI-assistant referral traffic) so you can validate — with your own data, not just industry claims — whether AI-assisted content is performing comparably to human-written content before scaling the process further.

## Reliability Assessment

**Confidence Level:** High

**Evidence Sources:**
* Original content (YouTube video description, chapter timestamps, and "Referenced in this episode" metadata retrieved directly from the video page)
* Supporting articles (Ryan Law's companion long-form article on ahrefs.com, "My Complete AI Content Process for Ahrefs," published the same day as the video and explicitly framed as the source material Tim Soulo questions him about in the episode)

**Limitations:**
* A full word-for-word spoken transcript of the 45-minute episode was not accessible through the sources used; YouTube's transcript could not be directly retrieved (the page returned a bot-protection response, so only embedded metadata — title, description, chapters, and referenced links/people/tools — could be recovered).
* Specific spoken quotes from the podcast conversation itself are not included in this file; all direct quotations used above (e.g., the ChatGPT custom-instructions text) are drawn from Ryan Law's companion written article, which states it documents the same process discussed in the episode.
* Chapter timestamps listed in the video description (e.g., "00:00 Why We Made This Episode," "30:43 A Closer Look at the 7 Foundational Documents") are reported as published metadata, not independently verified against actual spoken content at those exact times.

## Transcript Availability

A full transcript was not available. Direct retrieval of the YouTube video page returned a bot-protection response, which prevented access to the auto-generated captions/transcript. In place of a transcript, this file relies on: (1) the video's official description and chapter list (recovered from embedded page metadata), and (2) Ryan Law's detailed companion article published the same day, which the video description confirms documents the same workflow Tim Soulo interviews him about. No spoken dialogue, quotes, or timestamped statements from within the video itself have been fabricated or invented; all process details above are drawn from Law's own written account of the process.

## Research Notes

This content is a strong primary source for AI-powered SEO content production research because it documents, in granular and verifiable detail, how a major SEO/content SaaS company (Ahrefs) operationalizes AI in its own editorial pipeline rather than just advising others on AI strategy in the abstract.

**How Ahrefs approaches AI content:** The process is explicitly framed as augmentation of an existing human workflow, not replacement — Law converts the team's established editorial steps into LLM-followable documentation, then uses a ChatGPT Project with custom instructions and uploaded reference files to execute that workflow consistently across articles. AI is reserved for "hygiene" content (e.g., long-tail informational articles, listicles, content refreshes) rather than opinion pieces or original research.

**Editorial oversight methods:** Oversight is concentrated at two points: (1) the content brief, where a human supplies the keyword, anecdotes, competitive subtopics, and product mentions before generation begins, and (2) a structured review pass using inline commenting (via ChatGPT Canvas) at the outline and draft stages, mirroring how Law edits human writers. Law states he personally reads, reviews, edits, and approves every article before publication regardless of who or what wrote the first draft.

**AI workflow design:** The workflow is sequential and document-driven (brief → outline → structural edit → draft → product mention → line edit → internal links → metadata → shortcodes), encoded as custom instructions referencing uploaded Markdown process files, which Law describes as an evolving system he is still trying to simplify down to its highest-leverage ("Pareto") instructions.

**Risks and limitations discussed:** The clearest documented risk is link hallucination — ChatGPT invents URLs when asked to insert internal links, requiring a verification/fix step. Law also flags that the process is unsuitable for topics outside the editor's subject-matter competence, and that images/graphics remain a manual, non-AI task. He frames the whole system as "messy" and "imperfect," explicitly cautioning against treating it as a finished or fully hands-off solution.

**Relevance to B2B SaaS organizations:** Ahrefs is itself a B2B SaaS company, and the workflow integrates its own product (AI Content Helper, Site Audit, Portfolios, Web Analytics) into the content pipeline — making this a directly transferable case study for other SaaS content teams looking to scale informational/educational content (documentation-adjacent, comparison, and long-tail SEO content) while preserving editorial quality control and measurable performance tracking.
# The Science Of How AI Pays Attention

**Research Priority:** High
**Content Type:** Research Presentation / Original Data Analysis (published as a newsletter article and syndicated as a guest column)
**Research Category:** AI Search / GEO / B2B SaaS Growth

**Author:** Kevin Indig
**Source URL:** https://www.searchenginejournal.com/the-science-of-how-ai-pays-attention/567597/ (originally published on Kevin Indig's newsletter, Growth Memo: https://www.growth-memo.com/p/the-science-of-how-ai-pays-attention)
**Date Published:** February 17, 2026 (Growth Memo original: February 16, 2026)
**Duration:** Not applicable (written article); listed reading time is 10 minutes (Search Engine Journal) / 11 minutes (Search Engine Journal Twitter metadata)

## Why This Content Was Selected

This is one of Kevin Indig's most valuable contributions to AI Search/GEO research because it is a large-scale, methodologically transparent, original data analysis — not commentary or opinion. Indig analyzed 1.2 million ChatGPT responses (isolating 18,012 verified citations for positional analysis and 11,022 for linguistic analysis) using semantic embedding matching to determine precisely *where* on a page and *what kind* of writing ChatGPT cites from. It directly satisfies the research priority of content containing original research, data analysis, and a documented experimental methodology, and produces concrete, actionable findings (a "ski ramp" citation distribution and five measurable linguistic characteristics of cited content) rather than generic AI commentary.

## Key Takeaways

1. Across 18,012 verified citations, ChatGPT shows a "ski ramp" distribution: 44.2% of citations come from the first 30% of an article (the intro), 31.1% come from the middle 30–70%, and 24.7% come from the final third — meaning content placed early in an article is cited at a substantially higher rate than content buried mid-document.
2. This positional pattern was tested for statistical stability by splitting the data into four randomized validation batches; batches 2, 3, and 4 produced near-identical distributions (batch 1 was "slightly flatter"), and Indig reports the overall pattern has a P-value of 0.0 (p < 0.0001), which he describes as statistically indisputable.
3. At the paragraph level (analyzed across 1,000 high-citation pieces of content), ChatGPT does not simply quote the first sentence of a paragraph: 53% of citations come from the middle of a paragraph, 24.5% from the first sentence, and 22.5% from the last sentence — indicating the model selects whichever sentence carries the highest "information gain," not strictly the first one.
4. Five linguistic characteristics were found to meaningfully increase citation likelihood: (1) definitive/declarative language (e.g., "is defined as," "refers to") — cited text was almost 2x more likely to contain this (36.2% vs. 20.2%); (2) conversational, question-answer structure — cited text was roughly 2x more likely to contain a question mark (18% vs. 8.9%), and 78.4% of citations containing questions came from headings; (3) entity richness — heavily cited text averaged 20.6% entity density versus a 5–8% baseline in normal English text; (4) balanced sentiment — cited text averaged a subjectivity score of 0.47 on a 0.0 (pure fact) to 1.0 (pure opinion) scale, indicating an "analyst voice" blending fact and interpretation rather than pure objectivity or pure opinion; (5) simpler, business-grade writing — cited ("winning") text averaged a Flesch-Kincaid grade level of 16 versus 19.1 for uncited ("losing") text, meaning even highly complex topics benefited from clearer sentence construction.
5. Headings structured as literal questions followed directly by a matching answer (e.g., "When did SEO start?" → "SEO started in...") outperform abstract topic headings (e.g., "The History of SEO" → narrative description), a pattern Indig calls "entity echoing" — the heading's key term reappears as the first word of the answer.
6. The "ultimate guide" content format — long narrative intros that delay key insights until later in the piece — is identified as structurally disadvantaged for AI citation, since it places valuable information outside the highest-citation zone (the first 30% of the page).
7. Naming specific entities (brands, tools, competitors) by name measurably outperforms generic language; Indig's example contrasts "There are many good tools for this task" (0% entity density) against "Top tools include Salesforce, HubSpot, and Pipedrive" (30% entity density), arguing specific, verifiable entities lower the model's "perplexity" (uncertainty) and make a sentence more likely to be selected.
8. The findings explicitly do not support "dumbing down" content for AI: the highest-citation content used business-grade vocabulary (Flesch-Kincaid ~16, comparable to publications like The Economist or Harvard Business Review) rather than maximally simplified language, while still avoiding overly academic/jargon-heavy writing (Flesch-Kincaid ~19+).
9. Indig frames the overall implication as a "clarity tax": writers must front-load definitions, named entities, and conclusions rather than building toward them narratively, because the AI interprets a slow reveal as "a lack of confidence" and prioritizes immediate classification of entities and facts over narrative pacing.
10. The underlying data and methodology are disclosed in detail: all data came from Gauge (an AI-visibility data provider), drawing on roughly 3 million AI answers and 30 million citations from ChatGPT, with web content for each citation URL scraped at the time of the answer; semantic matching used the all-MiniLM-L6-v2 sentence-transformer model with cosine similarity and a 0.55 similarity threshold to filter out weak matches or hallucinated citations.

## Important Frameworks Mentioned

* **The "Ski Ramp" Citation Distribution** — a positional model of where ChatGPT pulls citations from within a page (44.2% from the first 30%, 31.1% from the middle 30–70%, 24.7% from the final third), used as a content-structuring heuristic: front-load the highest-value information into the first third of an article.
* **The Five Linguistic Citation Characteristics** — a repeatable content-quality checklist derived from the data: (1) definitive language, (2) conversational Q&A structure (especially in headings), (3) high entity density, (4) balanced sentiment/subjectivity (~0.47), (5) business-grade (not maximally simplified, not overly academic) readability.
* **"Entity Echoing"** — a heading/answer pairing technique where a heading phrased as a literal question is immediately followed by an answer that repeats the heading's key entity as its first word, intended to mirror how ChatGPT appears to treat headings as proxies for user prompts.
* **The "Clarity Tax" Concept** — Indig's strategic framing that AI-era content requires writers to pay an upfront cost in restructuring (front-loading conclusions, definitions, and entities) that traditional narrative-style "ultimate guide" writing does not require.
* **The Methodology Itself as a Reusable Research Framework** — semantic-embedding-based citation attribution (matching AI answer text to source sentences via cosine similarity above a defined threshold) is presented as a transferable approach for any team wanting to audit which parts of their own content are actually being cited by AI systems.

## Tools Mentioned

* ChatGPT (the AI system being studied)
* Gauge (the AI-visibility data provider that supplied the underlying dataset of ~3 million AI answers and 30 million citations)
* all-MiniLM-L6-v2 (the sentence-transformer embedding model used to match AI answer text to source-page sentences)
* Cosine similarity (the mathematical method used for matching, with a 0.55 similarity threshold applied to filter weak/hallucinated matches)
* Flesch-Kincaid readability scoring (used to measure and compare the reading-grade level of cited vs. uncited text)
* NLP subjectivity scoring (used to measure the 0.0–1.0 fact-to-opinion balance of cited text)

## Actionable Lessons For B2B SaaS

1. Restructure existing long-form content (guides, comparison pages, documentation) so the single most important insight, definition, or product claim appears within the first 30% of the page rather than being saved for a "big reveal" later — this is the single highest-leverage structural change implied by the ski-ramp data.
2. Rewrite section headings as literal user questions immediately followed by a direct, entity-repeating answer (e.g., "What is [Product Category]? [Product Category] is...") rather than abstract topic headers, since this "entity echoing" pattern correlated with a large majority (78.4%) of question-containing citations.
3. Audit existing content for entity density: replace vague references to "tools," "solutions," or "competitors" with named entities (specific product names, including competitors) — the data shows this materially increases the likelihood of being the source AI selects to cite, even though it can feel counterintuitive to name competitors.
4. Avoid optimizing exclusively for simplicity or exclusively for technical depth; target a "business-grade" voice (roughly Flesch-Kincaid grade 16) that mixes plain declarative sentences with substantive analysis, since both maximally simplified and maximally academic writing underperformed in the data.
5. Treat "ultimate guide" / narrative-build content formats as a liability for AI-citation goals specifically (even if they remain useful for other purposes like dwell time or backlink acquisition), and consider whether high-priority commercial or product pages would benefit from being restructured into a more "briefing-style" format with conclusions and definitions stated upfront.

## Reliability Assessment

**Confidence Level:** High

**Evidence Sources:**
* Original content (the full published article was retrieved directly from Search Engine Journal, where Kevin Indig publishes as a VIP Contributor; this is a syndicated/co-published version of his original Growth Memo newsletter piece)
* Research reports (the article includes a detailed, disclosed methodology section covering dataset size, data provider, embedding model, similarity threshold, and statistical validation approach)
* Supporting articles (multiple independent secondary sources — Search Engine Land, Similarweb, Jarred Smith's AEO playbook, and others — cite and corroborate the same headline figures, e.g., the 44.2% first-30%-of-content citation statistic and the P-value of 0.0, indicating consistent reporting of the original findings across outlets)

**Limitations:**
* No video or audio component exists for this piece — it is a written research article, not a podcast, webinar, or video, so there is no transcript to assess; this is noted because the requested format anticipates podcast/video content, but this written research piece was selected because it best satisfies the stated priority for original research, data analysis, and documented methodology over interview-style content.
* The free, publicly accessible version (via Search Engine Journal) contains the full positional and linguistic findings and full methodology section; a related follow-up piece ("The science of how AI picks its sources," Part 2) sits partly behind Kevin Indig's paid Growth Memo subscription, and only its publicly visible summary/preview content was used as supporting context — not as a primary source — in this file.
* The underlying raw dataset (Gauge's full citation database) was not independently re-verified; this assessment relies on Indig's disclosed methodology and the statistical claims as published, cross-checked only against the consistency of figures reported by independent secondary sources.
* No timestamps apply, as this is a written article rather than time-based media.

## Transcript Availability

Not applicable in the traditional sense — this is a written research article, not a recorded podcast, webinar, or video, so there is no spoken transcript to provide. The full text of the article was retrieved directly from its publicly accessible syndicated source (Search Engine Journal) and is accurately summarized above; no content has been paraphrased from secondary or paywalled sources beyond what is explicitly attributed as supporting context.

## Research Notes

**Impact of AI Search on SEO:** Indig's research provides a data-backed challenge to a foundational SEO content convention — the long-form "ultimate guide" with a narrative build toward a conclusion. He argues this structure is now misaligned with how AI systems extract and cite information, since LLMs disproportionately draw from the first 30% of a page and treat headings as direct stand-ins for user queries.

**GEO (Generative Engine Optimization):** The piece operationalizes GEO into specific, measurable content properties (positional placement, definitive language, question-structured headings, entity density, sentiment balance, readability grade) rather than treating it as a vague new discipline. This gives content teams concrete levers to test rather than general best-practice advice.

**LLM visibility strategies:** The "entity echoing" technique and the emphasis on named-entity density (20.6% in cited content vs. 5–8% baseline) suggest a practical LLM-visibility strategy: explicitly naming products, tools, and even competitors rather than using generic descriptive language, since specificity appears to reduce the model's uncertainty about which content best answers a query.

**AI Overviews implications:** While this specific study focuses on ChatGPT citations rather than Google AI Overviews directly, the underlying mechanism described (semantic retrieval favoring front-loaded, declarative, entity-rich text) is presented by Indig as part of a broader pattern in how generative AI systems across the board parse and extract web content, making the findings plausibly relevant to AI Overviews content strategy as well — though this extrapolation is the researcher's framing, not something independently tested for Google AI Overviews specifically in this article.

**B2B SaaS growth opportunities:** Because Indig's own audience and case studies are heavily oriented toward SaaS/B2B growth functions (his bio notes prior SEO/Growth leadership at Shopify, G2, and Atlassian), the recommendations are directly applicable to SaaS content types like comparison pages, "what is X" definitional content, and feature/product pages — content types that map closely to the "definitional," "entity-rich," "Q&A-headed" profile the research identifies as high-citation.

**Data-backed findings:** All major claims in this article are quantified (44.2%/31.1%/24.7% positional split; 53%/24.5%/22.5% paragraph-level split; 36.2% vs. 20.2% definitive language; 18% vs. 8.9% question-mark presence; 20.6% vs. 5–8% entity density; 0.47 average subjectivity score; Flesch-Kincaid 16 vs. 19.1), with an explicitly stated sample size (1.2 million underlying responses, 18,012 verified citations for positional analysis, 11,022 for linguistic analysis) and statistical significance claim (P-value of 0.0, p < 0.0001).

**Strategic recommendations:** Indig's central strategic recommendation is to restructure content production around a "briefing" model — stating conclusions, definitions, and named entities immediately — while explicitly cautioning that this does not mean simplifying content to the point of losing substantive, business-grade analysis. He frames this as a "clarity tax" that content teams must consciously pay rather than an optional stylistic preference.
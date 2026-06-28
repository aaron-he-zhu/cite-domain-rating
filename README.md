# CITE Domain Rating

> **📦 Merged into [aaron-marketing-skills](https://github.com/aaron-he-zhu/aaron-marketing-skills)** — CITE now ships inside the unified marketing skills library (v10.0.0) alongside the CORE-EEAT and C³ frameworks and 38 marketing skills. This repo remains as the standalone source.

> **4 dimensions x 10 items = 40 evaluation criteria** for assessing domain authority in the Generative Engine Optimization (GEO) era.

**Version**: 1.0 | **Author**: Aaron | **Updated**: 2026-02-10

**Sister Project**: [CORE-EEAT Content Benchmark](../core-eeat-content-benchmark/) — content-level quality assessment (80 items)

---

## How to Read This Document

This document uses **progressive disclosure** — read as deep as you need:

| Depth | Sections | You Will Learn |
|-------|----------|----------------|
| Skim | Parts 1-2 | What CITE is + all 40 check items at a glance |
| Apply | Parts 3-5 | How to score domains, adapt to domain types, and run evaluations |
| Master | Parts 6-7 | Detailed Pass/Partial/Fail criteria for every item |
| Optimize | Part 8 | AI engine preferences, CORE-EEAT integration, common mistakes |

---

# Part 1: Framework Overview

## What is CITE?

CITE is a domain-level authority rating designed for the GEO era. While traditional domain metrics (Moz DA, Ahrefs DR, SEMRush AS) are 90%+ link-based and built for the "10 blue links" era, CITE is the first open standard to formally model **AI citations, entity identity, and multi-platform visibility** as first-class signals alongside links.

## Why CITE?

| Problem | Traditional Metrics | CITE Solution |
|---------|-------------------|---------------|
| Link-only worldview | DA/DR measure almost exclusively backlinks | Multi-dimensional: links + AI citations + identity + visibility |
| No AI citation signal | None measure how often AI engines cite a domain | C05-C08 formally model AI citation frequency, prominence, and breadth |
| No entity identity | None measure knowledge graph presence or brand coherence | I dimension: 10 items covering entity recognition and brand identity |
| Traffic ignored | Only SEMRush includes organic traffic (and it's closed-source) | E dimension: organic visibility, multi-platform footprint, topical authority |
| Closed methodology | All existing metrics are proprietary black boxes | Open specification: anyone can implement, audit, and extend |

## CITE + CORE-EEAT: The Complete Picture

| Benchmark | Evaluates | Level | Items | Core Question |
|-----------|-----------|-------|-------|---------------|
| **CORE-EEAT** | Content quality | Single page/article | 80 | Is this content worth citing? |
| **CITE** | Domain authority | Entire domain | 40 | Is this domain worth trusting as a source? |
| **Combined** | Full assessment | Content + Domain | **120** | Should AI engines cite this source? |

**Quick rule**: If you're evaluating a specific article or page -> CORE-EEAT. If you're evaluating the domain behind it -> CITE.

## Positioning Against Existing Metrics

| Feature | Moz DA | Ahrefs DR | SEMRush AS | Majestic TF | **CITE** |
|---------|--------|-----------|------------|-------------|----------|
| Link signals | Yes | Yes | Yes | Yes | **Yes** |
| AI citation signals | No | No | No | No | **Yes** |
| Entity/brand identity | No | No | No | No | **Yes** |
| Organic traffic | No | No | Yes | No | **Yes** |
| Anti-spam detection | Spam Score | 2025 update | 6 factors | TF/CF ratio | **10 items** |
| Topical authority | No | No | No | Topical TF | **Yes** |
| Multi-platform visibility | No | No | No | No | **Yes** |
| Open methodology | No | No | No | No | **Yes** |
| Content-level companion | No | No | No | No | **CORE-EEAT** |

## 4 Dimensions

| Dim | Full Name | Weight | Core Question | MECE Boundary |
|-----|-----------|--------|---------------|---------------|
| **C** | Citation | 35% | How strongly is this domain referenced by others — through links AND AI citations? | All "others pointing to you" signals (positive attributes) |
| **I** | Identity | 20% | How clearly is this domain recognized as a distinct entity in the information ecosystem? | Entity presence and brand recognition |
| **T** | Trust | 25% | Are there red flags suggesting this domain's profile has been manipulated? | All "is this suspicious?" detection signals (defensive) |
| **E** | Eminence | 20% | How visible and influential is this domain across the information ecosystem? | Visibility, reach, and industry standing |

### MECE Boundary

The four dimensions are mutually exclusive and collectively exhaustive:

- **C** = positive referencing signals (links + AI citations + editorial endorsements)
- **I** = entity existence and brand coherence (who you are, not how visible you are)
- **T** = suspicion and manipulation detection (negative/defensive signals)
- **E** = visibility and influence outcomes (how much you're seen)

**Disambiguation rules**:
- "Someone linked to you" -> C (positive reference)
- "Your link profile looks unnatural" -> T (suspicion)
- "You exist in the knowledge graph" -> I (identity)
- "You rank for 10,000 keywords" -> E (visibility)

---

# Part 2: Complete 40-Item Checklist

> One-line standard for every check item. Use this as your evaluation reference.

### C — Citation (10 Items)

| ID | Check Item | One-Line Standard |
|----|-----------|-------------------|
| C01 | Referring Domains Volume | >=500 unique referring domains |
| C02 | Referring Domains Quality | Referring domains themselves have strong CITE profiles |
| C03 | Link Equity Distribution | Link sources concentrate their outbound links (not "link to a million sites") |
| C04 | Link Velocity | Steady, natural link growth over time (no sudden spikes) |
| C05 | AI Citation Frequency | Domain cited by >=2 AI engines (ChatGPT, Perplexity, Gemini, AI Overview) |
| C06 | AI Citation Prominence | Cited as primary/sole source, not just supplementary mention |
| C07 | Cross-Engine Citation | Cited across >=3 different AI engines |
| C08 | Citation Sentiment | Cited in positive or neutral context, not as a negative example |
| C09 | Editorial Link Ratio | >=60% of backlinks come from genuine editorial decisions (not directories/comments/signatures) |
| C10 | Link Source Diversity | Referring domains span >=3 industries and >=5 geographic regions |

### I — Identity (10 Items)

| ID | Check Item | One-Line Standard |
|----|-----------|-------------------|
| I01 | Knowledge Graph Presence | Entity exists in >=2 major knowledge graphs (Google KG, Wikidata, DBpedia) |
| I02 | Brand Search Volume | Brand name has measurable monthly search volume |
| I03 | Brand SERP Ownership | Brand search yields >=7 first-page results controlled by the domain |
| I04 | Schema.org Coverage | >=50% of indexable pages have correct Schema.org markup |
| I05 | Author Entity Recognition | Content authors have verifiable public identities or knowledge graph entries |
| I06 | Domain Tenure | Domain registered >=3 years with continuous active use |
| I07 | Cross-Platform Consistency | Brand name, description, and contact info consistent across all platforms |
| I08 | Niche Consistency | Domain has operated in the same niche for >=3 years without pivoting |
| I09 | Unlinked Brand Mentions | Brand mentioned by third parties without links (pure reputation signal) |
| I10 | Query-Brand Association | Users append brand name to industry queries (e.g., "SEO tools moz") |

### T — Trust (10 Items)

| ID | Check Item | One-Line Standard |
|----|-----------|-------------------|
| T01 | Link Profile Naturalness | Link growth curve follows natural distribution (no bulk acquisition patterns) |
| T02 | Dofollow Ratio Normality | Dofollow percentage between 40-90% (>90% is suspicious) |
| T03 | Link-Traffic Coherence | Link volume and organic traffic are proportional (**Veto Item**) |
| T04 | IP/Network Diversity | Referring domains distributed across diverse IP ranges (no PBN clusters) |
| T05 | Backlink Profile Uniqueness | No other domain shares a near-identical backlink profile (**Veto Item**) |
| T06 | WHOIS & Registration Transparency | WHOIS info public, reputable registrar, no frequent ownership changes |
| T07 | Technical Security | HTTPS site-wide, HSTS enabled, no malware/phishing flags |
| T08 | Content Freshness Signal | Domain regularly publishes or updates content (not abandoned) |
| T09 | Penalty & Deindex History | No history of Google manual actions or deindexing (**Veto Item**) |
| T10 | Review & Reputation Signals | Positive or neutral reviews on third-party platforms (BBB, Trustpilot, G2) |

### E — Eminence (10 Items)

| ID | Check Item | One-Line Standard |
|----|-----------|-------------------|
| E01 | Organic Search Visibility | Ranks for >=1,000 keywords across search engines |
| E02 | Organic Traffic Estimate | >=10,000 estimated monthly organic visits |
| E03 | SERP Feature Ownership | Appears in Featured Snippets, Knowledge Panels, or People Also Ask |
| E04 | Technical Crawlability | AI-crawler-friendly: permissive robots.txt, clean rendering, clear structure |
| E05 | Multi-Platform Footprint | Official presence on >=3 platforms (YouTube, LinkedIn, X, Reddit, etc.) |
| E06 | Authoritative Media Coverage | Featured or cited in authoritative news media or industry publications |
| E07 | Topical Authority Depth | Ranks for long-tail keywords deep within its niche |
| E08 | Topical Authority Breadth | Covers >=70% of sub-topics within its primary niche |
| E09 | Geographic Reach | Receives organic traffic from >=5 countries/regions |
| E10 | Industry Share of Voice | Holds measurable visibility share among industry core keywords |

---

# Part 3: Scoring System

## Per-Item Scoring

| Status | Score | Meaning |
|--------|-------|---------|
| **Pass** | 10 | Fully meets criteria |
| **Partial** | 5 | Partially meets criteria |
| **Fail** | 0 | Does not meet criteria |

## Dimension and Total Scores

Each dimension: sum of 10 items = 0-100 points.

### Default Weights

```
CITE Score = C x 0.35 + I x 0.20 + T x 0.25 + E x 0.20
```

### Weighted Scoring by Domain Type

For specific domain types, apply dimension weights instead of default:

```
Weighted CITE = C x Wc + I x Wi + T x Wt + E x We
```

| Dim | Default | Content Publisher | Product & Service | E-commerce | Community & UGC | Tool & Utility | Authority & Institutional |
|-----|:-------:|:-:|:-:|:-:|:-:|:-:|:-:|
| **C** | 35% | **40%** | 25% | 20% | 35% | 25% | **45%** |
| **I** | 20% | 15% | **30%** | 20% | 10% | **30%** | 20% |
| **T** | 25% | 20% | 25% | **35%** | 25% | 25% | 20% |
| **E** | 20% | 25% | 20% | 25% | **30%** | 20% | 15% |

**Example** (E-commerce domain):
```
CITE = C x 0.20 + I x 0.20 + T x 0.35 + E x 0.25
```

## Rating Scale

| Score | Rating | Meaning |
|-------|--------|---------|
| 90-100 | Excellent | Industry benchmark; highly cited by AI engines |
| 75-89 | Good | Strong domain authority; regularly cited |
| 60-74 | Medium | Adequate authority with room to improve |
| 40-59 | Low | Needs focused optimization across dimensions |
| 0-39 | Poor | Needs fundamental domain authority building |

## Veto Items

These items trigger a risk alert regardless of total score:

| Item | Trigger | Impact |
|------|---------|--------|
| **T03** Link-Traffic Coherence | Fail: massive links + zero organic traffic | Classified as link farm |
| **T05** Backlink Profile Uniqueness | Fail: near-identical profile exists on another domain | Classified as manipulation network |
| **T09** Penalty & Deindex History | Fail: has been penalized or deindexed by Google | Domain trust = zero |

When any veto item is triggered: CITE Score is capped at 39 (Poor) regardless of other dimension scores, and a **Manipulation Alert** flag is raised.

---

# Part 4: Domain Type Guide

## Decision Tree

```
What is the domain's primary function?
|
+-- Publishes articles, news, guides, or research     -> Content Publisher
+-- Sells/markets a product or service                 -> Product & Service
+-- Operates an online store or marketplace            -> E-commerce
+-- Hosts user-generated content, forums, or Q&A       -> Community & UGC
+-- Provides web tools, utilities, or applications     -> Tool & Utility
+-- Academic, government, non-profit, or standards     -> Authority & Institutional
```

## Domain Type Profiles

### Content Publisher

**Examples**: Blogs, news outlets, knowledge bases, media sites, niche content sites

**Why C is weighted highest (40%)**: Content publishers live or die by being cited. Their entire value proposition is being referenced as an information source — by both traditional links and AI engines.

**Key priorities**: C05-C08 (AI citation signals), E07-E08 (topical authority depth/breadth)

### Product & Service

**Examples**: SaaS companies, B2B services, software vendors, agencies

**Why I is weighted highest (30%)**: Product sites need brand recognition and entity identity above all. Users and AI engines must be able to clearly identify what the product is and who's behind it.

**Key priorities**: I01-I03 (knowledge graph, brand search, SERP ownership), T06-T07 (registration transparency, security)

### E-commerce

**Examples**: Online stores, marketplaces, D2C brands

**Why T is weighted highest (35%)**: Trust is the lifeline of e-commerce. Security, reviews, and anti-fraud signals directly determine whether users (and AI engines) will recommend the site.

**Key priorities**: T06-T07 (transparency, security), T10 (review signals), I04 (Schema.org for products)

### Community & UGC

**Examples**: Forums, Q&A platforms, social communities, Reddit-style sites

**Why E is weighted highest (30%)**: Community sites thrive on visibility and engagement. Their identity is distributed across users, so I is weighted lowest (10%).

**Key priorities**: E01-E02 (organic visibility and traffic), E05 (multi-platform), C01 (referring domains volume)

### Tool & Utility

**Examples**: Web applications, online calculators, utility tools, developer tools

**Why I is weighted highest (30%)**: Tools need brand trust to get users to rely on them. Identity and recognition are more important than raw citation volume.

**Key priorities**: I01 (knowledge graph), I07 (cross-platform consistency), T07 (technical security)

### Authority & Institutional

**Examples**: Universities, government agencies, non-profits, standards organizations, research institutions

**Why C is weighted highest (45%)**: Institutional domains exist to be authoritative sources. Their core value is being cited — by researchers, journalists, AI engines, and other websites.

**Key priorities**: C01-C02 (referring domain volume and quality), C05-C07 (AI citation signals), I06 (domain tenure)

---

# Part 5: Evaluation Workflow

## 4-Gate Evaluation Process

```
+---------------+--------------+------------------+---------------------+
|    Gate 1     |   Gate 2     |     Gate 3       |      Gate 4         |
|  Preparation  | C+I Review   |   T+E Review     |   Score & Action    |
+---------------+--------------+------------------+---------------------+
| Identify      | Review       | Review           | Calculate C/I/T/E   |
| domain type   | C01-C10      | T01-T10          | dimension scores    |
| Select        | (Citation)   | (Trust)          |                     |
| weights       | Review       | Review           | Calculate CITE      |
| Gather        | I01-I10      | E01-E10          | Score with weights  |
| competitor    | (Identity)   | (Eminence)       |                     |
| data          | Mark each    | Mark each        | Check veto items    |
|               | Pass/Partial | Pass/Partial     | Generate action     |
|               | /Fail        | /Fail            | plan                |
+---------------+--------------+------------------+---------------------+
| Output:       | Output:      | Output:          | Output:             |
| Config sheet  | C+I card     | T+E card         | Report + priorities |
+---------------+--------------+------------------+---------------------+
```

## Emergency Brake

These conditions require immediate action — do not wait for full evaluation:

| Trigger | Severity | Immediate Action |
|---------|----------|-----------------|
| T05 Fail: Identical backlink profile found | **Critical** | Flag as manipulation network; investigate link sources |
| T09 Fail: Google manual action on record | **Critical** | Address penalty first; all other optimization is futile |
| T03 Fail: 10,000+ links but <100 organic visits/mo | **High** | Audit backlink profile; disavow toxic links |
| 3+ Fails in T dimension | **High** | Systematic trust audit before any link building |

## Evaluation Frequency

| Domain Type | First Evaluation | Regular Re-evaluation | Re-evaluate Trigger |
|-------------|------------------|-----------------------|--------------------|
| Content Publisher | Before GEO campaign | Quarterly | Traffic drop, AI citation loss |
| Product & Service | Before launch/rebrand | Semi-annually | Brand perception change |
| E-commerce | Before launch | Monthly | Review score changes, security incidents |
| Community & UGC | Before monetization | Quarterly | Engagement decline |
| Tool & Utility | Before launch | Semi-annually | Competitor emergence |
| Authority & Institutional | Annually | Annually | Policy or leadership change |

## Cross-Reference with CORE-EEAT

When evaluating a domain holistically, pair CITE with CORE-EEAT:

```
1. Run CITE evaluation on the domain (40 items)
2. Sample 3-5 representative pages
3. Run CORE-EEAT on each sampled page (80 items)
4. Cross-reference: Domain CITE Score + Average Content CORE-EEAT Score
5. Identify gaps: Is the domain strong but content weak, or vice versa?
```

| Pattern | CITE Score | CORE-EEAT Score | Diagnosis | Action |
|---------|-----------|-----------------|-----------|--------|
| Strong domain, strong content | High | High | Ideal state | Maintain and expand |
| Strong domain, weak content | High | Low | Authority wasted on poor content | Prioritize content quality |
| Weak domain, strong content | Low | High | Great content, invisible domain | Build domain authority |
| Weak domain, weak content | Low | Low | Fundamental issues | Start with CORE-EEAT, then CITE |

---

# Part 6: C + I Dimensions — Detailed Criteria

> Detailed Pass/Partial/Fail criteria for all 20 Citation + Identity check items.

---

## C — Citation (10 items)

> How strongly is this domain referenced by others — through links AND AI citations?

**C01: Referring Domains Volume**
- **Pass**: >=500 unique referring domains pointing to the domain
- **Partial**: 50-499 referring domains
- **Fail**: <50 referring domains

**C02: Referring Domains Quality**
- **Pass**: >=20% of referring domains themselves have strong authority (e.g., DA 50+, DR 50+, or equivalent)
- **Partial**: 5-19% of referring domains have strong authority
- **Fail**: <5% of referring domains have notable authority

**C03: Link Equity Distribution**
- **Pass**: Top referring domains concentrate their outbound links (avg <1,000 outbound domains per source), sending meaningful link equity
- **Partial**: Mixed — some concentrated sources, some "link to everyone" sources
- **Fail**: Most referring domains link to >10,000 other domains (diluted equity)

**C04: Link Velocity**
- **Pass**: Steady link growth with natural variance; no month with >3x the average monthly link acquisition
- **Partial**: Mostly steady with 1-2 unusual spikes (explainable by viral content or PR events)
- **Fail**: Sudden massive spikes inconsistent with domain activity; patterns suggest bulk link acquisition

**C05: AI Citation Frequency**
- **Pass**: Domain cited by AI engines (ChatGPT, Perplexity, Gemini, Google AI Overview) on >=10 distinct queries within its niche
- **Partial**: Cited on 3-9 distinct queries
- **Fail**: Cited on 0-2 queries or not cited at all
- Test method: Query 20+ niche-relevant questions across major AI engines; count citations

**C06: AI Citation Prominence**
- **Pass**: When cited by AI, domain is the primary or sole source in >=50% of citations
- **Partial**: Domain appears as one of several sources in most citations
- **Fail**: Domain only appears in supplementary mentions or footnotes

**C07: Cross-Engine Citation**
- **Pass**: Cited by >=3 different AI engines
- **Partial**: Cited by 2 AI engines
- **Fail**: Cited by 0-1 AI engines

**C08: Citation Sentiment**
- **Pass**: >=80% of citations are in positive or neutral context (domain presented as reliable source)
- **Partial**: 50-79% positive/neutral citations
- **Fail**: >50% of citations are negative (domain used as counterexample or unreliable source)

**C09: Editorial Link Ratio**
- **Pass**: >=60% of backlinks come from editorial decisions (in-content links from articles, guides, research)
- **Partial**: 30-59% editorial links
- **Fail**: <30% editorial links (dominated by directory listings, forum signatures, comment spam, sidebar widgets)

**C10: Link Source Diversity**
- **Pass**: Referring domains span >=3 industries and >=5 geographic regions
- **Partial**: 2 industries or 3-4 regions
- **Fail**: Concentrated in 1 industry or <3 regions

---

## I — Identity (10 items)

> How clearly is this domain recognized as a distinct entity in the information ecosystem?

**I01: Knowledge Graph Presence**
- **Pass**: Domain's parent entity exists in >=2 major knowledge graphs (Google Knowledge Graph, Wikidata, DBpedia, CrunchBase)
- **Partial**: Exists in 1 knowledge graph
- **Fail**: Not present in any knowledge graph

**I02: Brand Search Volume**
- **Pass**: Brand name has >=1,000 monthly searches (exact match)
- **Partial**: 100-999 monthly searches
- **Fail**: <100 monthly searches or no measurable brand search volume

**I03: Brand SERP Ownership**
- **Pass**: Searching the brand name yields >=7 first-page results controlled by the domain (own site + official social profiles)
- **Partial**: 4-6 controlled results
- **Fail**: <4 controlled results (brand SERP dominated by third parties or competitors)

**I04: Schema.org Coverage**
- **Pass**: >=50% of indexable pages have correct, content-type-appropriate Schema.org markup (Organization, Article, Product, FAQ, etc.)
- **Partial**: 20-49% coverage or markup present but incorrect types
- **Fail**: <20% coverage or no Schema.org markup

**I05: Author Entity Recognition**
- **Pass**: >=80% of content has attributed authors with verifiable public identities (LinkedIn, personal sites, or knowledge graph entries)
- **Partial**: 40-79% of content has attributed authors
- **Fail**: <40% of content has author attribution, or authors are unverifiable ("Admin", "Staff Writer")

**I06: Domain Tenure**
- **Pass**: Domain registered >=5 years with continuous active use (no extended dormancy periods)
- **Partial**: 2-4 years of active use, or older domain with gaps in activity
- **Fail**: <2 years of active use, or recently acquired expired domain

**I07: Cross-Platform Consistency**
- **Pass**: Brand name, logo, description, and contact info are identical across all official platforms (website, social media, directories, app stores)
- **Partial**: Mostly consistent with minor discrepancies (e.g., slightly different descriptions)
- **Fail**: Significant inconsistencies or contradictions across platforms

**I08: Niche Consistency**
- **Pass**: Domain has operated in the same niche for >=3 consecutive years without major pivots
- **Partial**: 1-2 years in current niche, or 1 minor pivot in history
- **Fail**: Frequent niche changes, or domain recently pivoted from an unrelated industry

**I09: Unlinked Brand Mentions**
- **Pass**: Brand name mentioned (without link) on >=50 distinct third-party pages
- **Partial**: 10-49 unlinked mentions
- **Fail**: <10 unlinked mentions
- Note: This measures pure reputation — mentions without link incentives

**I10: Query-Brand Association**
- **Pass**: Users frequently append brand name to industry queries (e.g., "SEO tools moz", "email marketing mailchimp"); visible in autocomplete
- **Partial**: Some query-brand association visible in search suggest
- **Fail**: No measurable query-brand association

---

# Part 7: T + E Dimensions — Detailed Criteria

> Detailed Pass/Partial/Fail criteria for all 20 Trust + Eminence check items.

---

## T — Trust (10 items)

> Are there red flags suggesting this domain's profile has been manipulated?

**T01: Link Profile Naturalness**
- **Pass**: Link growth curve follows a natural distribution; no single month accounts for >15% of total backlinks; growth correlates with content publishing
- **Partial**: Mostly natural with 1-2 anomalous periods (explainable by PR events or viral content)
- **Fail**: Obvious unnatural patterns: bulk acquisition months, step-function growth, or links appearing before content exists

**T02: Dofollow Ratio Normality**
- **Pass**: Dofollow links constitute 40-85% of total backlinks
- **Partial**: 85-90% dofollow (slightly elevated)
- **Fail**: >90% dofollow (strong manipulation signal) or <20% dofollow (abnormally low)

**T03: Link-Traffic Coherence** | **VETO ITEM**
- **Pass**: Organic traffic is proportional to backlink volume; ratio is within 2 standard deviations of industry norm
- **Partial**: Mild imbalance (e.g., new site with traffic lagging behind link growth)
- **Fail**: Extreme imbalance — thousands of referring domains but near-zero organic traffic -> **Veto triggered**
- Industry benchmarks: Content sites ~10-50 visits per referring domain; E-commerce ~5-20

**T04: IP/Network Diversity**
- **Pass**: Referring domains distributed across >=100 unique IP C-class ranges; no single C-class accounts for >5% of links
- **Partial**: 50-99 unique C-class ranges, or 1-2 C-classes slightly overrepresented
- **Fail**: <50 unique C-class ranges, or a single C-class accounts for >20% of links (PBN signature)

**T05: Backlink Profile Uniqueness** | **VETO ITEM**
- **Pass**: No other domain shares >60% of the same referring domains
- **Partial**: One domain shares 40-60% overlap (possible industry co-citation)
- **Fail**: Another domain shares >60% of referring domains -> **Veto triggered** (manipulation network)

**T06: WHOIS & Registration Transparency**
- **Pass**: WHOIS information publicly available; reputable registrar; consistent ownership for >=2 years
- **Partial**: Privacy-protected WHOIS (common for individuals) but reputable registrar and stable ownership
- **Fail**: Frequently changing ownership, suspicious registrar, or recently acquired expired/auctioned domain

**T07: Technical Security**
- **Pass**: Site-wide HTTPS with valid certificate; HSTS enabled; no malware, phishing, or unsafe content flags from Google Safe Browsing or similar services
- **Partial**: HTTPS present but missing HSTS, or minor mixed-content issues
- **Fail**: HTTP-only pages, expired certificates, or flagged by security services

**T08: Content Freshness Signal**
- **Pass**: New content published or existing content updated within the last 90 days
- **Partial**: Last update 90-365 days ago
- **Fail**: No content updates for >1 year (abandoned domain)

**T09: Penalty & Deindex History** | **VETO ITEM**
- **Pass**: No record of Google manual actions, penalties, or deindexing
- **Partial**: Had a penalty >2 years ago that was successfully resolved and recovered
- **Fail**: Active penalty, recent deindexing, or unresolved manual action -> **Veto triggered**

**T10: Review & Reputation Signals**
- **Pass**: Positive or neutral reviews (>=3.5/5 average) on >=2 third-party review platforms (Trustpilot, G2, BBB, Glassdoor, etc.)
- **Partial**: Reviews exist but mixed (3.0-3.4 average), or only on 1 platform
- **Fail**: Predominantly negative reviews (<3.0 average) or no review presence despite being a consumer-facing domain

---

## E — Eminence (10 items)

> How visible and influential is this domain across the information ecosystem?

**E01: Organic Search Visibility**
- **Pass**: Ranks for >=1,000 keywords across search engines (any position in top 100)
- **Partial**: Ranks for 100-999 keywords
- **Fail**: Ranks for <100 keywords

**E02: Organic Traffic Estimate**
- **Pass**: >=10,000 estimated monthly organic visits
- **Partial**: 1,000-9,999 monthly visits
- **Fail**: <1,000 monthly visits

**E03: SERP Feature Ownership**
- **Pass**: Appears in >=3 types of SERP features (Featured Snippets, Knowledge Panels, People Also Ask, Image Pack, Video Carousel, etc.)
- **Partial**: Appears in 1-2 SERP feature types
- **Fail**: No SERP feature appearances

**E04: Technical Crawlability**
- **Pass**: AI-crawler-friendly robots.txt (does not block major AI crawlers); clean server-side rendering; clear HTML structure; fast load times (<3s)
- **Partial**: Partially blocks AI crawlers or has minor rendering issues
- **Fail**: Blocks all AI crawlers, heavily JavaScript-dependent without SSR, or load times >10s

**E05: Multi-Platform Footprint**
- **Pass**: Official verified presence on >=3 major platforms (YouTube, LinkedIn, X/Twitter, Reddit, GitHub, etc.) with recent activity
- **Partial**: Present on 1-2 platforms or present but inactive
- **Fail**: No presence beyond the domain itself

**E06: Authoritative Media Coverage**
- **Pass**: Featured or cited in >=3 authoritative publications (major news outlets, industry publications like Forbes, TechCrunch, or domain-specific leaders)
- **Partial**: 1-2 media mentions
- **Fail**: No media coverage from authoritative sources

**E07: Topical Authority Depth**
- **Pass**: Ranks for long-tail keywords (4+ words) deep within its primary niche; covers specific sub-topics that generalist sites miss
- **Partial**: Some long-tail rankings but gaps in niche coverage
- **Fail**: Only ranks for broad/head terms; no depth in niche topics

**E08: Topical Authority Breadth**
- **Pass**: Content covers >=70% of sub-topics within the domain's primary niche (as identified by keyword clustering)
- **Partial**: Covers 40-69% of niche sub-topics
- **Fail**: Covers <40% of sub-topics (significant gaps in niche coverage)

**E09: Geographic Reach**
- **Pass**: Receives organic traffic from >=10 countries/regions
- **Partial**: 5-9 countries/regions
- **Fail**: <5 countries/regions (hyper-local unless intentionally local)

**E10: Industry Share of Voice**
- **Pass**: Holds >=5% visibility share across the domain's top 50 industry keywords (compared to competitors)
- **Partial**: 1-4% visibility share
- **Fail**: <1% visibility share or not ranking for most industry keywords

---

# Part 8: Advanced Reference

## AI Engine Citation Preferences

Each AI engine has different preferences for which domains to cite:

| Engine | Citation Style | Preferred Domain Signals | Priority CITE Items |
|--------|---------------|-------------------------|---------------------|
| **Google AI Overview** | Snippet extraction; favors structured content | High organic rankings, Schema.org, SERP features | E01, E03, I04, C01 |
| **ChatGPT (Browse)** | Conversational synthesis with citation links | Original data, authoritative sources, clear conclusions | C05, C06, I01, E06 |
| **Perplexity AI** | Multi-source synthesis + inline citations | Research-grade content, methodology transparency, tiered sources | C09, C10, E07, I05 |
| **Google Gemini** | Knowledge-grounded with entity recognition | Knowledge graph presence, brand recognition, topical authority | I01, I02, E07, E08 |
| **Claude** | Precision-first with balanced reasoning | Trustworthy sources, balanced perspectives, transparent methodology | T01-T10, C08, I08 |

### Top 6 CITE Priority Items for AI Visibility

| Rank | Item | Why It Matters |
|------|------|---------------|
| 1 | **C05** AI Citation Frequency | Direct measurement of whether AI engines already cite you |
| 2 | **I01** Knowledge Graph Presence | AI engines use knowledge graphs to verify entity identity |
| 3 | **T03** Link-Traffic Coherence | Veto item that can invalidate all other scores |
| 4 | **E07** Topical Authority Depth | AI engines prefer deep niche experts over generalist sites |
| 5 | **C01** Referring Domains Volume | Foundation signal — high-quality links remain the backbone of authority |
| 6 | **I04** Schema.org Coverage | Structured data helps AI engines understand and parse your content |

## CITE + CORE-EEAT Integration Map

How CITE domain-level items relate to CORE-EEAT content-level items:

| CITE Item | Related CORE-EEAT Items | Relationship |
|-----------|------------------------|--------------|
| C05-C08 (AI Citations) | C02 (Direct Answer), O02 (Summary Box), E01 (Original Data) | Domain gets cited when content is citable |
| I01 (Knowledge Graph) | A07 (Knowledge Graph Presence), A08 (Entity Consistency) | EEAT-A items build the identity that I items measure |
| I04 (Schema.org) | O05 (Schema Markup), R09 (HTML Semantics) | Content-level Schema contributes to domain-level coverage |
| I05 (Author Entity) | Ept01 (Author Identity), Ept02 (Credentials Display) | Content author signals build domain author recognition |
| T07 (Technical Security) | T03 (Security Standards) | Same signal, different scope (domain vs page) |
| E07-E08 (Topical Authority) | C03 (Query Coverage), E08 (Depth Advantage) | Content depth builds domain topical authority |

## Data Source Mapping

> Maps each check item to data sources, tools, and technical audit methods.

| Check Item | Data Source | Tools | Audit Method |
|-----------|------------|-------|-------------|
| C01 Referring Domains Volume | Backlink index | Ahrefs, Moz, SEMRush | API query: unique referring domains count |
| C02 Referring Domains Quality | Backlink index + authority scores | Ahrefs (DR of sources), Moz (DA of sources) | Aggregate authority of top 100 referring domains |
| C03 Link Equity Distribution | Outbound link analysis of sources | Ahrefs (outgoing links per domain) | Avg outbound domains of top 50 referring domains |
| C04 Link Velocity | Historical backlink data | Ahrefs (new/lost referring domains over time) | Month-over-month link growth trend analysis |
| C05 AI Citation Frequency | AI engine output monitoring | Manual testing, Perplexity API, AI citation trackers | Query 20+ niche questions across 4+ AI engines |
| C06 AI Citation Prominence | AI engine output analysis | Manual review of AI responses | Classify citations as primary/supplementary/footnote |
| C07 Cross-Engine Citation | Multi-engine monitoring | ChatGPT, Perplexity, Gemini, AI Overview, Claude | Count distinct engines that cite the domain |
| C08 Citation Sentiment | NLP sentiment analysis | AI output + sentiment classifier | Classify citation context as positive/neutral/negative |
| C09 Editorial Link Ratio | Backlink type classification | Ahrefs (link context), Majestic | Categorize links: editorial vs directory/comment/sidebar |
| C10 Link Source Diversity | Referring domain metadata | Ahrefs + IP geolocation + industry classification | Cluster referring domains by industry and geography |
| I01 Knowledge Graph Presence | Knowledge graph APIs | Google KG API, Wikidata SPARQL, DBpedia | Query entity name across knowledge graphs |
| I02 Brand Search Volume | Search volume data | Google Keyword Planner, SEMRush, Ahrefs | Exact-match monthly search volume for brand name |
| I03 Brand SERP Ownership | SERP analysis | SEMRush, Ahrefs (SERP checker) | Search brand name; count owned results on page 1 |
| I04 Schema.org Coverage | Technical crawl | Screaming Frog, Sitebulb, Google Rich Results Test | Crawl site; % of pages with valid Schema.org |
| I05 Author Entity Recognition | Author page analysis + KG | Manual review + Google KG API | Check author pages for verifiable public identities |
| I06 Domain Tenure | WHOIS + Web Archive | WHOIS lookup, Wayback Machine | Registration date + continuous activity verification |
| I07 Cross-Platform Consistency | Multi-platform scraping | Manual audit or brand monitoring tools | Compare brand info across website + social profiles |
| I08 Niche Consistency | Web Archive + content analysis | Wayback Machine + topic modeling | Historical content analysis over time |
| I09 Unlinked Brand Mentions | Brand mention monitoring | Google Alerts, Brand24, Mention.com | Count brand mentions minus linked mentions |
| I10 Query-Brand Association | Search suggest data | Google Autocomplete, SEMRush | Check if brand appears in industry query suggestions |
| T01 Link Profile Naturalness | Historical link data | Ahrefs (new referring domains timeline) | Statistical analysis of growth curve distribution |
| T02 Dofollow Ratio Normality | Link attribute data | Ahrefs, Moz (link attributes) | Calculate dofollow % of total referring domains |
| T03 Link-Traffic Coherence | Links + traffic estimates | Ahrefs/Moz (links) + SEMRush/SimilarWeb (traffic) | Ratio: organic visits per referring domain |
| T04 IP/Network Diversity | IP data of referring domains | Ahrefs (referring IPs), Majestic | Count unique C-class IP ranges; check concentration |
| T05 Backlink Profile Uniqueness | Cross-domain link comparison | Ahrefs (link intersect tool) | Check overlap % with other domains' link profiles |
| T06 WHOIS & Registration Transparency | WHOIS database | WHOIS lookup, DomainTools | Check registration info, registrar, ownership history |
| T07 Technical Security | Security scanners | Google Safe Browsing API, SSL Labs, SecurityHeaders | HTTPS check + security header audit + malware scan |
| T08 Content Freshness Signal | Crawl timestamps | Screaming Frog, Google Cache dates | Check last-modified dates across site pages |
| T09 Penalty & Deindex History | Google Search Console + archives | GSC Manual Actions report, Web Archive | Check for manual actions; verify index status |
| T10 Review & Reputation Signals | Third-party review platforms | Trustpilot API, G2 API, BBB | Aggregate ratings across review platforms |
| E01 Organic Search Visibility | Keyword ranking data | SEMRush, Ahrefs, Sistrix (Visibility Index) | Count keywords ranking in top 100 |
| E02 Organic Traffic Estimate | Traffic estimation models | SEMRush, Ahrefs, SimilarWeb | Estimated monthly organic visits |
| E03 SERP Feature Ownership | SERP feature tracking | SEMRush (SERP Features report), Ahrefs | Count distinct SERP feature types domain appears in |
| E04 Technical Crawlability | Technical audit | Screaming Frog, robots.txt analyzer | Check robots.txt AI crawler policies + render test |
| E05 Multi-Platform Footprint | Platform presence check | Manual audit or social media discovery tools | Verify official profiles on major platforms |
| E06 Authoritative Media Coverage | Media mention databases | Google News, Meltwater, Cision | Count authoritative media mentions |
| E07 Topical Authority Depth | Long-tail keyword rankings | Ahrefs (keyword report, 4+ word filter) | Count long-tail keyword rankings in primary niche |
| E08 Topical Authority Breadth | Topic clustering | SEMRush (Topic Research), MarketMuse | Map sub-topics covered vs total niche sub-topics |
| E09 Geographic Reach | Geographic traffic data | SEMRush (Traffic Analytics), SimilarWeb | Count countries with organic traffic |
| E10 Industry Share of Voice | Competitive visibility | SEMRush (Position Tracking), Sistrix | Calculate visibility % across top 50 industry keywords |

## Common Evaluation Mistakes

| # | Mistake | Item | Wrong | Right |
|---|---------|------|-------|-------|
| 1 | Ignoring AI citations | C05 | Only checking backlinks | Also monitor AI engine citations across major platforms |
| 2 | Counting total links, not domains | C01 | "We have 50,000 backlinks!" | Count unique referring domains, not total link count |
| 3 | Link quality conflated with quantity | C02 | 10,000 low-authority links = good | 200 high-authority editorial links > 10,000 directory links |
| 4 | Ignoring entity identity | I01 | Focus only on links and traffic | Check knowledge graph presence; it's how AI verifies sources |
| 5 | Neglecting Schema markup | I04 | "Schema doesn't matter for authority" | Schema helps AI engines understand your domain's scope |
| 6 | Not checking veto items first | T03 | Full evaluation before checking fundamentals | Always check T03, T05, T09 first — they can invalidate everything |
| 7 | Treating abandoned domains as trustworthy | T08 | "Old domain = authoritative domain" | A domain dormant for 3 years has decayed authority |
| 8 | Overlooking AI crawler policies | E04 | Blocking all bots for "security" | Review robots.txt; blocking AI crawlers kills GEO potential |
| 9 | Equating social presence with authority | E05 | "We have 100K followers = high authority" | Social presence is one of 40 items, not a proxy for overall authority |
| 10 | Using single-metric shortcuts | — | "Our Moz DA is 60, so we're good" | No single metric captures the full picture; CITE evaluates 40 signals |

## MECE Disambiguation Rules

When unsure which dimension a signal belongs to:

| Rule | Assign To |
|------|-----------|
| "Someone referenced/linked to us" | C (Citation) |
| "Our link profile looks suspicious" | T (Trust) |
| "We exist in the knowledge graph" | I (Identity) |
| "We rank for keywords / get traffic" | E (Eminence) |

### Commonly Confused Pairs

| Pair | Disambiguation |
|------|---------------|
| **C01 (Referring Domains)** vs **E01 (Organic Visibility)** | C01 = who links to you (input); E01 = where you rank (output) |
| **I09 (Unlinked Mentions)** vs **E06 (Media Coverage)** | I09 = any third-party mention without a link; E06 = authoritative media specifically |
| **I08 (Niche Consistency)** vs **E07/E08 (Topical Authority)** | I08 = how long you've stayed in one niche (identity); E07/E08 = how deep/broad your rankings are (visibility) |
| **C09 (Editorial Link Ratio)** vs **T01 (Link Naturalness)** | C09 = positive quality (what % are editorial); T01 = negative detection (is the growth pattern natural) |
| **T06 (WHOIS Transparency)** vs **I06 (Domain Tenure)** | T06 = is the registration suspicious (trust); I06 = how long has it been active (identity) |

---

## Changelog

- **v1.0** (2026-02-10): Initial release — open domain authority standard for the GEO era; 4 dimensions, 40 items, 6 domain types

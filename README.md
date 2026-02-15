# TalentFlux: AI-Driven Career Roadmap

**SkillGap Monitor** is a professional-grade SaaS platform designed to solve the problem of "Skill Obsolescence" in the fast-paced 2026 tech market. It utilizes **Web Scraping**, **Natural Language Processing (NLP)**, and **Vector Mathematics** to provide job seekers with a real-time roadmap to employability.


## Problem Statement

* **Information Overload:** Thousands of job descriptions are posted daily, making it impossible for humans to track emerging trends manually.
* **Semantic Gap:** Traditional job portals use basic keyword matching (e.g., searching for "React"), which fails to understand the context or related technologies (e.g., "Next.js Server Components").
* **Static Skills vs. Dynamic Market:** Professionals often learn tools that are already losing demand, leading to a "Skill Gap" between their expertise and actual market needs.


##  AI & Research Focus (The Core)

This project is built as a **Computer Science Research Study** focused on **Computational Labor Economics** and **NLP**.

### 1. Named Entity Recognition (NER)

* **Technology:** Gemini 1.5 Flash / GPT-4o-mini via **Vercel AI SDK**.
* **Task:** The AI acts as a classifier to distinguish between "Required Skills," "Preferred Experience," and "Soft Skills" within unstructured HTML data.

### 2. Semantic Vector Embeddings

* **Technology:** OpenAI `text-embedding-3-small` & **Supabase Vector (pgvector)**.
* **Math:** Uses **Cosine Similarity** to compare High-Dimensional Vectors ( dimensions).
* **Research Potential:** Evaluating how "Semantic Similarity" outperforms "Keyword Matching" in Applicant Tracking Systems (ATS).

### 3. Temporal Skill-Drift Analysis

* **Research Goal:** Measuring the "Velocity" of technology adoption.
* **Proposed Paper Title:** *"Predictive Modeling of Labor Market Requirements: A Vector-Based Approach to Skill Decay and Adoption."*

---

##  Technical Stack

* **Framework:** [Next.js 15](https://nextjs.org/) (App Router & Server Actions)
* **Scraping:** Puppeteer / Playwright (Headless Browser automation)
* **AI SDK:** Vercel AI SDK (for LLM orchestration)
* **Database:** [Supabase](https://supabase.com/) (PostgreSQL with `pgvector` extension)
* **Deployment:** [Vercel](https://vercel.com/) (Free Tier)
* **UI/UX:** Tailwind CSS + shadcn/ui

---

## Application Workflow

1. **Resume Ingestion:** User uploads a resume; the system parses text and generates a **User Skill Vector**.
2. **Market Scrape:** The app triggers a server-side scraper to fetch the latest  jobs for a specific role and location.
3. **AI Distillation:** An LLM processes the scraped text to create a **Market Demand Profile**.
4. **Gap Analysis:** The system calculates the similarity score.
5. **Intelligence Dashboard:** * **Skill Gap Score:** A percentage match.
* **Rising Stars:** Technologies gaining momentum this month.
* **Learning Path:** AI-generated links to bridge the identified gaps.



---

##  Why This Project Matters

* **For Users:** It provides a data-driven path to their next job, removing the "guesswork" of what to learn next.
* **For Researchers:** It provides a framework for understanding how quickly the tech industry evolves and how AI can automate career counseling.


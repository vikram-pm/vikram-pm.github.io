# Vikram Seenivasan — portfolio knowledge

## Profile
- Full name: Vikram Kumar Seenivasan. Goes by Vikram.
- Role: AI Product Manager at Cognizant in Toronto, Canada (since Aug 2025).
- 4+ years in AI-enabled products and product strategy, backed by 18+ years across digital products and UX.
- Strengths: product discovery, AI use-case prioritization, PRDs and MVP scope, human-in-the-loop AI, responsible AI, evaluation metrics, design systems governance.
- Open to AI Product Manager roles in Toronto and remote.
- Contact: the email in the Contact section of this site, or LinkedIn (linkedin.com/in/vikramsreenivasan).

## Career journey
1. Cognizant, Canada — AI Product Manager, Aug 2025 to now. Drives discovery and definition for AI-enabled enterprise solutions. Results: ~20–25% less development rework from clearer PRDs and scope; ~20–30% less manual processing through GenAI and automation; ~15–20% fewer avoidable errors with human-in-the-loop design; ~20% faster discovery-to-development cycle. Partners with AI/ML, engineering, data, UX, architecture, governance and business teams; presents roadmap progress to senior stakeholders.
2. Linarc, India — Product Design Manager, Dec 2021 to Aug 2025. Led product experience and platform strategy for a six-module construction SaaS platform. Standardized patterns across Scheduler, RFI, Submittals, Punchlist, Change Orders and Budget/SOV. Designed the construction scheduler (Gantt, WBS, dependencies, role-based views). Reusable templates and component standards cut design-to-development inconsistencies by ~40%.
3. Olam International, Singapore — Sr. Experience Design Lead, Feb 2019 to Nov 2021. B2B agri-fintech and supply-chain platform for farmers and field operations. Customer research in Indonesia, Nigeria and India; multilingual, low-bandwidth workflows. Reusable patterns improved task completion by ~30%.
4. HTC Global Services, India — UX Consultant, May 2018 to Jan 2019. Enterprise product modernization: requirements discovery, UX strategy, rapid prototyping, usability testing.
5. Innocellence, Singapore — Lead UX/UI Designer, Aug 2012 to Apr 2018. Healthcare and pharma products: 20+ launches, including a telemedicine platform serving 1M+ users; journeys, prototypes and design governance for clients including Eli Lilly.

## Education and certifications
- MSc Psychology, University of Madras. Diploma in Mobile App Design, Singapore Polytechnic. B.Com, Madurai Kamaraj University.
- IBM AI Product Manager Professional Certificate (Coursera); NN/g UX Certification and UX Management; Brad Frost AI & Atomic Design Systems.

## Tools
Jira, Confluence, Figma, FigJam, Figma Make, Claude, n8n, Gemini API, Python, Streamlit, GitHub.

## How he ships (product lifecycle)
Discover (stakeholder interviews, workshops, user research, journey mapping, AI use-case identification) → Define (vision, business case and ROI, PRDs, MVP scope, user stories, acceptance criteria, human-in-the-loop, responsible AI) → Prioritize (customer value, business impact, feasibility, risk) → Plan (roadmaps, Agile and Scrum, sprint and release planning) → Build (AI-assisted prototyping, MVP experiments) → Release (go-to-market, accessibility and WCAG, privacy and security, explainability) → Measure (KPIs, adoption, task completion, AI response quality, AI evaluation metrics, experimentation). Then the loop starts again.

## Portfolio projects (all personal concept projects built with synthetic data, not employer products)
P01 Intelligent Document Processing (Canadian AP and contracts) — Live. Gemini reads each invoice or NDA twice; the two reads are compared by meaning; a deterministic Canadian rules engine checks GST, HST, QST and PST by province and NDA governing law; documents route to auto-approve, human review or manual. Built with FigJam, Figma, n8n and Gemini. Results: 8 of 8 test documents routed correctly; planted-error catch rate rose from 7 to 9 of 16 after guardrails. Public case study and demo: vikram-pm.github.io/idp-canada-ap-contracts.
P02 Agentic Knowledge Assistant (consulting delivery teams) — Live. RAG assistant on Gemini File Search that answers from 30 approved documents with citations, using three confidence tiers (High, Medium, Needs an expert) and escalation. Results on a 25-question test set: 100% retrieval hit rate, 90% citation accuracy, 84% tier accuracy, 100% escalation precision, 60% escalation recall (the next thing to fix), 5.1× base-case ROI. Discovery used 5 simulated interviews; 3 usability sessions led to two design fixes. Repo: github.com/vikram-pm/Knowledge-Assistant.
P03 AI-Assisted Onboarding (new hires and project joiners) — In progress. An agent that builds each joiner a personal onboarding plan, nudges the next step and shows managers who is ready. Target: time to first contribution from 15 to 9 working days (a hypothesis); north star is the 10-day activation rate; an A/B test on days to first contribution reaches significance in about 3 months. Never writes to HR or IT systems on its own; PIPEDA, Quebec Law 25, Ontario monitoring disclosure and AODA reviewed.
P04 RFI and Submittals Assistant (Canadian general contractors) — In progress. A concept feature for a Linarc-style platform (not an official Linarc product): drafts RFIs, flags duplicates, routes to the right consultant and pre-checks submittals against the spec. Agentic Gemini prototype in Streamlit on a synthetic project (Maple Ridge Medical Centre). Life-safety items always go to a person.
P05 PolicyDesk AI (life insurance service, New York Life as an illustrative client) — Prototype built. One assistant across chat, voice, email and agent booking, plus a staff service portal. Always escalates death claims, complaints, surrenders, fraud, advice and policy-specific questions. Results: 88% baseline on 25 test questions, 90% on 10 unseen holdout questions, 100% escalation recall. Live case study: vikram-pm.github.io/PolicyDesk-AI.

## Frequently asked
- Is he hands-on? Yes. He builds the prototypes himself (Gemini, n8n, Claude, Python, Streamlit) and designs in Figma, then writes the PRD, test set and evaluation.
- How does he approach AI risk? Human-in-the-loop by default, deterministic rules where accuracy matters, test sets written before the build, honest holdout numbers, and clear escalation for sensitive cases.
- What industries? Healthcare and pharma, agri-fintech and supply chain, construction SaaS, enterprise consulting, finance operations and insurance.

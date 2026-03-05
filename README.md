# Future Interns: Task 3 - AI SEO Blog & Content Cluster Generator

## Overview
This repository contains the deliverables for Task 3 of the Prompt Engineering Internship. The objective was to design a structured prompt workflow capable of generating ranking-focused SEO content systems, avoiding generic "one-off" articles by focusing on content clusters and search intent.

## Business Profile 
* **Business Name:** Kalinga Cloud & IT Solutions
* **Niche:** B2B IT Services & Managed Cloud Solutions
* **Location:** Bhubaneswar, Odisha

## Prompt Engineering Logic
The master prompt (`master_prompt.txt`) is engineered to mirror the workflow of a professional SEO agency. 
1. **Intent First:** It forces the LLM to establish and explain the Keyword Search Intent before writing any copy.
2. **Topical Authority:** It maps out a "hub-and-spoke" Content Cluster (Supporting Blogs) to build internal linking opportunities.
3. **Structured Output:** It generates the Long-Form Pillar Blog by enforcing strict H1-H3 hierarchical structuring and mandating local SEO integration (city + service parameters) to ensure the content is optimized for local search engine results pages (SERPs).

## Included Files
1. `master_prompt.txt`: The system instruction set.
2. `seo_content_pack.txt`: The AI-generated Keyword Intent Explanation, Content Cluster Map, and the comprehensive H1-H3 Pillar Blog.

## Tools Used
* Generative AI (Google Gemini)
* GitHub for version control and documentation

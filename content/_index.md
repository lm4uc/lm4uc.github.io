+++
title = "Language Models for Underserved Communities"
extra.tagline = "AAAI 2026 Workshop"
extra.subtitles = ["Singapore", "January 27, 2026"]
extra.buttons = [
    {name="Submit Paper", url="https://openreview.net/group?id=AAAI.org/2026/Workshop/LM4UC"},
    {name="Submit Shared Task", url="https://openreview.net/group?id=AAAI.org/2026/Workshop/LM4UC_Shared_Task"},
    {name="Join Discord", url="https://discord.gg/wfwXhYUN2W"},
    {name="LM4UC@2025", url="/2025/"}
]
+++

## Call for Papers

Underserved communities often lack adequate access to advanced natural language processing (NLP) technologies due to limited linguistic data, insufficient computational resources, or inadequate AI governance frameworks. This gap hinders equitable access to NLP advancements, exacerbating the digital divide. Our workshop aims to address this by fostering a multidisciplinary dialogue around the development of language models (LMs) that prioritize cultural sensitivity, resource efficiency, and sustainable AI practices. We invites researchers, practitioners, and policymakers to address challenges and propose innovative solutions for building and deploying language models for underserved languages and communities.

### Topics of Interest

We invite submissions of full papers, ongoing work, position papers, and survey papers on topics including, but not limited to:

1. **Measuring and Governing AI**  
   Developing reliable evaluation methods for LMs under constraints in data, compute, and expertise. How can psychometrics, auditing frameworks, or validity theory guide responsible measurement and governance?

2. **Benchmarking and Fairness**  
   Building inclusive benchmarks and evaluation pipelines that reduce bias, improve cultural and linguistic representation, and ensure fair performance across underserved communities.

3. **Pluralistic Alignment**  
   Designing approaches for aligning LMs with diverse values, cultural norms, and epistemologies, including participatory and community-driven methods.

4. **Open and Inclusive Infrastructure**  
   Creating open datasets, benchmarks, models, and participatory platforms that support sustainable and equitable NLP research and deployment.


## Submission Guidelines

We welcome long papers (**8 pages**) and short papers (**4 pages**), excluding references. Submissions must follow the [**AAAI 2026 style guidelines**](https://aaai.org/conference/aaai/aaai-26/submission-instructions/).

### Important Dates
- **Submission deadline**: <s>November 14, 2025</s> <s>November 20, 2025</s> November 24, 2025
- **Notification of acceptance**: December 12, 2025
- **Camera-ready paper due**: January 10, 2026
- **Workshop dates**: January 27, 2026

Please note that all the deadlines are in **AoE (Anywhere on Earth)** timezone.

### Submission Link
Papers should be submitted via [OpenReview](https://openreview.net/group?id=AAAI.org/2026/Workshop/LM4UC).

## Contact Us

For inquiries, please contact the workshop organizers: [**lm4uc.organizers (at) gmail.com**](mailto:lm4uc.organizers@gmail.com)

Alternatively, you can reach us via our [**Discord server**](https://discord.gg/wfwXhYUN2W).

{{ new_block() }}

# Shared Task: AI Measurement for the Public Interest

In this year, we are excited to announce a shared task on "AI Measurement for the Public Interest," organized as part of the Language Models for Underserved Communities (LM4UC) workshop at AAAI 2026. The shared task aims to foster the development of evaluation methodologies and infrastructures that prioritize the needs of underserved communities, focusing on context-aware and institutionally grounded measurement practices.

This shared task invites participants to design and prototype evaluation workflows tailored to underserved linguistic and cultural contexts. The focus is not on optimizing model performance, but on developing measurement infrastructures that reflect how institutions, researchers, and communities actually assess and deploy language technologies under varied resource, governance, and environmental constraints. The task is organized around three complementary layers of an evaluation ecosystem:

1. **AI Evaluation Infrastructure and Stewardship** — *Where and how evaluation is conducted.* This includes workflows that enable local institutions to run assessments, control access to evaluation assets, and maintain their own scoring and deployment environments.
2. **AI Measurement Design** — *What is being measured and how it is operationalized.* This includes defining new evaluation dimensions, benchmarks, scoring criteria, and documentation practices that capture capabilities relevant to local use cases.
3. **AI Downstream Impact Assessment** — *How system behavior varies across populations, domains, or deployment settings.* This includes methods for quantifying performance variation, robustness, or utility across communities and identifying areas needing further capability development.

These layers together support end-to-end evaluation: designing the evaluation environment, specifying meaningful constructs, and analyzing performance in real deployments. Submissions may address any layer independently or propose workflows that integrate multiple layers. The shared task welcomes contributions such as datasets, protocols, analysis pipelines, benchmark definitions, evaluation software, and institutional frameworks. Submissions will be evaluated on clarity, methodological rigor, practical feasibility, and relevance to settings where existing benchmark infrastructure is limited or mismatched to local priorities. This initiative reflects LM4UC’s broader goal of advancing scalable, context-aware measurement infrastructures that support the long-term development of language technologies beyond traditional benchmark settings.

## Track 1: AI Evaluation Infrastructure & Stewardship
This track focuses on designing evaluation workflows that can be operated by local institutions rather than relying on centralized infrastructure. Submissions may include device-side evaluation, federated scoring, offline test packages, access-controlled scoring interfaces, or procedures for maintaining and updating evaluation assets over time. We are looking for clear and feasible mechanisms that allow organizations to run evaluations, control access to evaluation artifacts, and adapt workflows to their institutional constraints. Deliverables include, but are not limited to, a process card or documentation outline describing the evaluation pipeline design and usage constraints, a workflow diagram or prototype demonstrating how the evaluation is run end-to-end, and a short technical memo (about four pages) detailing assumptions, governance structure, and system requirements.

## Track 2: AI Measurement Design
This track invites new evaluation dimensions that capture aspects of model behavior relevant to real-world use cases not covered by existing benchmarks. Submissions may define cultural, linguistic, functional, domain-specific, communicative, or socio-institutional constructs and propose schemas, item formats, scoring procedures, and documentation standards. We are looking for well-defined constructs with clear motivating use cases, explicit assumptions, and verifiable measurement strategies.  Deliverables include, but are not limited to, a benchmark schema or dataset card describing the construct, example items or evaluation prompts with scoring criteria, and a short write-up (≈4 pages) explaining construct definition, related work, and measurement rationale.


## Track 3: AI Downstream Impact Assessment
This track focuses on methods that assess how model performance varies across contexts—e.g., across languages, institutions, domains, or deployment environments. Submissions may include empirical studies, diagnostic dashboards, error analyses, reliability studies, or pipelines that surface capability gaps. We look for clear methodologies for quantifying variation in behavior across settings and interpreting those differences in terms of practical deployment needs. Deliverables include, but are not limited to, a report or dashboard summarizing comparative results, a reproducible analysis pipeline or evaluation notebook, and a brief documentation (≈4 pages) clarifying assumptions, data sources, and interpretive limitations.

Please contact us on Discord or email if you are interested in participating in the shared task. We are open via appointment to help facilitate team formation, find resources, and brainstorm ideas with you. 

**Important Dates**
- Submission deadline via OpenReview: January 9, 2025
- Feedback release: January 16, 2025
- Submission portal: [OpenReview](https://openreview.net/group?id=AAAI.org/2026/Workshop/LM4UC_Shared_Task)


{{ new_block() }}

# List of Speakers

{{ grid(
    text = [
        ["Simon Chesterman","NUS | AI Singapore"], 
        ["Jian Gang Ngui","AI Singapore"],
    ],
    urls = [
        "https://law.nus.edu.sg/people/simon-chesterman/",
        "https://www.linkedin.com/in/jian-gang-ngui/",
    ],
    image_dir = "organizers",
    narrow = true) }}



{{ new_block() }}



# List of Organizers

{{ grid(
    text = [
        ["Sang Truong", "Stanford"],
        ["Sarah Luger", "MLCommons"],
        ["Rafael Mosquera", "MLCommons"],
        ["Duc Nguyen", "NUS"],
        ["Fagun Patel", "Stanford"],
        ["Francesca Vera", "Stanford"],
        ["Tracy Navichoque", "Stanford"],
        ["Sanmi Koyejo", "Stanford"],
    ],
    urls = [
        "https://ai.stanford.edu/~sttruong/",
        "https://www.linkedin.com/in/sarahluger/",
        "https://www.linkedin.com/in/rafael-mosquera",
        "https://comp.nus.edu.sg/~nqduc/",
        "https://www.linkedin.com/in/fagunpatel98/",
        "https://www.linkedin.com/in/ma-francesca-vera/",
        "https://hai.stanford.edu/people/tracy-navichoque",
        "https://cs.stanford.edu/~sanmi/",
    ],
    image_dir = "organizers") }}


{{ new_block() }}


# Schedule

[TBD]


{{ new_block() }}

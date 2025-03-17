+++
title = "NAACL Workshop: Language Models for Underserved Communities"
+++

## Call for Papers

In the evolving landscape of AI, NLP advancements have potential across diverse sectors, yet underserved communities often miss out on these benefits. Due to limited resources, computational models, or commercial interests, many languages—such as Indigenous, regional dialects, and those spoken by smaller populations—remain unsupported by advanced NLP technologies. These include languages like Yoruba, Igbo, Native American languages, and minority languages in multilingual countries such as India, China, and Indonesia.

This workshop seeks to advance NLP for underserved communities, addressing unique challenges in deploying language models (LMs) to enable equitable, sustainable, and culturally sensitive NLP technologies. Our framework centers on three key pillars:

1. **AI Governance**: Developing legal and ethical frameworks for NLP, ensuring fairness, transparency, and respect for data sovereignty and cultural rights.
2. **Cultural NLP**: Building culturally nuanced models that understand and preserve language-specific terms and values, safeguarding linguistic diversity.
3. **Sustainable NLP**: Creating resource-efficient, scalable models suitable for low-resource and environmentally constrained contexts.

We invite full and short papers on the following (but not limited to) topics:

- **Democratization**: Democratization of AI, open access data & models, community-driven LLMs
- **Data Sovereignty**: Data ownership & protection for language data
- **Legal Concerns**: Ethical LLMs, privacy in language data, intellectual property for LLMs
- **Preserving Diversity in LLMs**: Human-centric data collection for endangered languages, LLMs for minority languages
- **Preserving Cultural Norms**: Encoding cultural norms, training & evaluating culturally specific LLMs
- **Efficient LMs for Broader Accessibility**: Efficient LLMs, model compression, distributed computing, transfer learning, and knowledge distillation

This workshop will explore cutting-edge research and methodologies to develop and deploy LLMs for underserved communities, from training to deployment. By gathering insights from AI governance, cultural NLP, and sustainable NLP, we aim to create inclusive, impactful NLP technologies.

## Submission Details
- **Submission Deadline**: <s>January 30, 2025</s> February 7, 2025
- **Pre-reviewed (ARR) Submission Deadline**: February 20, 2025
- **Notification of Acceptance**: March 01, 2025
- **Workshop Date**: May 04, 2025
- **Submission Format**: We welcome long papers (8 pages) and short papers (4 pages), excluding references. Submissions are double-blind and must follow the [ARR guidelines](https://aclrollingreview.org/cfp#paper-submission-information).

We accept both archival and non-archival submissions. Accepted papers that choose the archival track will be published in the NAACL workshop proceedings and archived on the workshop website. For inquiries, please contact the workshop organizers through this email: **lm4uc.organizers (at) gmail.com**.

We look forward to contributions that drive innovation and inclusivity in NLP, supporting underserved communities globally. 


{{ new_block() }}



# List of Speakers

{{ grid(
    text = [
        ["Timothy Baldwin","MBZUAI"], 
        ["Timnit Gebru","Google"],
        ["Pratyusha Kalluri","Stanford"],
        ["David Ifeoluwa Adelani", "McGill"],
    ],
    urls = [
        "https://mbzuai.ac.ae/study/faculty/timothy-baldwin/",
        "https://en.wikipedia.org/wiki/Timnit_Gebru",
        "https://pkalluri.github.io/",
        "https://dadelani.github.io/",
    ],
    image_dir = "organizers",
    narrow = true) }}



{{ new_block() }}



# List of Organizers

{{ grid(
    text = [
        ["Sang Truong", "Stanford"],
        ["Rifki Afina Putri", "KAIST"],
        ["Duc Nguyen", "VNU-HCMUT"],
        ["Angelina Wang", "Stanford"],
        ["Daniel Ho", "Stanford"],
        ["Alice Oh", "KAIST"],
        ["Sanmi Koyejo", "Stanford"],
    ],
    urls = [
        "https://ai.stanford.edu/~sttruong/",
        "https://rifkiaputri.github.io/",
        "https://martinakaduc.github.io/",
        "https://angelina-wang.github.io/",
        "https://law.stanford.edu/daniel-e-ho/",
        "https://aliceoh9.github.io/",
        "https://cs.stanford.edu/~sanmi/",
    ],
    image_dir = "organizers") }}


{{ new_block() }}



# Schedule

| Time             | Event                        |
| ---------------- | ---------------------------- |
| 09:00am - 09:30am | Opening: Alice Oh           |
| 09:30am - 10:30am | Keynote                     |
| 10:30am - 11:30am | Coffee / Networking Break   |
| 11:30am - 12:30pm | Panel Discussion 1          |
| 12:30pm - 01:30pm | Lunch Break                 |
| 01:30pm - 03:00pm | Oral Presentation           |
| 03:00pm - 04:00pm | Panel Discussion 2          |
| 04:00pm - 05:00pm | Poster Session              |
| 05:00pm - 05:30pm | Award & Conclusion: Sanmi Koyejo |



{{ new_block() }}



# Accepted Papers

{{ table(
    data = "papers.csv", 
    button_names = ["Paper"], 
    button_data_columns = [4], 
    button_output_columns = [1]) }}



{{ new_block() }}

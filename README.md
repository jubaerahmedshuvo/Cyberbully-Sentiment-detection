Summary

>Automated moderation of social media comments to classify posts into five categories: political, sexual, troll, threat, and neutral.

>Online platforms face scale and speed challenges moderating harmful content. A deep learning classifier enables timely triage and policy enforcement for community standards.

>Build a custom text classifier using a character/word hybrid embedding with a 1D-CNN + BiLSTM architecture. Compare it with at least one alternative custom deep model (e.g., >pure CNN or pure BiLSTM) under identical training conditions. Follow the full CRISP‑DM lifecycle: business understanding, data understanding, preparation, modeling, evaluation, deployment.

>6,010 labeled posts evenly distributed across five classes, scraped from YouTube, Facebook, and Twitter. The dataset is balanced; we’ll verify quality, clean noise, and standardize formatting.

 >Achieve robust macro‑F1 and calibration suitable for moderation pipelines. Provide thresholded confidence outputs and rationale snippets for review tooling.

>Reduce moderation backlog, standardize enforcement, and provide analytics on incident types to inform policy and education.

 >Deploy as a REST API (Flask) with a lightweight moderation dashboard. Include a presentation demonstrating stakeholders’ KPIs: accuracy, latency, and false positive/negative risks.


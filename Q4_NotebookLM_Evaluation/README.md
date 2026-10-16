# Q4 – NotebookLM Evaluation Evidence

## Evaluation scenario

NotebookLM was evaluated as an academic assistant for preparing a briefing on Australia’s mandatory climate-related reporting framework. The investigation focused on reporting thresholds, implementation dates, AASB S2 disclosure requirements and the regulatory roles of ASIC, the AASB and Treasury.

## Sources used

Three authoritative sources were uploaded:

1. ASIC Regulatory Guide 280 – Sustainability Reporting
2. AASB S2 – Climate-related Disclosures
3. Australian Treasury – Climate-related Financial Reporting guidance

Using authoritative sources provided a suitable basis for testing source-grounded answers, citation quality and factual reliability.

## Features tested

| Feature | Academic use demonstrated | Main result |
|---|---|---|
| Source-grounded chat | Compared reporting groups, thresholds, commencement dates and regulatory roles | Produced relevant answers grounded in the uploaded sources |
| Inline citations | Opened citations and checked claims against source passages | Most citations supported the claims, but some required manual verification |
| Comparison table | Organised complex requirements into a structured summary | Useful for comparing reporting cohorts and regulatory responsibilities |
| Briefing document | Generated a concise ESG reporting briefing | Efficient starting point, but required fact-checking and editing |
| Study guide | Converted source material into revision notes | Useful for exam preparation and identifying key concepts |
| Audio Overview | Generated a 4-minute 58-second spoken explanation | Accessible and engaging, but introduced factual oversimplifications |
| Interactive quiz | Tested understanding of reporting requirements | Score was 3/10, with seven incorrect answers and no skipped questions |

## Experiment findings

### Source-grounded question answering

NotebookLM successfully identified the three implementation dates and the main corporate-size thresholds. It also distinguished the roles of ASIC, the AASB and Treasury. The source-grounded format was useful because citations could be opened and checked against the original documents.

An audit prompt was used to verify numerical thresholds, entity cohorts, the two-of-three size test, commencement dates and regulatory responsibilities. This identified an internal parsing label, `SOURCE_IMAGE_1`, which was not an acceptable citation. The affected output was corrected using specific AASB S2 and ASIC RG 280 paragraph, page and table references.

### Generated briefing and study guide

The briefing document and study guide efficiently transformed lengthy regulatory documents into structured academic notes. They were useful for identifying key themes, preparing summaries and supporting revision. However, generated material remained a secondary interpretation and could not replace reading the authoritative sources.

### Audio Overview

The Audio Overview was clear and suitable for introductory revision, but manual comparison with the uploaded sources identified several problems:

- It implied that Treasury directly writes legislation rather than leading policy development.
- It oversimplified ASIC RG 280 as an enforcement mechanism.
- It described some reporting thresholds using “or,” although the corporate-size test requires meeting at least two of three criteria.
- It presented climate-scenario assumptions with more certainty than the source justified.
- It made speculative statements about impacts on small suppliers.

The audio should therefore be treated as a learning aid rather than authoritative evidence.

### Interactive quiz

The quiz provided active recall practice and immediate explanations. The recorded result was 3/10, with seven incorrect answers and zero skipped questions. Reviewing the explanations helped expose misunderstandings and demonstrated the value of retrieval practice. Quiz wording and answers should still be checked against the source documents.

## Critical evaluation

### Accuracy and relevance

NotebookLM generally produced relevant, source-focused outputs, especially when prompts requested exact citations. Accuracy declined when information was transformed into conversational audio or simplified summaries. Citation availability improved transparency but did not guarantee that every interpretation was correct.

### Usefulness in academic workflows

The tool was valuable for source comparison, revision materials, briefing preparation, citation discovery, audio learning and self-testing. It could save time during early research and help students navigate long documents.

### Limitations and risks

Key risks included oversimplification, unsupported inference, citation-parsing errors, misplaced confidence and student over-reliance. Uploaded university or organisational documents may also contain personal, confidential or commercially sensitive information. Students should avoid uploading restricted material unless institutional privacy and data-governance requirements are satisfied.

## Overall conclusion

NotebookLM is suitable for limited, supervised academic use as a research and learning assistant. It should not be treated as an authoritative decision-maker or substitute for original sources. High-quality use requires authoritative inputs, precise prompts, citation verification, human review and transparent acknowledgement of AI assistance.

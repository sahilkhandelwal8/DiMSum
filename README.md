# DiMSum
Summarizing EHR data using Transformers

A Method to Automate the Discharge Summary

Abstract

Physicians spend approximately two hours in the electronic health
record (EHR) for every one hour of patient care. The time required for
recording, reviewing and summarizing information in EHRs has imposed
complex and burdensome workflows on physicians, which has
contributed to burnout. To alleviate documentation burden, multiple
efforts have pursued automated summary of the hospital patient record
through natural language processing (NLP) . When a patient is
discharged from a hospital, a physician authors a discharge summary, a
transition of care document that summarizes the patient’s hospital stay
and is sent to providers who continue the patient’s care in other settings.
While the discharge summary is both required and valuable, clinical
workflow can delay its availability, which can increase the risk of
rehospitalization and medication errors . In the United States, the
content of this document can only include information that has already
been documented within the EHR . In generating a discharge summary,
physicians spend most of their time manually writing the hospital course
section, a textual narrative that describes the progress of treatment for
the patient from admission to discharge. Automating this section could
potentially save time for physicians, as note templates have automated
other sections of the discharge summary but not the hospital course
section.
We propose using transformers for our objective. When using
transformers with smaller datasets, the recommended best approach is
to fine-tune a pre-trained model. We plan to leverage such models from
HuggingFace and perform necessary alterations

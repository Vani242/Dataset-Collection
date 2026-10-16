# Question Generation Pilot Dataset

This repository contains a small pilot dataset for the question-generation
research project. It is meant to help review the dataset format and annotation
fields.

## Files

- `question_generation_pilot_dataset_v0_1.csv` — pilot examples for use in code
- `question_generation_pilot_dataset_v0_1.xlsx` — the same data with a methods note

## What’s in the dataset

Each row contains a source passage, a question, an answer supported by that
passage, a question type, and source information.

## Status and limitations

The 18 questions were written manually from the project brief and course
syllabus. They are not outputs from the model and are not the held-out corpus
or timestamped news dataset.

Coverage has not been measured. The novelty labels only indicate that
duplicates were not intentionally included in this small pilot.

Note: This repository contains a schema-only pilot to illustrate the proposed dataset format. It is not the completed evaluation dataset.

## Next steps

Review the fields with the project supervisor. Then build the evaluation
dataset from approved source documents and measure coverage, redundancy,
novelty, and answer grounding.

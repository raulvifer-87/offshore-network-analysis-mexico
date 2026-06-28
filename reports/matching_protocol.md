# Matching Protocol

## Objective

This protocol defines how candidate matches are identified, classified and validated in the project.

## Data sources

The project may use:

- Public data from the ICIJ Offshore Leaks Database.
- Controlled lists of people, companies or institutions.
- Public complementary sources for manual validation.

## Matching stages

### 1. Name normalization

Names are standardized before comparison:

- lowercase conversion,
- accent removal,
- punctuation removal,
- whitespace normalization,
- removal of common corporate suffixes such as SA de CV, S.A., Ltd, Limited, Inc, Corp or Holdings.

### 2. Exact matching

The first stage compares normalized names exactly.

### 3. Fuzzy matching

The second stage uses approximate string matching to identify similar names.

Candidate matches are ranked by similarity score.

### 4. Confidence classification

| Level | Criteria |
|---|---|
| High | Almost identical name plus supporting evidence such as country, address, role or relationship |
| Medium | Similar name and partially compatible context |
| Low | Similar name without additional validation |
| Discarded | Likely homonym or insufficient evidence |

## Manual validation

Candidate matches must be manually reviewed before interpretation.

Validation may include:

- country,
- jurisdiction,
- address,
- role,
- associated company,
- date,
- source dataset,
- complementary public documentation.

## Ethical rule

A match is not evidence of wrongdoing. It is only a candidate relationship that requires validation.

# Methodology

## General approach

This project uses a reproducible data analysis workflow focused on entity resolution and network analysis.

The goal is to identify potential matches between a controlled list of people or companies of interest and public records from offshore leaks databases.

## Methodological workflow

1. Collect public data sources.
2. Clean and normalize names of people and companies.
3. Perform exact name matching.
4. Perform approximate matching using fuzzy matching.
5. Classify matches by confidence level.
6. Validate candidate matches using complementary variables.
7. Build networks between people, entities, intermediaries, addresses and jurisdictions.
8. Document findings, limitations and ethical considerations.

## Unit of analysis

The initial unit of analysis is the name of a person, company or organization.

The second level of analysis focuses on relationships between nodes, such as:

* people,
* offshore entities,
* intermediaries,
* addresses,
* jurisdictions,
* datasets.

## Match confidence levels

| Level     | Criteria                                                                                      |
| --------- | --------------------------------------------------------------------------------------------- |
| High      | Almost identical name plus supporting evidence such as country, address, role or relationship |
| Medium    | Similar name and partially compatible context                                                 |
| Low       | Similar name without additional validation                                                    |
| Discarded | Likely homonym or insufficient evidence                                                       |

## Limitations

This project identifies potential matches, not legal responsibility or wrongdoing.

Any candidate match must be manually validated with additional public sources before making substantive claims.

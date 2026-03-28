| Acronym    | Full Term                                   | Description / Notes                                          |
| ---------- | ------------------------------------------- | ------------------------------------------------------------ |
| **DP**     | Disease Prediction                          | Name of the task                                             |
| **MR**     | Medication Recommendation                   | Name of the task                                             |
| **E2E**    | End-to-End Success Rate                     | Metric: Proportion of correct LLM reasoning                  |
| **FCR**    | Format Compliance Rate                      | Metric: Proportion of LLM outputs following instruction format |
| **TTR**    | Thinking Truncation Rate                    | Metric: Proportion of LLM reasoning chains truncated         |
| **FCA**    | Format-Conditioned Accuracy                 | Metric: Accuracy of LLM responses under format constraints   |
| **DP-R-E** | Disease Prediction – Random – Easy          | Test set generated with random distractors; easy level       |
| **DP-R-M** | Disease Prediction – Random – Medium        | Test set generated with random distractors; medium level     |
| **DP-R-H** | Disease Prediction – Random – Hard          | Test set generated with random distractors; hard level       |
| **DP-S-E** | Disease Prediction – Similarity – Easy      | Test set generated with similarity-based distractors; easy level |
| **DP-S-M** | Disease Prediction – Similarity – Medium    | Test set generated with similarity-based distractors; medium level |
| **DP-S-H** | Disease Prediction – Similarity – Hard      | Test set generated with similarity-based distractors; hard level |
| **MR-R-E** | Medication Recommendation – Random – Easy   | Test set with random distractors; easy level                 |
| **MR-R-M** | Medication Recommendation – Random – Medium | Test set with random distractors; medium level               |
| **MR-R-H** | Medication Recommendation – Random – Hard   | Test set with random distractors; hard level                 |
| **O1R**    | Off-by-One Rate                             | Metric: Counts the number of test items where the prediction set matches the gold standard size but has exactly one missing and one extra label. |
| **OMR**    | Off-by-Many Rate                            | Metric: Prediction set matches gold standard size, but includes multiple incorrect labels; measures deviation |

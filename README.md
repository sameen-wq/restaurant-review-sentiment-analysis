
## Model Results

| Metric | Result |
| Total Reviews (After Cleaning) | 996 |
| Positive Reviews | 499 |
| Negative Reviews | 497 |
| Training Reviews | 796 |
| Testing Reviews | 200 |
| Selected Model | Multinomial Naive Bayes |
| Cross-Validation Macro-F1 | 0.797 |
| Baseline Accuracy | 50.0% |
| Test Accuracy | 82.0% |
| Test Macro-F1 Score | 0.820 |
| Correct Predictions | 164 |
| Incorrect Predictions | 36 |

## Classification Report

| Sentiment | Precision | Recall | F1-Score |
| Negative | 0.848 | 0.780 | 0.812 |
| Positive | 0.796 | 0.860 | 0.827 |
| Macro Average | 0.822 | 0.820 | 0.820 |
| Weighted Average | 0.822 | 0.820 | 0.820 |

## Observations

The Multinomial Naive Bayes model achieved 82% accuracy on the test dataset. Out of 200 restaurant reviews, the model correctly classified 164 reviews and incorrectly classified 36 reviews.

The results helped me understand how TF-IDF and machine learning can be used to classify text. I also noticed that some reviews can be difficult to classify when they contain mixed positive and negative opinions.

## Limitations

The dataset is relatively small, and the models may not perform as well on reviews from different sources. Future improvements could include testing with larger datasets and comparing more NLP techniques.

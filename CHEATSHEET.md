# 🩺 Cheatsheet: Classification Metrics & Clinical Risk

## 1. The Confusion Matrix Quadrants
| Quadrant | Name | Clinical Meaning |
| :--- | :--- | :--- |
| **Top-Left (32)** | **True Negative** | Healthy person correctly identified as Healthy. |
| **Top-Right (4)** | **False Positive** | Healthy person misidentified (Causes unnecessary stress/cost). |
| **Bottom-Left (4)** | **False Negative** | **SICK person missed!** (The highest risk in medicine). |
| **Bottom-Right (20)** | **True Positive** | Sick person correctly identified as At-Risk. |

## 2. Key Metrics & The "Why"
*   **Precision (0.83):** "When the model says you're sick, how often is it right?" (Protects against over-diagnosis).
*   **Recall (0.83):** "Of all the sick people, how many did we catch?" (Protects against missing a diagnosis).
*   **F1-Score (0.83):** The harmonic mean of Precision and Recall. Best for overall performance.

## 3. Interview Script
> "I developed a diagnostic classifier for heart disease that achieved 87% accuracy. More importantly, I analyzed the **Confusion Matrix** to quantify the rate of False Negatives. In a clinical context, I argued for prioritizing **Recall (Sensitivity)** to ensure that the maximum number of at-risk patients are captured for further screening, acknowledging that a trade-off in Precision is acceptable to save lives."
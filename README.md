# Airline Satisfaction Drivers: Customer Feedback EDA

A data-driven investigation into passenger survey responses to isolate the service factors most critical to airline customer retention.

## Business Problem
Airlines operate on thin margins where brand loyalty is paramount. Identifying exactly which touchpoints (e.g., legroom, wifi, boarding process) drive a passenger to rate an experience as "Satisfied" vs "Neutral/Dissatisfied" allows management to optimize capital expenditure and staff training.

## Dataset
* **Source:** [Kaggle Airline Passenger Satisfaction dataset]
* **Size:** [25,976 rows, 26 columns]

## Tools & Skills Demonstrated
* **Language:** Python
* **Libraries:** `pandas`, `matplotlib`, `seaborn`
* **Techniques:** Likert Scale Aggregation, Customer Segmentation (Business vs. Economy), Missing Data Imputation, Pivot Tables.

## Key Insights
* The dataset is clean: no missing values and no duplicate rows across 25,976 records.
* Loyalty and satisfaction are strongly linked: loyal customers are satisfied 48.1% of the time vs. only 25.2% for disloyal customers.
* Economy class has the highest average total delay (≈30.1 min) and Business the lowest (≈28.0 min), though the gap is modest and the median delay is just 2–3 minutes in every class — the mean is driven by a right-skewed tail of poorly delayed flights.
* Satisfaction declines as total delay increases (from ≈42.7% satisfied at 0–30 minutes of delay to ≈35.4% satisfied at 120–150 minutes), but this view only covers about 49% of flights because it excludes the ~46% of flights with zero delay and the ~5% with more than 150 minutes of delay.

## Contact
* LinkedIn: https://www.linkedin.com/in/khoa-nguyen-38076b365/
* Email: nd.duykhoa@gmail.com

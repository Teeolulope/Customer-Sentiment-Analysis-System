# Customer-Sentiment-Analysis-System

## Introduction

This project is a Python case study on customer sentiment analysis for customer experience decision support. Modern customer support and CRM platforms rely heavily on software to analyze feedback data and support better decisions about who needs follow-up and who deserves recognition. This project evaluates feedback from two customers (Grace Okafor and Ibrahim Bello) using predefined rules to determine satisfaction levels and whether immediate follow-up or special appreciation is required.

## Problem Statement

Customer feedback significantly influences retention and brand loyalty. Support teams need timely insights into satisfaction ratings and complaint history to make informed decisions about how to respond to each customer. This project demonstrates how Python can be used to analyze customer feedback data and support simple customer relationship decision-making.

## Project Goal

The objectives of this project are to:

- Calculate an average satisfaction rating from multiple feedback dimensions.
- Evaluate whether a customer is highly satisfied or has a high complaint level.
- Determine whether immediate follow-up is required.
- Identify brand advocates and customers who deserve special appreciation.

## Data Source
A sample customer feedback dataset containing ratings and complaint history for two customers:

<img width="636" height="534" alt="Screenshot 2026-07-23 231738" src="https://github.com/user-attachments/assets/6257b451-b750-42db-ac0b-7d75f761ac4d" />
<img width="486" height="523" alt="Screenshot 2026-07-23 231753" src="https://github.com/user-attachments/assets/52bc13e2-a3a3-4b61-9602-8f849e222e98" />


## Tools Used

- Python
- Jupyter Notebook
- Variables
- Data types
- Arithmetic operators
- Comparison operators
- Boolean expressions
- Basic conditional logic for result interpretation

## Methods

- Data entry and inspection for each customer.
- Average rating calculation across satisfaction, delivery, product quality, and support scores.
- Complaint level analysis using predefined thresholds.
- Determination of follow-up and appreciation requirements based on the results.

## Findings

- Grace Okafor recorded a high complaint level, resulting in a requirement for immediate follow-up. Her case shows that a single unresolved complaint can outweigh an otherwise decent average rating — support teams should weigh the recency and frequency of complaints, not just the overall score.
- Ibrahim Bello recorded a high average rating with low complaints, qualifying him as a brand advocate. This shows that consistently strong ratings across all feedback dimensions, not just one, are what earn a customer that status.
- Recommendations were generated based on the outcome of the analysis for each customer.

## Recommendations

- Monitor satisfaction ratings and complaint counts regularly, not just at a single point in time.
- Trigger immediate follow-up whenever complaint levels are high and satisfaction is not exceptional, since ratings alone can mask an unresolved issue.
- Recognize and appreciate customers who qualify as brand advocates, since consistent positive feedback is a strong signal of loyalty.

## Limitations

- This analysis is based on a small sample of two customers; a real-world system would need a much larger dataset to draw reliable conclusions.
- The satisfaction and complaint thresholds used (e.g. average rating above 4.5, complaints ≥ 2) are fixed and were chosen for illustration. A production system would likely need dynamic, data-driven thresholds tailored to the business.

## Sample Output
<img width="1256" height="443" alt="Screenshot 2026-07-23 234340" src="https://github.com/user-attachments/assets/e8ad9d98-b997-43ec-9a03-83c0be60dbea" />
<img width="1252" height="389" alt="Screenshot 2026-07-23 234433" src="https://github.com/user-attachments/assets/762abeb5-f443-4818-8b31-ecfa5592da04" />
<img width="1247" height="420" alt="Screenshot 2026-07-23 234513" src="https://github.com/user-attachments/assets/bd1edc2c-7565-4ae0-8761-d12d27706bd9" />
<img width="1247" height="420" alt="Screenshot 2026-07-23 234513" src="https://github.com/user-attachments/assets/9dc45434-80bb-4560-865a-91f497ed36c3" />
<img width="1250" height="370" alt="Screenshot 2026-07-23 234541" src="https://github.com/user-attachments/assets/b37af2bd-4eaa-4733-bb97-340196f8555b" />
<img width="1241" height="374" alt="Screenshot 2026-07-23 234617" src="https://github.com/user-attachments/assets/d24fa56b-4cfd-4af9-b3b4-9983526e9450" />
<img width="1241" height="456" alt="Screenshot 2026-07-23 234658" src="https://github.com/user-attachments/assets/1ebe01d2-9097-4551-9ec0-f02e6c6a5487" />
<img width="1243" height="366" alt="Screenshot 2026-07-23 234720" src="https://github.com/user-attachments/assets/bb361d74-a391-40cc-9838-232970fddf22" />


## How to Run

1. Clone this repository:
   ```
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open `Gift 1.ipynb` in Jupyter Notebook or JupyterLab.
3. Run all cells from top to bottom to reproduce the analysis and printed reports.

## Repository Structure

- **README.md** – Project overview and case study summary.
- **Gift 1.ipynb** – Python notebook containing the analysis.
- **images/** – Screenshots referenced in this README (add after uploading your notebook output screenshot).

## Author

**Tolulope Tolulola**

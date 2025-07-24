# Google Pay Retention Analytics Case Study

This project simulates a real-world Product Analyst task: identifying user retention problems in a fintech app (Google Pay) and proposing data-driven solutions.

## Problem Statement

Google Pay is experiencing **high user churn** — more than half of new users do not return after their first transaction. This project explores simulated user behavior data to understand:
- Who is churning?
- What patterns are tied to retention?
- How product teams can improve user engagement and repeat activity.

## Dataset

A simulated dataset of **1,000 users** was generated using Python. Key features include:
- `user_id`, `signup_date`, `first_txn_date`
- `num_txns`, `total_txn_value`
- `device_os` (Android/iOS)
- `used_offer` (Yes/No)
- `retained_30d` (Yes/No)

> The dataset mimics real transactional data for exploratory product analysis.

## Key Insights

- **50.6% of users are one-time transactors**
- **Offer usage improves retention**: 52.3% of users who used a promo offer returned, vs. only 44.8% of those who didn’t
- **iOS users retained slightly better** (50.4%) than Android users (49.0%)

## Recommendations

- Trigger **targeted cashback offers** for second transactions
- Introduce **“cashback streaks”** to build repeat behavior habits
- Segment push notifications and onboarding by device OS
- Monitor offer usage to detect one-time incentive seekers

## Tools Used

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Jupyter Notebook
- PowerPoint (for summary slides)

## Files Included

| File | Description |
|------|-------------|
| `googlepay_user_simulated.csv` | Simulated user behavior data |
| `01_generate_data.ipynb` | Data simulation script |
| `02_eda.ipynb` | Exploratory data analysis |
| `GooglePay_Retention_CaseStudy.pdf` | Final presentation slides |

##  Author

**Khushboo Masih**  
MSc Data Science | BBA  
khushboomasih193@gmail.com 
https://www.linkedin.com/in/khushboo-masih/  

## License

This project is provided for educational and portfolio purposes only. No affiliation with Google or Google Pay.

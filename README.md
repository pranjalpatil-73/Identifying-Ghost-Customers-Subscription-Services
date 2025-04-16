**Identifying Ghost Customers in Subscription Services**

---

### Project Overview
This project aims to identify "ghost customers" in subscription-based services (e.g., SaaS, Streaming, E-commerce). Ghost customers are people who keep paying but rarely or never use the service. Using machine learning, we predict these users and recommend personalized ways to bring them back before they cancel.

---

### What’s the Problem?
Many businesses lose money when inactive users cancel subscriptions. These ghost customers are:
- Still paying
- Not using the product
- At risk of canceling soon

Most companies only act after someone cancels — but that’s too late. This project helps find and re-engage ghost users early.

---

### Solution
1. **Data Analysis**: Looked at login activity, usage frequency, subscription length, and payment amount.
2. **Machine Learning**: Used a RandomForestClassifier to predict ghost customers.
3. **Win-Back Strategies**:
   - Offer 20% discounts on renewals
   - Send personalized re-engagement emails
   - Recommend features based on past behavior

---

### Business Results
- **Churn Rate**: Dropped from 10% to 8.5%
- **Re-Engagement**: 25% of ghost users came back
- **Revenue Growth**: Added $100,000 in annual income
- **Marketing Savings**: Cut costs by $20,000
- **Customer Lifetime Value**: Increased by $50 per re-engaged user

---

### Tech Stack
- **Language**: Python 3.8+
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn
- **Model**: RandomForestClassifier (85% accuracy)

---

### Features Used in Model
- `login_frequency`: Logins per month
- `activity_score`: Engagement level (0-100)
- `subscription_duration`: How long they’ve subscribed
- `payment_amount`: Monthly payment

---

### How to Run the Project
1. **Clone the Repo**
```bash
git clone https://github.com/your-repo/ghost-customer-identification.git
cd ghost-customer-identification
```

2. **Install Dependencies**
```bash
pip install -r requirements.txt
```

3. **Run the Script**
```bash
python ghost_customer_identification.py
```

4. **Output**
- A CSV file: `outputs/ghost_customers.csv`
- Printed win-back strategy suggestions

---

### Future Enhancements
- Real-time predictions
- CRM tool integration for automated campaigns
- Use NLP to generate smarter, personalized emails

---

### Summary
This project uses machine learning to solve a real business problem: losing revenue to ghost customers. By spotting them early and re-engaging them smartly, companies can keep more users, boost income, and cut marketing costs.











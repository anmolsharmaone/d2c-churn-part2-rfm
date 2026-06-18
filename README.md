# d2c-churn-part2-rfm
# Customer Segmentation and Retention Strategy

## Project Overview

This project is based on a RFM (Recency, Frequency, Monetary) framework for customer segmentation, with customer engagement and customer service components. The goal is to determine the segments of customers at varied risk of churn and need for retention.

---

## Dataset

The analysis is based on customer level behavioral data such as:

* Purchase history
* Revenue contribution
* Website engagement
* Campaign interactions
* Customer support activity
* Product return behavior
* Churn outcome labels

---

## Methodology

### RFM Scoring

The following criteria were used for assigning scores to customers:

* Recency
* Frequency
* Monetary Value

Each score was added together to create a composite RFM score, which ranged from 3 to 15.

### Additional Behavioral Signals

The following variables were added:

* ticket_count_90d
* sessions_30d
* campaign_clicks_30d
* return_rate_180d
* avg_discount_pct_180d

---

## Customer Segments

Six segments of customers were identified:

1. Champion
2. Loyal Customer
3. High Value Unhappy
4. Discount Sensitive
5. Dormant
6. At Risk

---

## Key Findings

### Segment Distribution

* Loyal Customer: 708
* At Risk: 482
* Dormant: 443
* Discount Sensitive: 344
* Champion: 330
* High Value Unhappy: 93

### Churn Analysis

 Segment             Average Churn Rate 
  
 Champion            7%                 
 High Value Unhappy  23%                
 Loyal Customer      30%                
 Dormant             49%                
 Discount Sensitive  64%                
 At Risk             90%                

---

## Business Recommendations

### Highest Priority

* At Risk
* High Value Unhappy

### Medium Priority

* Loyal Customer
* Discount Sensitive

### Lower Priority

* Dormant
* Champion

Retention resources should be directed towards revenue impact and churn probability.

---

## Deliverables

* Customer segmentation model
* Segment distribution analysis
* Churn analysis by segment
* Retention strategy recommendations
* Manual review cases

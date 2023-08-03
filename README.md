# Optimal-promotional-channel-prediction
**promotional channel that maximizes drug sales**
- Developed a multivariate multiple time series model to predict the optimal promotional channel for a drug, resulting in a significant F1 score improvement from a baseline of 0.2 to an impressive 0.53 using a multiclass classification approach.
- Successfully addressed the challenge of predicting individual features in the test data, which lacked multivariate
 information .
- Incorporated real-world considerations, such as maximum reachability and cost of promotion, into the modeling
 process, ensuring practicality and relevance.
- Overcame data limitations, with each independent time series containing only 57 weekly data points, showcasing
 efficiency and effectiveness in building a reliable predictive model

**Problem Statement**
- Based on the datasets shared, project background and promotional constraints, the ask is to identify the best promotional
channel for every HCP for the upcoming week. The best channel should be identified among three channels – sales rep
calls, emails, and sample drops. The best channel should meet the promotional constraints shared and should maximize the
brand TRx for the upcoming week for that HCP. The frequency of promotion of the channel should not be considered while
identifying the best promotional channel.

- Promotional Constraints:

1. Sales rep calls in last 12 months (including the promotion week to be optimized for) should not be more than:
     - 48 calls for High Segment HCPs
     - 24 calls for Medium Segment HCPs
     - 12 calls for Low Segment HCPs
2. Only 25% of the HCPs can be reached out through sample drops in any week
3. Overall predicted Brand Rx (across all HCPs) should not deviate more than 10% than the immediate previous week

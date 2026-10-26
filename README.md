# Ad Optimization Agent

This project analyzes advertising data from Search, Social, and Display channels to recommend daily advertising budget allocations.

## How to Run
1. Open Ad_Optimization_Agent.ipynb in Google Colab.
2. Run the code cell.
3. Upload the advertising Excel or CSV dataset when prompted.
4. Review the channel metrics and next-day budget recommendations.
5. Download the generated ZIP file containing the results.

## Budget Rules
- Total daily budget: $300.
- Minimum allocation per channel: 10%.
- Maximum daily budget adjustment per channel: 20%.
- Use the most recent 7 days of data for recommendations.
- Require at least 3 days of data for each channel before adjusting budgets.

## Outputs
- advertising_data.csv
- channel_metrics.csv
- decision_log.csv
- next_day_budget.csv

## Limitations
The data is simulated, and recommendations do not guarantee improved real-world advertising performance.

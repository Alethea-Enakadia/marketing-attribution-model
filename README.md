## Python | Marketing Analytics | Attribution Modeling

## Multi-Touch Marketing Attribution Model
A marketing engineering system that builds a multi-touch attribution system in Python to analyze customer journeys and assign conversion credit across marketing channels.

The project transforms raw interaction data into channel-level performance insights to support data-driven budget allocation, campaign optimization, and marketing decision-making.

## Architecture
Dataset → Data Processing → Attribution Models → Insights

## Tags
marketing-analytics  
attribution-model  
data-science  
python  
marketing-engineering  
customer-journey  
performance-marketing  

## Problem
Marketing teams often rely on last-click attribution, which ignores earlier touchpoints in the customer journey and leads to poor budget allocation decisions.

## Project Pipeline
1. Data ingestion  
2. Journey construction  
3. Attribution modeling  
4. Performance evaluation  

## Project Structure
- data/ → dataset
- notebook/ → attribution model implementation
- images/ → visualizations
- README.md → project documentation

## Solution
Built a multi-touch attribution system in Python that models customer journeys and assigns conversion credit using:
- First Click Attribution  
- Last Click Attribution  
- Linear Attribution  
- Time Decay Attribution  

## Dataset
Customer journey dataset containing user interactions across marketing channels.

### Dataset Structure
- user_id — unique customer identifier  
- timestamp — interaction time  
- channel — marketing channel  
- campaign — campaign name  
- conversion — conversion outcome (Yes/No)
  
### Sample Data

| user_id | timestamp | channel | campaign | conversion |
|---|---|---|---|---|
| 1 | 2024-01-01 | Google | Search_A | No |
| 1 | 2024-01-03 | Email | Retargeting | Yes |

## Tools
Python, Pandas, NumPy, Matplotlib

## Results
The attribution models generated significantly different channel performance rankings, demonstrating how attribution methodology directly impacts marketing insights and budget decisions.

### Channel Performance Example
- Google: 32% credit (linear model)
- Email: 25% credit
- Meta: 43% credit
  
## Visualization
Bar charts compare channel performance across attribution models.

## Key Insights
- Different models assign different credit weights across channels  
- Multi-touch attribution reveals hidden channel contributions  
- Last-click attribution can overvalue final touchpoints  

## Business Impact
Provides a data-driven framework for:
- Marketing performance measurement  
- Budget allocation optimization  
- Campaign effectiveness analysis  
- Customer journey understanding  

## How to Run
1. Install dependencies:
```bash
pip install pandas numpy matplotlib
```

2. Open the notebook and run all cells.

## Future Improvements
- Markov attribution  
- Budget optimization engine  
- Machine learning conversion prediction  
- Interactive dashboard

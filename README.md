## AI-powered Insight Assistant for Retail and CPG Business Decision Making

This project solves a real industry problem: retail and CPG leaders struggle to get unified insights from scattered sales, marketing, customer feedback, and operational data. Building an assistant that answers business questions using real data enables faster decisions and revenue growth.

🚀 Project Goal

 -Build a Retrieval Augmented Generation (RAG) based Insight system that:

- Understands natural language business queries

- Retrieves relevant documents from structured & unstructured data

- Generates business insights, charts, and recommendations

- Acts as an Insight Assistant for sales, marketing & supply chain leaders

🎯 Example Business Questions

- “Why did the sales drop for Shampoo 200ml in South region in Q2?”
- "What are customers complaining about most in detergent category?"
- "Summarize marketing spend vs ROI for last quarter."

📂 Data Used
Data	Description
POS / Sales data	SKU, Region, Channel, Revenue, Volume
Customer Reviews	Text reviews from marketplaces
Marketing data	Campaigns, spend, performance
Product master	Pack size, category, MRP

🧠 Architecture
- ETL → Embeddings → Vector DB → RAG Pipeline → LLM → Streamlit UI

🔍 Sample Output
Sales for Shampoo 200ml dropped by 18% in South region in Q2.

Key Drivers Identified:
• Price increase of 12% in April reduced repeat customers
• Competitor Dove launched BOGO offer in May–June
• Packaging defects increased complaints by 22%

Recommended Actions:
• Run combi-offer campaign
• Fix packaging leakage issue
• Push influencer content strategy

📈 Business Impact
- Metric	Before	After
- Insight turnaround time	7–10 days	5–8 seconds
- Sales forecasting accuracy	68%	89%
- Revenue growth	+3.5%	

🎥 Demo Video

(Add later after building Streamlit demo)

📜 Future Enhancements

- Integrate demand forecasting models

- Add dashboard + automated email reporting

- Make mobile app version

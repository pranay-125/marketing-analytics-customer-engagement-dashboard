<h1>📊 Marketing Analytics & Customer Engagement Analysis</h1>

<hr>

<h2>📌 Project Overview</h2>

<p>
This project analyzes <b>digital marketing performance and customer experience insights</b> for an e-commerce business (ShopEasy).
</p>

<p>
The objective of the analysis is to understand:
</p>

<ul>
<li>Why <b>customer engagement is high</b></li>
<li>But <b>conversion rates remain low</b></li>
<li>And how marketing campaigns can be optimized using <b>data-driven insights</b></li>
</ul>

<p>
The project integrates:
</p>

<ul>
<li>Marketing analytics</li>
<li>Customer journey analysis</li>
<li>Customer sentiment analysis</li>
</ul>

<p>
All insights are presented through an <b>interactive Power BI dashboard</b>.
</p>

<hr>

<h2>🎯 Business Problem</h2>

<p>The company observed the following issues:</p>

<ul>
<li>Marketing campaigns generate <b>high impressions</b></li>
<li>Customer engagement exists but <b>conversion remains low</b></li>
<li>Large volumes of <b>customer feedback are not analyzed</b></li>
</ul>

<p><b>Core Business Question</b></p>

<blockquote>
Why are customers interacting with campaigns but not completing purchases?
</blockquote>

<hr>

<h2>🧠 Project Objectives</h2>

<p>The project focuses on solving the following business problems:</p>

<ul>
<li>Analyze <b>digital marketing campaign performance</b></li>
<li>Measure <b>customer engagement behavior</b></li>
<li>Identify <b>conversion funnel drop-offs</b></li>
<li>Analyze <b>customer feedback sentiment</b></li>
<li>Build an <b>interactive Power BI dashboard for stakeholders</b></li>
</ul>

<hr>

<h2>🗂 Dataset Structure</h2>

<h3>Fact Tables</h3>

<table border="1" cellpadding="6">
<tr>
<th>Table Name</th>
<th>Description</th>
</tr>

<tr>
<td>fact_engagement_data</td>
<td>Stores user engagement events such as views, clicks, likes, and comments</td>
</tr>

<tr>
<td>fact_customer_journey</td>
<td>Tracks customer movement through the marketing funnel</td>
</tr>

<tr>
<td>fact_customer_reviews</td>
<td>Contains customer ratings and review text</td>
</tr>

</table>

<br>

<h3>Dimension Tables</h3>

<table border="1" cellpadding="6">
<tr>
<th>Table Name</th>
<th>Description</th>
</tr>

<tr>
<td>dim_products</td>
<td>Product details including category and brand</td>
</tr>

<tr>
<td>dim_calendar</td>
<td>Custom calendar table for time-based analysis</td>
</tr>

</table>

<hr>

<h2>🏗 Data Model</h2>

<p>A <b>Star Schema data model</b> was implemented in Power BI.</p>

<h3>Fact Tables</h3>

<ul>
<li>Engagement Data</li>
<li>Customer Journey</li>
<li>Customer Reviews</li>
</ul>

<h3>Dimension Tables</h3>

<ul>
<li>Product Dimension</li>
<li>Calendar Dimension</li>
</ul>

<h3>Key Relationships</h3>

<ul>
<li><b>customer_id</b> → links engagement, journey, and reviews</li>
<li><b>product_id</b> → connects fact tables with product dimension</li>
<li><b>date</b> → connects fact tables with calendar dimension</li>
</ul>

<p>
This model enables <b>multi-dimensional analysis across campaigns, audiences, and products</b>.
</p>

<hr>

<h2>📈 Key Performance Indicators (KPIs)</h2>

<table border="1" cellpadding="6">

<tr>
<th>KPI</th>
<th>Description</th>
<th>Formula</th>
</tr>

<tr>
<td>Impressions</td>
<td>Number of times ads were shown</td>
<td>Total impressions</td>
</tr>

<tr>
<td>Clicks</td>
<td>Number of user clicks</td>
<td>Total clicks</td>
</tr>

<tr>
<td>Engagements</td>
<td>User interactions with ads</td>
<td>Clicks + Shares + Comments</td>
</tr>

<tr>
<td>Purchases</td>
<td>Completed conversions</td>
<td>Total purchases</td>
</tr>

<tr>
<td>CTR</td>
<td>Click Through Rate</td>
<td>Clicks ÷ Impressions</td>
</tr>

<tr>
<td>Engagement Rate</td>
<td>Interaction efficiency</td>
<td>Engagements ÷ Impressions</td>
</tr>

<tr>
<td>Conversion Rate</td>
<td>Purchase efficiency</td>
<td>Purchases ÷ Clicks</td>
</tr>

<tr>
<td>Purchase Rate</td>
<td>Purchase probability</td>
<td>Purchases ÷ Impressions</td>
</tr>

<tr>
<td>Total Budget</td>
<td>Total campaign spend</td>
<td>Campaign budget</td>
</tr>

<tr>
<td>Avg Budget per Campaign</td>
<td>Average budget allocation</td>
<td>Total Budget ÷ Campaigns</td>
</tr>

</table>

<hr>

<h2>📊 Dashboard Visualizations</h2>

<p>The Power BI dashboard includes multiple analytical views.</p>

<h3>Audience Insights</h3>

<ul>
<li>Gender Distribution (Donut Chart)</li>
<li>Age Group Engagement (Bar Chart)</li>
</ul>

<h3>Geographic Insights</h3>

<ul>
<li>Country Performance Map</li>
</ul>

<h3>Time-Based Analysis</h3>

<ul>
<li>Calendar Heat Map (Monthly Trends)</li>
<li>Weekly Performance Trend</li>
<li>Hourly Engagement Pattern</li>
</ul>

<h3>Campaign Performance</h3>

<ul>
<li>Creative Performance</li>
<li>Ad Type Performance Matrix</li>
</ul>

<p>
 <img width="1920" height="1080" alt="Screenshot 2026-04-02 150510" src="https://github.com/user-attachments/assets/63936c19-fa4b-442b-a961-b1549443f5f0" />
 </p>

<p>
  <img width="1920" height="1080" alt="Screenshot 2026-04-02 150520" src="https://github.com/user-attachments/assets/7346d205-e410-4c76-8aa1-8d9ee530b099" />
</p>

<p>
  <img width="1920" height="1080" alt="Screenshot 2026-04-02 150530" src="https://github.com/user-attachments/assets/d6716b13-2118-48aa-a196-09dc8450bcd1" />
</p>

<p>
  <img width="1920" height="1080" alt="Screenshot 2026-04-02 150543" src="https://github.com/user-attachments/assets/ec05d7d2-0bbc-4090-85e2-438b2df3b3ea" />
</p>

<hr>

<h2>📉 Funnel Performance</h2>

<table border="1" cellpadding="6">

<tr>
<th>Metric</th>
<th>Value</th>
</tr>

<tr>
<td>Impressions</td>
<td>216K</td>
</tr>

<tr>
<td>Clicks</td>
<td>25.4K</td>
</tr>

<tr>
<td>Purchases</td>
<td>1.3K</td>
</tr>

</table>

<br>

<p><b>Key Observation</b></p>

<p>
Although campaigns generate <b>strong reach and engagement</b>, the <b>conversion efficiency remains low</b>.
</p>

<p>
This indicates a <b>funnel leakage between engagement and purchase stages</b>.
</p>

<hr>

<h2>🔍 Audience Insights</h2>

<h3>Gender Insights</h3>

<p>Female users generate the <b>highest engagement levels</b>.</p>

<h3>Age Group Insights</h3>

<p>The <b>18–30 age group dominates campaign interaction</b>.</p>

<p>
This indicates marketing campaigns resonate most strongly with <b>younger female audiences</b>.
</p>

<hr>

<h2>🐍 Python Sentiment Analysis</h2>

<p>Python was used to analyze <b>customer review text</b>.</p>

<p><b>Steps performed:</b></p>

<ol>
<li>Load review dataset</li>
<li>Clean text data</li>
<li>Apply sentiment analysis</li>
<li>Classify reviews into Positive, Neutral, and Negative</li>
</ol>

<p>
This enriched the dataset with <b>customer experience insights</b>.
</p>

<hr>

<h2>💡 Key Insights</h2>

<ul>

<li>Campaigns generate <b>strong awareness</b> but <b>low conversion efficiency</b></li>

<li>Major drop-off occurs <b>between engagement and purchase</b></li>

<li>Customer sentiment is <b>mostly positive</b>, but ratings show improvement areas</li>

<li>Marketing performance shows <b>seasonal patterns</b></li>

</ul>

<hr>

<h2>🚀 Business Recommendations</h2>

<ul>

<li>Improve <b>landing page and checkout experience</b></li>

<li>Implement <b>retargeting campaigns for engaged users</b></li>

<li>Use <b>customer feedback insights to improve CX</b></li>

<li>Align campaigns with <b>high-performing seasonal periods</b></li>

</ul>

<hr>

<h2>🛠 Tools Used</h2>

<table border="1" cellpadding="6">

<tr>
<th>Tool</th>
<th>Purpose</th>
</tr>

<tr>
<td>SQL</td>
<td>Data cleaning and transformation</td>
</tr>

<tr>
<td>Python</td>
<td>Sentiment analysis</td>
</tr>

<tr>
<td>Power BI</td>
<td>Data modeling and dashboard creation</td>
</tr>

<tr>
<td>Excel</td>
<td>Initial data exploration</td>
</tr>

</table>

<hr>

<h2>👤 Author</h2>

<p>
<b>Name:</b> Pranay Shrivastava <br>
<b>Degree:</b> B.Tech – Artificial Intelligence & Data Science <br>
<b>Specialization:</b> Data Analytics | Business Intelligence <br>
<b>Email:</b> shrivastavapranay35@gmail.com <br>
<b>LinkedIn:</b> <a href="https://www.linkedin.com/in/pranayshrivastavaofficial/">linkedin.com/in/pranay-shrivastava</a> <br>
<b>GitHub:</b> <a href="https://github.com/pranay-125">github.com/pranay-125</a>
</p>

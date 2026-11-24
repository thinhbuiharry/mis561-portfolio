# mis561-portfolio
Portfolio of projects from my Data Visualization course. This will include the completion of assignments in Excel, Tableau, PowerBi through DataCamp, Adobe Express, and various AI tools

Initial E-Commerce Profitability Analysis, Develop a basic profitability set of dashboards and explain my design, [a link to my tableau public workbook](https://public.tableau.com/views/AdvancinginExcelandTableauPt_1_17894448917840/ExploratoryDash?:language=fr-FR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link), If I were doing this again, I'd planned earlier and spent more time cleaning it up.


Account Profitability and Service Tiers, Develop a basic net contribution set of dashboards and explain my design, [a link to my tableau public workbook](https://public.tableau.com/views/AdvancinginExcelandTableauPt_2_17900549073190/AccountPortfolioDashboard?:language=fr-FR&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link), If I were doing this again, I'd planned earlier and spent more time cleaning it up.

Power BI Business Intelligence Training, Date Complete: 9/27/2026, https://public.tableau.com/views/IntroductiontoPowerBI/PowerBIStroy?:language=fr-FR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

One thing I feel Power BI does automatically is detect relationships between tables when I add new data. In Flex 3 and Flex 4, I used XLOOKUP in Excel to look up data across different tables and bring the values into my dataset before visualizing them. In Power BI, it can automatically detect the relationship between tables based on common fields, which allows me to use the related data in my visualizations without manually creating an XLOOKUP for every value. Therefore, next time I need to work with data across different tables, I would prefer Power BI because it reduces manual data processing and makes the analysis more efficient.


Introduction to DAX, Date Complete: 10/5/2026, https://public.tableau.com/views/IntroductiontoPowerBI/PowerBIStroy?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

I would make Margin % = Profit ÷ Sales as a measure in Power BI. The main purpose of making it a measure is flexibility for the users, because one measure can dynamically calculate the margin based on what Anita or Marcus is looking at or filtering. If the margin calculation lives in the Power BI model instead of my workbook, they do not have to go through different worksheets or ask me to find and recalculate the number; they can select the measure and explore the margin by product, account, or other filters. The benefit of the business is that Anita and Marcus can get the number they need and explore the data on their own instead of depending on me to find or calculate it for them. 


Advancing in Power BI Data Visualization Training, Date Complete: 10/7/2026, https://public.tableau.com/views/IntroductiontoPowerBI/PowerBIStroy?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Hi Sarah, 

I’m ready for business intelligence work at Southwest because I’ve built views that help Anita and Marcus decide, and I know where Power BI would improve them. In Flex 4, I built a bar chart of net contribution by discount band with a reference line at the $500 target. In Power BI, I would replace the line with conditional formatting rules: green for bands above $500, light green near it, and red well below. Marcus could then see which bands meet the target without comparing each bar to the line. In Flex 3, my scatter plot of product losses left a lot of empty space. It showed profit margin, revenue, and profit, but Anita only needs to know where to act first. In Power BI, I would use a bar chart of profit by subcategory, sorted by profit, with negative values colored red. Tables, the biggest loss, would stand out immediately. 

Power BI has clear advantages, but Excel and Tableau still matter in business intelligence. Excel is best for quick calculations and PivotTables. Tableau is better for creative, customized dashboards, since it isn’t limited to rigid chart templates. Power BI works best when connecting Excel workbooks and sharing reports quickly through Teams, and its DAX language adds strong analytical power. My main operational gap is never having published or maintained live reports on the Power BI Service for active business users. To close this, I am building end-to-end published reports using real-world public datasets to master workspace administration. 

AI acknowledgment: I used Claude (Anthropic) to help edit and tighten the wording of this entry; the examples, analysis, and conclusions are my own.

Card Portfolio Review – Contactless Readiness, Develop a basic set of dashboards for contactless and non-contactless cards, and explain the design, [Card Portfolio Review - Contactless Readiness](https://public.tableau.com/views/CardPortfolioReview/ExploratoryDash?:language=fr-FR&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link), If I were doing this again, I'd planned earlier and spent more time cleaning it up and dive deeper on the analysis.

Card Growth Analysis – Wildcat Rewards Offer, Develop a basic set of dashboards to identify credit card customers who qualify for the offer under the provided Credit Risk guardrails, and explain the design, [Card Growth Analysis – Wildcat Rewards Offer](https://public.tableau.com/views/CardGrowthAnalysis-WildcatRewardsOffer_17929176361990/ExploratoryDashboard?:language=fr-FR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link), If I were to do this again, I would plan earlier and spend more time exploring different data visualizations to evaluate which one communicates the findings most effectively.

**Nov 2, 2026 · Data Storytelling with Adobe Express**

Work sample for Jordan Ellis, VP of Card Growth at Bear Down Bank: PRIORITIZE TEXAS CUSTOMERS FOR THE WILDCAT REWARDS PILOT.

[Work sample (PDF)](https://github.com/thinhbuiharry/mis561-portfolio/blob/main/adobe/bui-data-storytelling.pdf) · [Adobe Express](https://new.express.adobe.com/id/urn:aaid:sc:VA6C2:64bea197-24cc-43c3-9e93-6615a1c18f05?accept=true&invite=true&promoid=Z2G1FQKR&mv=other)

Design Choice: I used a horizontal bar chart to display the qualification rates by state among the 10 states with the largest customer counts. This visualization highlights two key insights: which state has the largest number of customers qualified for the Wildcat Rewards pilot and which state has the highest qualification rate. I removed the penetration by generation breakdown because presenting the data only as percentages could make it difficult for the audience to understand how many customers each percentage represents. 

Training completed: Nov 1, 2026


**Nov 16, 2026 · Product Pitch with Generative AI in Adobe Express**

Pitch to Jordan Ellis, VP of Card Growth, at Bear Down Bank: approve a two-week first phase to identify the which customer segment receives the Wildcat Rewards Card pilot mailing.

[Pitch deck (PDF)]( https://github.com/thinhbuiharry/mis561-portfolio/blob/main/adobe/bui-product-pitch.pdf) · [Adobe Express](https://new.express.adobe.com/id/urn:aaid:sc:VA6C2:04de46b1-0945-4653-97c8-8060c4e1865b?accept=true&invite=true&promoid=Z2G1FQKR&mv=other)

Toughest objection: "We only have enough budget for one pilot. How can we be confident that we are targeting the right customers, and what happens if we get it wrong?" 
Slide 5 answers it: we will rank eligible customer concentration across two dimensions: state and generation. By identifying which segments have the highest concentration of eligible customers, Bear Down Bank can prioritize the strongest potential target segment and focus its limited pilot budget there.

AI use: I use it to check grammar and brainstorm what the slides should look like. Nov 16, 2026.

Training completed: Nov 16, 2026


**Nov 23, 2026 · Brand Standard Application in Tableau**

Rebranded a public IMDb movie dashboard, then built a brief for Dana Ruiz, VP of
Advertising Sales: which two or three genres should lead next year’s ad pitch?

[Tableau workbook](https://public.tableau.com:9443/views/DataPlusMovies2000-2023_17954112804710/DataMoviesIMDBDashboard?:language=fr-FR&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

One thing I’d change: I would pick my theme before formatting anything. Switching from
light to dark halfway through meant redoing every text color.

AI use: Claude checked my writing grammar and brainstorm ideas how to visualize the explanatory dashboards,
11 23, 2026.


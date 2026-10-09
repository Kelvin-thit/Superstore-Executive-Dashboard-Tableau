# Superstore-Executive-Dashboard-Tableau
Superstore Executive Performance Dashboard (Tableau)

An interactive executive dashboard built in Tableau Desktop for a fictional VP of Retail Operations, using Tableau's Superstore sample dataset. Built for Data-Driven Decision-Making (MASY1-GC 1215) at NYU School of Professional Studies, Fall 2026.

What the dashboard answers
Tier	Question	Visuals
1. KPI cards	Are we on track?	Total Sales vs Target ($2.33M, 93% of $2.5M), Net Profit Margin (12.6% vs 15%), Overall Return Rate (5.8% vs 5% limit)
2. Diagnostics	Why is performance moving?	Profit margin map by state and province, margin and return rate by region, profit vs average discount by sub-category
3. Action list	What should the front line fix?	Top 10 loss-making products with sales, discount, order lines and units

Clicking a state on the map filters the diagnostic charts and the action list to that market.

Key findings
Returns are a West problem. West returns 11.6% of orders, against about 3% in the other three regions.
Deep discounts drive losses. Tables lose $17,753 at a 26% average discount, and seven of the ten worst products sell at 35% off or more.
Central has the weakest margin. Central earns 7.9%, about half of West's 15.0%, and Texas runs at -15.1%.

The three benchmarks ($2.5M sales, 15% margin, 5% return limit) are assumed targets, since the dataset contains none.

Tableau techniques used
Relationship between the Orders and Returns tables on Order ID
Calculated fields: profit margin, return rate, target attainment and status flags
Parameters for the sales, margin and return-rate benchmarks
Filled map, dual-measure bar charts with reference lines, Bottom-N filter
Dashboard filter action with a context filter so the Top 10 list stays at ten rows
Custom tooltips, number formatting and a consistent colour-blind-safe palette
Files
File	Contents
HA1_Thit_Kelvin.twbx	Packaged Tableau workbook (includes the data). Open with Tableau Desktop or the free Tableau Reader.
HA1_Thit_Kelvin.docx	Executive brief and appendix of Tableau proof-of-skill screenshots
Tools

Tableau Desktop 2026.1, Superstore sample data

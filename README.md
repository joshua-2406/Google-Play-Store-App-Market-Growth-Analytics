Google-Play-Store-App-Market-Growth-Analytics

Overview

Public Play Store dataset (10,841 apps) cleaned in Python (pandas), then modeled and visualized in Power BI as a 4-page interactive dashboard — designed less as a set of charts and more as a strategy document: where's the whitespace, what pricing works, and what actually drives installs.

Dashboard Pages

1. Category Performance
AI-driven Key Influencers visual identifying what pushes an app into the "High Installs" tier — factors like pricing type, rating band, size, and category, ranked by influence multiplier (e.g. being a Free app made High Installs ~13x more likely).

2. Whitespace Opportunity
Custom quadrant scatter chart (App Count vs. Installs per App) with median reference lines splitting categories into Dead Zone, Pricing, Saturated & Weak, and true Whitespace — surfacing categories like Video Players and Entertainment that have low competition but strong installs-per-app.

3. Field Parameter Toggle
Dynamic metric switcher (Total Installs / Avg Rating / App Count) using Field Parameters, sliced by Price Band, letting the same visual answer different business questions without duplicating charts.

4. Gauge Visual — Catalog Health
Single KPI gauge tracking % of apps updated in the last 90 days (43.36% in this dataset) — a proxy for how actively a category or catalog is being maintained.

Key Findings


Apps updated within the last 90 days averaged 15.1M installs, versus 1.2M for apps untouched for 12+ months — a ~12x gap, suggesting Play Store's discovery algorithm rewards active maintenance, not just app quality.
Games and Communication apps dominate total installs but are also the most saturated categories. Video Players, Entertainment, and Weather carry far less competition while still holding strong installs-per-app — genuine whitespace, not just an assumption.
App size showed almost no correlation with installs (r ≈ 0.13) — users don't appear to select apps based on file size.
Free-with-in-app-purchase outperformed upfront paid pricing by a wide margin; among paid apps, pricing under $5 clearly beat premium pricing.


Key Techniques Used


Python (pandas) for data cleaning and preprocessing before load
Power BI Key Influencers visual for AI-driven driver analysis
Custom quadrant/whitespace chart with median reference lines
Field Parameters for dynamic metric-switching across visuals
Gauge visual for single-KPI catalog health tracking


Tools

Python (pandas) · Power BI Desktop · Power Query · DAX



# Bengaluru Cloud Kitchen Strategy: Zomato Market Analysis

## Business Task

Advise a restaurant investment group on the optimal location, pricing strategy, and market positioning for a new Cloud Kitchen in Bengaluru using historical Zomato platform data.

## Tech Stack & Data Processing

- Python (Pandas, NumPy): Handled complex data cleaning on 51,000+ rows of raw Indian market data.
- Data Transformation: Engineered custom functions to parse messy string data (e.g., stripping '₹' and commas from prices, converting fraction strings like '4.1/5' into raw float aggregates).
- Visualization (Seaborn, Matplotlib): Built geospatial and pricing scatter plots to identify market gaps.

## The BLUF (Key Insights)

- Geospatial Demand: BTM, Koramangala (5th Block), and Indiranagar dominate raw order volume and engagement. However, due to hyper-competition, launching a Cloud Kitchen in adjacent "spillover" areas like HSR Layout offers a better restaurant-to-customer density ratio.
- The Pricing "Sweet Spot": The scatter plot analysis reveals that a higher price does not guarantee a better rating. The highest density of 4.0+ rated restaurants operates in the ₹400 - ₹800 (Cost for Two) range. Pricing outside this band faces steep drop-offs in customer engagement.

## Strategic Recommendations

- Launch Location: Target HSR Layout for the initial Cloud Kitchen facility to capture high tech-worker demand with slightly lower competition than Koramangala.
- Menu Pricing: Cap the "Cost for Two" at ₹600. The data proves this is the optimal threshold to achieve high volume and maintain a 4.0+ rating on the platform.

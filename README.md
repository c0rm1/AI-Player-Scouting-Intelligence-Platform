# AI-Player-Scouting-Intelligence-Platform
Goal: Create a professional scouting tool that ranks players, identifies similar profiles, and generates evidence-based scouting reports.

Build plan
1. Import player statistics, positions, minutes played, and season data.
2. Clean data and normalise metrics per 90 minutes or possessions.
3. Implement kNN and cosine similarity to find comparable players.
4. Apply K-Means and PCA to discover player archetypes.
5. Create radar charts, percentile rankings, and similarity visualisations.
6. Add a natural-language scouting report that references actual statistical evidence.
7. Deploy an interactive scouting dashboard.
Suggested stack: Python, pandas, scikit-learn, PostgreSQL, FastAPI, React, Plotly.

Module practice: kNN, clustering, dimensionality reduction, preprocessing, cloud APIs.

Evaluation: Similarity quality, cluster stability, position-aware comparisons, and agreement with expert-labelled examples.

Extension: Build a searchable multi-season database that answers questions such as “Find U23 midfielders similar to Declan Rice but with higher progressive passing numbers.”

Data: StatsBomb Open Data for football, or publicly available NBA player statistics.

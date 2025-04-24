# Assignment 2: Amazon Review Data Storytelling with Tableau

## Project Overview

This project analyzes Amazon customer reviews for the Electronics category during 2021. The goal is to leverage Tableau's data storytelling capabilities to create an interactive and visually compelling narrative that answers critical business questions related to product trends, customer sentiment, and purchase behaviors, without relying on separate reports.

Project submitted by: Tauheed Akbar And Talha Sheikh

### Data Source

The analysis is based on a sample dataset created by combining and preprocessing three sources:
*   All Amazon Reviews JSON dataset
*   Amazon Product Dataset
*   Stanford Amazon Meta Dataset

The combined data was cleaned, structured, and focused on the specified category and year to prepare it for Tableau analysis.

### Objectives

*   Develop interactive Tableau dashboards visualizing key aspects of customer reviews.
*   Create a cohesive data story that guides the user through the analysis.
*   Answer critical business questions regarding customer sentiment, review trends, product performance, potential anomalies, and purchase patterns.
*   Design visually appealing and user-friendly dashboards with clear insights.

### Tools Used

*   Tableau Desktop (for visualization and storytelling)

## Dashboard Navigation Guide

The analysis is presented as a Tableau Story, guiding the user through the findings step-by-step. Open the `.twbx` file and navigate using the story points (tabs) at the top.

1.  **1. How Do Customers Feel? Sentiment Snapshot (Electronics):**
    *   Provides an overview of customer sentiment using a word cloud for frequent terms and a heatmap showing sentiment distribution across categories.

2.  **2. Review Engagement & Seasonal Patterns:**
    *   Examines review volume trends over time (yearly) and reviewer activity patterns month-by-month (seasonal heatmap) to identify peak periods.

3.  **3. Comparing Products: Rating vs. Review Volume:**
    *   Uses a scatter plot to compare individual products based on their average rating and the number of reviews received, identifying top performers and potentially overlooked products.

4.  **4. Identifying Unusual Review Patterns:**
    *   Visualizes monthly review volume to spot sudden spikes and uses a bubble chart to highlight products with potentially anomalous repeat review activity, aiding in fraud detection.

5.  **5. Verified Purchases: Impact on Rating & Volume:**
    *   Analyzes the relationship between verified purchase status, review sentiment/rating buckets, and overall review volume using a heatmap and bar chart.

6.  **6. Summary & Key Business Insights:**
    *   Consolidates the key findings from the previous points and provides direct answers to critical business questions derived from the analysis. Features the Sentiment dashboard for visual context.

Interactivity: Feel free to use the filters (e.g., Category, Rating, Verified Purchase) embedded within the dashboards on each story point to explore the data further. Hover over data points for detailed tooltips.

## Key Insights Summary

The analysis uncovered several key insights:

1.  **Overall Positive Sentiment:** Customers generally express positive feelings about Electronics products, frequently mentioning usability ("easy", "use") and performance ("great", "good", "works").
2.  **Strong Seasonality:** Review activity significantly peaks in Q4 (October-December), aligning with holiday shopping seasons.
3.  **High Ratings vs. High Volume:** Many products achieve high ratings (4.0+), but combining high ratings with high review volume is less common. These high-volume, high-rated products are likely key drivers.
4.  **Anomaly Detection Markers:** Sudden spikes in monthly review volume and unusually high repeat reviews for specific products serve as potential indicators for further investigation into authenticity.
5.  **Verified Purchase Dominance & Correlation:** Verified purchases constitute the vast majority of reviews and show a strong correlation with higher product ratings (predominantly in the 'High' rating bucket).

## How to View

1.  Ensure you have Tableau Desktop or Tableau Reader installed.
2.  Open the  file located in the `dashboards/` folder.
3.  Navigate through the story using the tabs at the top.
4.  Interact with filters and tooltips for deeper exploration.


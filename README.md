# Retail Chain Profit Analysis 

## Project Overview

Assuming that a retail chain operating in the United States approached us to create a Tableau visualization analyzing profit contributions at different geographic levels. This visualization provides insights into state-wide and city-level profit contributions using dual-axis maps and Level of Detail (LOD) calculations.

![Screenshot 2025-03-27 124408](https://github.com/user-attachments/assets/217304b0-983b-488a-9d6b-07c01981e39c)


## Visualization Breakdown

1. State-Level Profit Analysis

The color of each state represents the average profit across cities in that state.

This helps in understanding which states have overall higher or lower city-level profit averages.

2. City-Level Contribution Analysis

The size of each circle represents the average profit a city contributes to its respective state.

The color of the circle indicates the profit contribution's nature:

*    Blue: Positive contribution to the state's overall profit.

*    Red: Negative contribution to the state's overall profit.

3. LOD Calculation Usage

LOD (EXCLUDE) calculations were used to compute state-level profits while excluding city and postal code details.

This allows us to display the average city profit per state without city-level granularity distorting the values.

4. Dual-Axis Chart Implementation

*    First Map Layer:

Shows state colors based on the average profit across cities.

*    Second Map Layer:

Adds circles at city locations, where:

1. Size = Average city profit contribution to state

2. Color = Contribution direction (blue for positive, red for negative)

## Key Insights

*    This visualization helps identify which states have cities driving or dragging overall profitability.

*    The interactive nature allows users to explore city-wise contributions and drill down into specific problem areas.

*    The use of LOD calculations ensures accurate state-level profit representation while maintaining city-level insights.

## Tools & Technologies Used

1. Tableau for data visualization

2. LOD Expressions for precise aggregation handling

3. Dual-Axis Maps to combine state-level and city-level insights

4. Color Encoding for clear profit differentiation

## How to Use

*    Hover over states to view their average city profit values.

*    Hover over city circles to see their exact profit contributions.

*    Analyze color and size to identify key areas impacting state profitability.

## Conclusion

This Tableau project provides a clear, interactive, and insightful visualization for a retail chain to analyze profitability across states and cities. By leveraging LOD calculations, dual-axis charts, and strategic color encoding, this visualization helps decision-makers identify key areas for improvement and growth.


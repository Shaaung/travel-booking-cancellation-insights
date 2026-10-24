# Travel Booking & Cancellation Insights

[Explore the interactive Tableau workbook](https://public.tableau.com/views/TravelBookingandCancellationInsights/TravelBookingCancellationOverview)

An interactive Tableau case study of 1,000 travel bookings from the [Travel & Tourism dataset](https://www.kaggle.com/datasets/madhavw/travel-and-tourism). The workbook combines a destination dashboard, a quarterly movie, and a four-part story to explore where cancellations occur and how patterns change over time.

## Key findings

- 141 of 1,000 bookings were cancelled, an overall rate of 14.1%.
- Indonesia (25.0%, 11 of 44), the United Arab Emirates (19.0%, 8 of 42), and the United Kingdom (17.1%, 7 of 41) have the highest observed destination rates. Each has fewer than 50 bookings, so these are leads for further investigation rather than definitive rankings.
- India accounts for 669 bookings and 95 cancellations. Its cancellation rate is 14.2%, close to the overall rate.
- Family emergencies (27), transportation disruptions (24), and visa issues (22) are the most frequent cancellation reasons.

## Workbook views

| View | What it shows |
| --- | --- |
| Overview | Key metrics, a booking-volume map, destination cancellation-rate ranking, and cancellation reasons linked by interactive actions. Booking year and transportation filters support comparisons. |
| Movie | Quarterly Pages animation comparing cumulative cancellation rate and average trip cost. Bubble size represents cumulative bookings; a 14.1% reference line provides context. |
| Story | Four points that connect the overall pattern, destination differences, cancellation reasons, and possible operational responses. |

## Tableau techniques

Calculated fields derive booking counts, cancellation counts, rates, and leading reasons. Map and bar-chart encodings show volume and rate separately. Dashboard filter and highlight actions connect views, while running-sum table calculations and the Pages shelf create the quarterly animation.

The dataset contains 1,000 records, with booking dates from January 2024 through August 2026. Small destination samples and the incomplete third quarter of 2026 limit comparisons. The visuals are exploratory; they do not establish that trip cost or destination causes a cancellation.

## Data source

[Travel & Tourism dataset on Kaggle](https://www.kaggle.com/datasets/madhavw/travel-and-tourism). The original data is linked rather than rehosted in this repository.

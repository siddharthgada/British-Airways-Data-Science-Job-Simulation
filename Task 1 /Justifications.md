# 1. How did you group the flights in your table?
I grouped the flights using four different criteria to enable more targeted analysis:

Flight Type and Time of Day: I categorized flights as Long Haul AM, Long Haul PM, Short Haul AM, and Short Haul PM based on their duration and whether they were scheduled to depart in the morning or evening.

Region-Based Grouping: Flights were grouped according to their destination regions (e.g. international or specific geographic zones), allowing for regional trend analysis.

Departure Hour: I organized flights by their exact hour of departure to identify patterns related to specific time windows throughout the day.

Destination City: Flights were also grouped by their destination cities to analyze traffic volumes and demand at a more granular level.

# 2. Why did you choose that grouping method?
"I chose these grouping methods to better understand lounge access demand accordingly:

Flight Type and Time of Day (Long Haul/Short Haul, AM/PM): Lounge usage patterns often vary depending on flight type and departure time. Long haul passengers, especially those departing in the evening, tend to arrive earlier and spend more time in lounges. By separating AM and PM flights, I could analyze peak lounge usage periods and tailor services accordingly.

Region-Based Grouping: Different regions may have varying eligibility rules for lounge access (e.g. premium vs. economy). Grouping by region helped identify which flights brought in more lounge-eligible passengers.

Departure Hour: Grouping flights by departure hour allowed me to pinpoint specific time blocks with high lounge traffic, enabling more accurate staffing and provisioning during peak hours.

Destination City: Certain cities may be associated with higher business travel, leading to increased lounge usage. Grouping by destination helped identify which routes contribute most to lounge occupancy, informing potential upgrades or access policy changes.

# 3. What assumptions did you make about passenger eligibility ? 
Tier 3 (Club Lounge)
Highest eligibility (Avg: 16%, Max: 46%)
Access for Silver cardholders and Business Class passengers. Most commonly used lounge, especially in the evening.

Tier 2 (First Lounge)
Moderate eligibility (Avg: 4%, Max: 16%)
Exclusive to BA Gold members. Used by frequent elite flyers, less crowded than Tier 3

Tier 1 (Concorde Room)
Very limited access (Avg: 0%, Max: 11%)
Reserved for First Class, Premier cardholders, and Gold Guest List members. Highly exclusive, low overall usage which suggests that Tier 1 Lounge might not be needed as of now.

Peak Lounge Demand: 6 PM – 10 PM

Tiers 2 and 3 show highest usage, especially Tier 3. Suggests more premium travelers fly in the evening

# 4. How can your model apply to future or changing flight schedules?

My model is built on flexible grouping variables such as flight time, destination region, and flight type (long-haul vs short-haul). These categories are not dependent on static schedules, which allows the model to adapt to:

Schedule Changes:
Grouping by time of day and destination means the model remains valid even as specific flights are added, removed, or rescheduled.

New Routes or Cities:
City-based and region-based groupings allow easy incorporation of new destinations without needing to rebuild the model.

Seasonal or Demand-Based Adjustments:
Airlines often shift schedules based on seasonal demand. The model's time-based structure (e.g., AM/PM or hourly grouping) captures these patterns dynamically.

Scalable Passenger Forecasting:
Lounge eligibility trends by time and region help predict passenger lounge demand, even with evolving schedules, ensuring proper resource planning.

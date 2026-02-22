# An Ode to Gravel

There’s nothing better than the sound of gravel crunching under your tires.

This project explores eight months (90 rides) of gravel cycling data exported from Strava and analyzed in pandas using Google Colab.

What started as a simple question -- what would I find if I downloaded my ride history and started digging? -- turned into a small data exploration of mileage, elevation, time spent riding, and weekly patterns.

## Question Explored
- How far did I ride?
- How much time did I spend on my bike?
- How much climbing did I do?
- What day of the week was my most prolific?

## Results (High Level)
- 998 total miles
- 59,789 feet climbed
- 109.5 moving hours
- 76-day gap due to injury
- 20 moving hours per active month
- 10,937 ft climbed per active month
- Monday was my most prolific day across mileage, climbing, and time

## Running This Yourself
If you export your own data from Strava, you can use this notebook as a jumping-off point. The structure is simple and built around standard activity export files.

Place your exported files locally (not committed to the repo) and adjust column names as needed.

## Next Steps
This is just the beginning of the trail. I'm curious to dig into the GPX files Strava provides, which offer route mapping and terrain analysis possibilities.

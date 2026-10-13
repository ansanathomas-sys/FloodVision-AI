The problem

During floods, it’s hard to quickly tell which areas need attention first.
Information comes from many sources (rainfall, river levels, terrain), and decision-makers need one clear picture.

What FloodVision AI does

It screens 14 locations across Kerala and sorts each one into Low, Medium or High risk.
A colour-coded interactive map shows where the risk is, and a priority list shows which areas to assess first.
Charts show rainfall, water level against the danger mark, and a 7-day trend per location.
A summary table lists the areas needing further assessment, with the reason each was flagged. It can be downloaded as CSV.

How the risk is calculated (easy to explain to judges)

The score has three parts: 3-day rainfall (40%), water level relative to its danger mark (40%) and how low-lying the terrain is (20%).
Below 0.35 is Low, 0.35 to 0.60 is Medium, and 0.60 or above is High.
It is explainable: every flag comes with a plain-language reason, so it’s not a black box.

Honesty about data

The website uses simulated sample data, and says so with a badge, a banner and chart labels.
Elevations and danger levels are illustrative placeholders, not official figures.
Weights and thresholds are chosen for the demo and are not calibrated against past floods.
It is a screening prototype, not an early-warning system. Official alerts come from IMD, CWC and KSDMA.

Space-tech angle (the roadmap)

Sentinel-1 radar can map surface water through cloud cover, which matters because floods come with heavy cloud.
Satellite rainfall and soil-moisture data can replace the simulated inputs.
Official river-gauge data can then replace the simulated water levels.

Why it’s useful

It gives a fast first look at which areas to investigate.
It is simple to read, with no training needed.
It is easy to extend to more locations or other states.

Demo flow (about 2 minutes)

Start on Light rain: the map is mostly green.
Slide to Extreme rain event: markers turn red, and the priority list fills.
Click a red marker to show its rainfall and water-level trend.
Scroll to the assessment table and show the reasons and the CSV download.
Close with the roadmap: swap simulated inputs for satellite and gauge data

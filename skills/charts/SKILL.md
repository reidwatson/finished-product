---
name: charts
description: Choose the chart that answers the viewer's question and encode it honestly, with real identities, meaningful color, interactive marks, and designed sparse and empty states. Use whenever building a chart or data visualization.
license: MIT
---

# Charts

Start from the question the viewer is answering. Each visualization makes one point first; everything else in it supports that point. Name the question before choosing the form.

Pick the form by what the data does. One number is a large figure with its change. Comparing items is sorted bars. Change over time is a line; discrete events like games are columns. Gain and loss, win and loss, diverge from a zero line. Part of a whole is one stacked bar or a treemap with the tail folded into Other. Rank within a group is a position on a scale with "#n of N". State is a marker with a label. When the answer is a single value, don't draw a chart.

Show the real things. People get their photos, teams and brands their marks and colors, products their images. Identity should be recognizable at a glance, not decoded from a legend. Abstract shapes are the fallback, not the default.

Encode honestly. Position and length first, then area, then color. Bars start at zero. Area matches value. One scale per chart. Give values their frame once: the population, the average, the previous period, the zero line.

Keep color meaningful. An entity keeps its color everywhere in the product. Status colors only mean status. Validate contrast and color-blind separation in light and dark modes. Text uses text colors; color sits on the mark beside it.

Design every size of a repeated mark. Tiles, cards and bars appear large, medium and small; decide what each size shows, and drop elements before they collide, clip or truncate into nonsense. Label selectively: the headline value, the extremes, the latest point.

Make marks interactive. Touching or hovering a mark shows its exact value, and opening it leads to the record it represents. Time series scrub. Ranges and scopes are controls above the chart, not separate charts.

Design sparse and empty data. A chart with one point or no movement isn't a chart. Widen the default range to where movement exists, or show the state plainly. Missing data stays visibly missing, never drawn as zero.

Test with real distributions on the narrowest screen: one dominant value with a long tail, many tiny values, long names, a single data point, nothing at all. Render it with real data and put it next to the reference design or the best example you know. If the reference looks better, it isn't done.

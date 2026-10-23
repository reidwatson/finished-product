# Finished Product

Completely avoid adding any text whatsoever that reflects your internal thoughts, concerns, or opinions in your products.

You might think one way or another about a feature. You might have an interesting thought while making an artifact. The end user does not need to hear it. Keep it to yourself, or tell the creator in the existing chat.

You weren't asked for your opinions. You were asked to build a product. Never add your own conjecture or opinion about making the thing to a website, PDF, email, graphic, or other output meant to be seen and used by people.

Do you really need that subtitle? Is that extra line of copy seriously necessary? Does the footer need a little tidbit from the creator? Probably not. Just keep it in the chat.

You might think an explanation within this element will cover all of your bases. Wrong. The answer is to make things that speak for themselves. If you have to explain it, it isn't intuitive to use / see / read

Facts can be slop too. Every bit of text must be absolutely essential to the product. Repeated explanatory copy is a hard failure. State shared context once. Never repeat "vs. previous 30 days" under every metric: show the period once and use clear visual indicators with the values. Use consistent symbols, shape, position, and layout for recurring statuses. Don't add duplicate dates or currency notes, or scatter account labels, attribution notes, "SAMPLE DATA" stamps, and raw "svg" text around the page. Design essential numbers into metrics, charts, tables, and controls.

When humans use LLMs to create things, the LLM does not need to address the audience as itself, period. Speak to the creator in the existing chat medium.

Inspect the whole finished product, including repeated cards, rows, and states. Don't just remove phrases the user flagged. Find the same failure everywhere. Delete every word that isn't absolutely essential.

## Show, don't write

LLMs work with text, so they reach for text. Humans just want to see the information and intuit what it's saying. Text is the last resort for conveying information, especially numbers.

Start with what the user is trying to do on the page. That action leads, and the page directs them to it. Everything else is visual and secondary. It should feel like a dashboard.

Every value has a natural shape. Before writing a value as words, find the visual indicator that fits that specific value and design it in. Relationships between things show through typography, grouping, and position, not a line of text the user has to decode.

If something isn't clear, fix the design, not the copy. UI work isn't done until the UX is good.

## Settings and metrics

A value is shown before it is edited. Never render saved settings as permanently open inputs: read mode shows each value in its natural form, ideally drawn into the thing it controls, and an explicit Edit action turns them into fields. Edit mode shows what will change before it is saved (the new value beside the current one, a preview drawn over the current state), then Save or Cancel returns to read mode. Inputs that sit open on every visit read as unfinished and invite accidental changes.

A row of large numbers in identical cards is not a visualization. It means the numbers were not understood. Before placing any metric, ask what it is part of and what it is compared with: counts that sum to a population are one stacked bar or a funnel, activity over time is a series, a level is judged against its target or its previous value. Put a number in a card only when it is a single headline value with its change, and never repeat that card four times across the page.

## Tables

A table is not a pile of text. Decide what each column means before building it. One record per row. One field per column. One value per cell. No stacked facts or fake second rows.

Align text left and numbers right. Headers follow their columns. Use digits that line up. Keep dates, units, decimals, padding, and row structure consistent. Set column widths deliberately. Short values stay on one line. Handle long values consistently and make the full value available. No random wrapping, collisions, or crushed columns.

In interactive products, tables need working search, filters, sorting, and pagination. Give row actions one consistent place. Controls must change the actual results and show their state.

Inspect long names, big numbers, missing values, empty results, loading, and errors. Check narrow and wide screens. Use the controls, including keyboard navigation. Fix the whole table, not just the first row.

## Visualize data

Start from the question the viewer is answering. Each visualization makes one point first; everything else in it supports that point. Name the question before choosing the form.

Pick the form by what the data does. One number is a large figure with its change. Comparing items is sorted bars. Change over time is a line; discrete events like games are columns. Gain and loss, win and loss, diverge from a zero line. Part of a whole is one stacked bar or a treemap with the tail folded into Other. Rank within a group is a position on a scale with "#n of N". State is a marker with a label. When the answer is a single value, don't draw a chart.

Show the real things. People get their photos, teams and brands their marks and colors, products their images. Identity should be recognizable at a glance, not decoded from a legend. Abstract shapes are the fallback, not the default.

Encode honestly. Position and length first, then area, then color. Bars start at zero. Area matches value. One scale per chart. Give values their frame once: the population, the average, the previous period, the zero line.

Keep color meaningful. An entity keeps its color everywhere in the product. Status colors only mean status. Validate contrast and color-blind separation in light and dark modes. Text uses text colors; color sits on the mark beside it.

Design every size of a repeated mark. Tiles, cards and bars appear large, medium and small; decide what each size shows, and drop elements before they collide, clip or truncate into nonsense. Label selectively: the headline value, the extremes, the latest point.

Make marks interactive. Touching or hovering a mark shows its exact value, and opening it leads to the record it represents. Time series scrub. Ranges and scopes are controls above the chart, not separate charts.

Design sparse and empty data. A chart with one point or no movement isn't a chart. Widen the default range to where movement exists, or show the state plainly. Missing data stays visibly missing, never drawn as zero.

Test with real distributions on the narrowest screen: one dominant value with a long tail, many tiny values, long names, a single data point, nothing at all. Render it with real data and put it next to the reference design or the best example you know. If the reference looks better, it isn't done.

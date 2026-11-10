---
name: show-dont-write
description: Design interfaces that show information visually instead of writing it out. The page leads with the user's action, values get visual indicators, settings have read and edit modes, and metrics are placed by what they mean. Use for any UI or UX work.
license: MIT
---

# Show, Don't Write

LLMs work with text, so they reach for text. Humans just want to see the information and intuit what it's saying. Text is the last resort for conveying information, especially numbers.

Start with what the user is trying to do on the page. That action leads, and the page directs them to it. Everything else is visual and secondary. It should feel like a dashboard.

Every value has a natural shape. Before writing a value as words, find the visual indicator that fits that specific value and design it in. Relationships between things show through typography, grouping, and position, not a line of text the user has to decode. Use consistent symbols, shape, position, and layout for recurring statuses.

If something isn't clear, fix the design, not the copy. UI work isn't done until the UX is good.

## Settings

A value is shown before it is edited. Never render saved settings as permanently open inputs: read mode shows each value in its natural form, ideally drawn into the thing it controls, and an explicit Edit action turns them into fields. Edit mode shows what will change before it is saved (the new value beside the current one, a preview drawn over the current state), then Save or Cancel returns to read mode. Inputs that sit open on every visit read as unfinished and invite accidental changes.

## Metrics

A row of large numbers in identical cards is not a visualization. It means the numbers were not understood. Before placing any metric, ask what it is part of and what it is compared with: counts that sum to a population are one stacked bar or a funnel, activity over time is a series, a level is judged against its target or its previous value. Put a number in a card only when it is a single headline value with its change, and never repeat that card four times across the page.

## Banned styling

Never put a colored accent stripe on one side of a card, row, or callout: no `border-left` (or `borderLeftWidth`) in a brand or status color on a rounded box. It is the clearest sign a UI was generated, not designed. Separate and emphasize with layout, type, and color on the content itself.

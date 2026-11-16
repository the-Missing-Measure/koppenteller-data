# Koppenteller: open data

Who is in the Dutch news headline? Koppenteller counted the people in 21,574 headlines from fifteen Dutch news outlets, from January 2025 to November 2026. Of the 9,339 people whose gender the headline shows, 26% are women (margin 24% to 28%).

This repository holds the open data behind [koppenteller.nl](https://koppenteller.nl), a project by [The Missing Measure](https://missingmeasure.com). The website, the methods and the full explanation of every column are on the site itself.

## Files

`data/koppenteller-koppen.csv` has one row per headline (21,574 rows). `data/koppenteller-personen.csv` has one row per woman or man in a headline (9,339 rows). Both are UTF-8 CSV with commas. The text of the headlines and the names are not included.

The columns are explained on [koppenteller.nl/en/data](https://koppenteller.nl/en/data) (Dutch: [koppenteller.nl/data](https://koppenteller.nl/data)).

## Method, in short

Every headline was read by a language model (Claude, by Anthropic) following a fixed handbook, in two rounds. A check by people has started but is not finished, which is why Koppenteller is a pilot. What was counted, how, which period, what was left out and where it can go wrong is on [koppenteller.nl/en/methods](https://koppenteller.nl/en/methods). Read it before drawing conclusions: differences between outlets mostly reflect which news feeds were archived, not how a newsroom works.

## Version

Version of 14 November 2026. Each new version of the data gets its own release here.

## Licence and citation

The data is published under [CC BY 4.0](LICENSE). Cite as:

Bussink, A. (2026). Koppenteller: wie staat er in de kop (open data, version 14 November 2026). The Missing Measure. https://koppenteller.nl/data

Spotted a mistake? Write to astrid@missingmeasure.com. Corrections are made on the site and noted there.

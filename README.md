# VicParl Member Quiz

Adaptive learning tool for Victorian Parliament reporters.

## Dataset
`members.json` contains 128 current members sourced from the workbook's `Data-MA` worksheet: 88 Legislative Assembly and 40 Legislative Council members. Image filenames are mapped to the supplied LA and LC filename inventories, including `.jpg` / `.jpeg` and preferred-name exceptions.

## Current modes
- Flashcards
- Quiz: Name, with optional progressive hints: chamber, electorate/region, then four-name multiple choice
- Quiz: Electorate / Region, free recall followed by optional multiple choice
- My Progress, stored locally in the browser between sessions
- Adaptive question selection gives greater weight to weaker or missed items

## Repository image structure
- `images/LA/` for the 88 Assembly images
- `images/LC/` for the 40 Council images

## Palette
- LA: `rgb(0, 90, 54)`
- LC: `rgb(124, 26, 34)`
- Admin: `rgb(32, 21, 71)`
- Main stage: `rgb(0, 76, 151)`

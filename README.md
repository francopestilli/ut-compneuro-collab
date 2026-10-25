# Neuroscience Collaboration Map

A one-page, self-contained view of how seven UT Austin neuroscience research programs overlap, built to support the discussion of a computational neuroscience center.

Open `index.html` in any browser. It has no dependencies and works offline.

## What it shows

- A network of seven researchers and 17 research themes. Box size and shade show cross-lab overlap.
- The major modes of common interest, ranked.
- NeuroAI as an emerging theme anchored in neural data methods.
- Collaboration ideas, and a collapsed section with profile similarity and theme scores.

## Method

Publication records come from OpenAlex (author profiles, 25 most-cited works per person, and pairwise co-authorship searches). Each work was coded into themes and scored 0 to 3 for involvement. Cross-lab overlap is, for every pair of labs, the smaller of their two scores in a theme, summed.

## Caveats

- Top-cited works skew toward older papers, so recent shifts are underweighted.
- Several OpenAlex profiles contained misattributed records, which were excluded.
- NeuroAI scores and AI-agent work come from the author's own description.
- Each researcher should confirm their own row.

## Sharing

If you publish this with GitHub Pages, the page is public. Keep the repository private for internal discussion, and note that GitHub Pages for private repositories requires a paid plan.

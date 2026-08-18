# braintube

A YouTube feed filtered down to what one person actually wants to watch.

Videos from the channels I subscribe to are scored 1–10 by a local LLM against
a written description of my interests; anything scoring below 6 never reaches
this page. The page itself is static — the score slider, ranking, and the
"recently published" boost all run in your browser, so there is no server
behind it.

Published to GitHub Pages by [BrainTube](https://github.com/brainwagon/mytube).
Regenerated whenever the feed is re-scored.

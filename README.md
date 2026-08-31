# lobbying-feed

A live wire on lobbying worldwide: who paid whom to shape the law, through what
register or none.

Built after "For Money, Not Law" on Welcome to Your Galaxy and the sources its
footnotes point to — the OECD on which countries disclose what, OpenSecrets on
spending and the bills lobbied for, InfluenceMap on climate policy engagement
by companies and trade associations, Corporate Europe Observatory's
RevolvingDoorWatch, and the Revolving Door Project.

## The twenty subjects

| | |
|---|---|
| What is spent | The lobbyists themselves |
| Unregistered and shadow lobbying | The revolving door |
| Registers, disclosure and transparency | Whether it is regulated at all |
| Who writes the law | Access, donations and who gets heard |
| The bodies most lobbied | Trade associations and industry groups |
| Front groups and astroturf | Funded research and captured expertise |
| Climate policy obstruction | Financial sector lobbying |
| Food, drink, tobacco, pharma, gambling | Technology and platform lobbying |
| States, cities and governments lobbying | Lobbying for foreign powers |
| Second jobs and conflicts of interest | What is set against it |

Two departures from the section, both deliberate. Its footnotes say the
presentation covered only corporations and industry associations, leaving out
unions, non-profits and government bodies lobbying each other; this wire
carries the last of those, because a city hiring a firm to work the federal
budget is the same machinery pointed a different way. And it treats funded
research and captured expertise as lobbying rather than as a food-industry
story, since paying for the study that decides the policy is influence bought
earlier in the chain.

## The gate

A hotel lobby is refused, as is ordinary business and policy coverage with no
influence angle, and the election horse race, which belongs to the voter wire.

A story no subject will claim is refused and counted as refused, rather than
filed under a fallback subject it did not earn.

## Weight

A decision (2), institutional material (2), a measured figure (1), a pending
decision with a date (1), a named jurisdiction (1), a primary source (1). At
three or more it is marked consequential.

## Sources

184 wires. 30 direct feeds carried over from the sibling repos where they are
already proven, plus 138 Google News locale searches across 26 languages with
24 rotating queries, and 16 subject searches.

The section's own research list is the obvious thing to add, with URLs you have
opened: OpenSecrets, InfluenceMap, the Revolving Door Project,
RevolvingDoorWatch, LobbyFacts, and the OECD lobbying transparency pages.

## Running it

    python3 harvest_lobbying.py
    python3 harvest_lobbying.py --dry-run
    python3 verify_sources.py

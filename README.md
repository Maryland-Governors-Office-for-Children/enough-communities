# ENOUGH Communities Map

Live page: https://maryland-governors-office-for-children.github.io/enough-communities/

A map and list of the 30 communities in Maryland's ENOUGH Initiative, designed by GOC Communications.
The first version of the page, exactly as GOC Communications designed it, is saved in this repository under the
tag `maddy-original`.

## What the page includes

- **Accurate map.** Real Maryland and county outlines from the U.S. Census Bureau, with the census
  tracts each community serves shaded in.
- **Close-ups** of the Baltimore area and the Washington, DC suburbs, with every community labeled.
  On phones the close-ups fit the screen, with larger markers and a list of names to tap.
- **Figures for every community.** Each pop-up shows the share of children living in poverty and
  the ENOUGH funds awarded, calculated from the same source for all 30 communities.
- **At-a-glance figures** (communities, census tracts, counties) worked out from the data,
  so they stay correct when the list changes.
- **Progress stories** for the eight featured communities in their pop-ups, which can also be opened from
  the list.
- **County filter** on the list of all communities.
- **About the data** section explaining each figure and why some poverty rates are below 30%.
- **Accessibility:** keyboard access to every marker, Escape closes a pop-up, skip link, visible focus,
  text contrast that meets WCAG AA, and no motion for visitors who turn it off.
  The page passes an automated axe-core check (WCAG 2.1 A and AA) with no issues.
- **Privacy and speed:** fonts are served from this site, so the page makes no third-party requests.
- **Link previews** when the page is shared on social media or in email.

## How to update the page

- **Community text** (names, links, strategies, stories): edit the block marked `CONTENT` near the
  top of the script in `index.html`.
- **Figures** (funds, children, poverty, tracts) come from the ENOUGH Master Sheet. The Governor's Office for
  Children data team rebuilds them.

## Sources

- Child poverty: GOC analysis of U.S. Census Bureau American Community Survey 5-year estimates, 2020–2024.
- Funds awarded: GOC grant records, fiscal years 2025 through 2027.
- Boundaries: U.S. Census Bureau cartographic boundary files, 2024.
- Font: Source Serif 4, SIL Open Font License (`fonts/OFL.txt`).

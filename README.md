
## Latest May 23 follow-up update

- Replaced the hero **Sponsored By Bitcoin** badge icon with the provided Bitcoin image and tilted it **14° clockwise**.
- Added a **Satoshi.movie** link to every **Cryptography Mailing List** card and dialog view.
- Corrected **Entry 6** text from **sourceforge.com** to **sourceforge.net**.
- Moved the **Other** lane on the Timechain map into the upper group, below **SourceForge / Bitcoin list** and above the central Timechain line.


## Latest fullscreen and source-default update

- Added one **Other** timeline entry dated **2008-11-16** containing the combined early source-code comments from `nov08 code comments main node main combined.ods`.
- Added a **Full screen** button to the Timechain map controls so users can expand the zoomable timeline into a full-screen view and exit again.
- Changed the initial source-filter state so all datasets are selected by default **except Patoshi Blocks**, keeping the largest 21,951-entry dataset off until a user turns it on.


## Latest sponsor and Other-events update

- Added **8 Other timeline events** from `Other Events to add to timeline 8.ods`.
- Added a small right-side hero badge with an orange Bitcoin logo above **Sponsored By Bitcoin**.
- Added weekday labels to timeline card dates, modal dates, focused timeline labels, and deep-zoom day tick marks without changing the overall layout.

## Latest visual refresh

- Updated the TimeChain motif again so the center line uses small standalone **₿** symbols with interlinking infinity-style connectors and no filled circles.
- Removed the **Download JSON** button from the timeline controls.
- Restyled the central **TimeChain** line to a more gold Bitcoin-link motif inspired by the supplied reference image.
- Refined the central **TimeChain** line again so it uses smaller, subtler, more transparent **₿** symbols connected by infinity-like loops.

# Satoshi Nakamoto Quote Timeline

## Latest Patoshi Blocks update

- Added **21,951 Patoshi Blocks** from `patoshi_block_heights_matchedbytheamazingchatgpt.xlsx`.
- Added a dedicated **Patoshi Blocks** category/lane to the zoomable timeline graphic and source filters.
- Each Patoshi block card includes the block height and UTC timestamp from the spreadsheet.
- Added density-aware rendering for Patoshi Blocks so the map stays responsive while still keeping the full dataset searchable.

This is a dependency-free static website intended for GitHub Pages. It showcases extracted Satoshi Nakamoto writings from `Kicking_the_Hornets_Nest-e3-20241005.pdf` plus all quote instances extracted from `33 missing satoshi quotes form theymos.ods`.


## Latest layout refinement

- Compressed the search/filter/year controls section so the source chips take less vertical space.
- Refined the TimeChain map links into a tighter, interlocked, mostly gold chain motif.

## Latest visual update

- Removed the four hero statistic boxes below the headline.
- Updated the timeline graphic with a TimeChain-inspired linked chain track, category connectors, and block-like event markers while keeping the existing layout, controls, filters, cards, and modal behavior intact.

## Latest code commit update

- Added **164 Satoshi code commit events** from `CHATGPT excel of all commits with deets NO CODE ADDITIONS JUST COMMENTS.xlsx`.
- Added a dedicated **Code Commits** category/lane to the zoomable timeline graphic and filters.
- Each commit card includes the commit number, title/description, date-time, author, added comment snippets, and + / - line counts from the spreadsheet.
- Included an empty `.nojekyll` file for GitHub Pages compatibility.

## Latest update

- Added **33 unique missing Theymos quote instances** from the uploaded ODS spreadsheet.
- The added quote text is preserved from the spreadsheet segments, including original line breaks inside each quote instance.
- Kept the bottom bar chart removed.
- Kept the 10000× deep-zoom timeline, large exhibit height, source lane guides, and GitHub Pages compatibility.

## Files

- `index.html` - page shell
- `styles.css` - responsive styling and large 10000× zoom timeline visuals
- `app.js` - filtering, zoom/pan timeline map, full-screen map mode, and modal quote reader
- `data.js` - timeline data, including the added Theymos quote instances and Satoshi code commit events
- `.nojekyll` - empty file that tells GitHub Pages to serve files directly

## How to host on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder into the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/root`, then save.
6. GitHub will publish the site at `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY/`.

No build step, server, database, Node, or package install is required.

## Data notes

The PDF data was extracted programmatically and organized into source categories. The Theymos spreadsheet additions are labeled under **Theymos Missing Quotes** and source **Theymos missing archive**. The code commit spreadsheet additions are labeled under **Code Commits** and source **Bitcoin source code commit history**. Because these sources are parsed extractions, verify sensitive citations against the original source files.


## Latest update

- Added a dedicated **Theymos Missing Quotes** category/lane for the 33 imported spreadsheet quote entries.


## Latest content update

- Added the 2009-01-13 **Bitcoin SourceForge (s_nakamoto)** “Bitcoin v0.1 released - P2P e-cash” project news quote to the **Other** lane.

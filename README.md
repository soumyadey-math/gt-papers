# Geometry, Topology & Groups: Paper Database

A searchable list of research papers in low-dimensional topology, mapping class groups, Teichmüller theory and geometric group theory, published in 39 leading mathematics journals. The data is compiled from [zbMATH Open](https://zbmath.org/).

**Browse and search:** https://soumyadey-math.github.io/gt-papers/

**Researchers:** https://soumyadey-math.github.io/gt-papers/people.html lists everyone who appears as an author, with last known affiliation, homepage, MathSciNet, zbMATH and Mathematics Genealogy links, publication counts, papers in top journals and major prizes.

## What is included

A paper is listed if at least one of its MSC 2020 codes, primary or secondary, is one of these:

| Code | Area |
|---|---|
| 57K20 | 2-dimensional topology (surfaces, mapping class groups) |
| 57K32 | Hyperbolic 3-manifolds |
| 57M50 | General geometric structures on low-dimensional manifolds |
| 57M99, 57N05 | Other low-dimensional topology; topology of the Euclidean 2-space, 2-manifolds |
| 20F36 | Braid groups; Artin groups |
| 20F65 | Geometric group theory |
| 20F67 | Hyperbolic groups and nonpositively curved groups |
| 20F28 | Automorphism groups of groups |
| 20F34 | Fundamental groups and their automorphisms |
| 30F60 | Teichmüller theory for Riemann surfaces |
| 32G15 | Moduli of Riemann surfaces, Teichmüller theory |

Papers whose title contains "mapping class" or "Teichmüller" are also included even when they carry none of these codes. They are marked "Found by title keyword".

All years are covered for every journal. Records marked **Verified** were confirmed against the publisher's record in Crossref or by two independent reads of zbMATH. The others (**Checked**) were read once and passed consistency checks. Missing DOIs and some zbMATH errors (pages, year, issue) were corrected by hand.

## Using the site

- Type in the search box to search titles, authors, MSC codes and DOIs. Accents don't matter, so `teichmuller` also finds Teichmüller.
- Use `au:` to search authors, `ti:` for titles, `msc:` for codes and `j:` for journals. Put phrases in quotes, for example `ti:"curve complex"`. A leading minus excludes a word, as in `-erratum`.
- Filter by journal, years, status and MSC chips. You can group results by year or by journal, or show a flat list.
- Click an author's name to see all their papers, or an MSC code to filter by it. Click a bar in the year chart to jump to that year.
- **Copy BibTeX** copies one citation. **Download BibTeX / CSV** saves every result that matches the current search.
- **Copy link to this search** gives a URL that reopens exactly this search, which is handy for sharing with students.

## Files

| File | Contents |
|---|---|
| `index.html` | The website (a single page, no build step) |
| `data/papers.json` | The database the page reads |
| `data/papers.csv` | The same data as a spreadsheet |
| `data/papers.bib` | The same data as BibTeX |
| `data/meta.json` | Counts and the last-updated date |
| `people.html` | The researchers page |
| `data/people.json`, `data/people.csv` | The researcher data |

To update the database, replace the four files in `data/`. The page picks them up automatically.

## Corrections

Corrections are very welcome, about papers or about people. If you find an error or a missing paper, or anything about you or a colleague on the researchers page is wrong or out of date (or you would like an entry removed), please [open an issue](https://github.com/soumyadey-math/gt-papers/issues/new) or email the maintainer.

## Credits and licence

Compiled by Dr Soumya Dey, Krea University. Bibliographic data from zbMATH Open, used under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) licence; this compilation is shared under the same licence. Researcher details also draw on Wikidata (CC0) and Jon McCammond's list of [people in geometric group theory](https://web.math.ucsb.edu/~jon.mccammond/geogrouptheory/people.html).

Prepared with the help of Claude (Anthropic): the records were harvested from zbMATH Open, cross-checked and corrected, and the website was built by Claude under the author's direction.

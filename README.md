# Low-Dimensional Topology and Geometric Group Theory: Research Papers Database

A searchable database of research papers in low-dimensional topology, mapping class groups, Teichmüller theory and geometric group theory, published in 39 leading mathematics journals from 1904 to the present. It currently lists about 7,000 papers and 4,000 authors.

- **Papers:** https://soumyadey-math.github.io/gt-papers/
- **Researchers:** https://soumyadey-math.github.io/gt-papers/people.html

The data comes from [zbMATH Open](https://zbmath.org/). Records were checked against the publishers' own DOI records in [Crossref](https://www.crossref.org/), and errors were corrected by hand.

## What is included

A paper is listed if at least one of its MSC 2020 codes, primary or secondary, is one of these:

| Code | Area |
|---|---|
| 57K20 | 2-dimensional topology (surfaces, mapping class groups) |
| 57K32 | Hyperbolic 3-manifolds |
| 57M50 | General geometric structures on low-dimensional manifolds |
| 57M99, 57N05 | Other low-dimensional topology; topology of surfaces |
| 20F36 | Braid groups; Artin groups |
| 20F65 | Geometric group theory |
| 20F67 | Hyperbolic groups and nonpositively curved groups |
| 20F28 | Automorphism groups of groups |
| 20F34 | Fundamental groups and their automorphisms |
| 30F60 | Teichmüller theory for Riemann surfaces |
| 32G15 | Moduli of Riemann surfaces, Teichmüller theory |

Papers whose title contains "mapping class" or "Teichmüller" are included too, even without one of these codes. They are marked "Found by title keyword".

Every year of every journal is covered. The list is only as complete as zbMATH's classification: a paper filed under other MSC codes will be missing, and the newest issues can take a few months to appear.

<details>
<summary><b>The 39 journals</b></summary>

Acta Mathematica · Advances in Mathematics · Algebraic & Geometric Topology · American Journal of Mathematics · Annales de l'Institut Fourier · Annales Scientifiques de l'École Normale Supérieure · Annals of Mathematics · Bulletin of the London Mathematical Society · Cambridge Journal of Mathematics · Commentarii Mathematici Helvetici · Communications on Pure and Applied Mathematics · Compositio Mathematica · Duke Mathematical Journal · Forum of Mathematics, Pi · Forum of Mathematics, Sigma · Geometric and Functional Analysis · Geometry & Topology · Groups, Geometry, and Dynamics · International Mathematics Research Notices · Inventiones Mathematicae · Israel Journal of Mathematics · Journal de Mathématiques Pures et Appliquées · Journal für die reine und angewandte Mathematik · Journal of Differential Geometry · Journal of Geometric Analysis · Journal of Symplectic Geometry · Journal of Topology · Journal of the American Mathematical Society · Journal of the European Mathematical Society · Journal of the London Mathematical Society · Mathematical Proceedings of the Cambridge Philosophical Society · Mathematische Annalen · Mathematische Zeitschrift · Pacific Journal of Mathematics · Proceedings of the American Mathematical Society · Proceedings of the London Mathematical Society · Publications Mathématiques de l'IHÉS · Selecta Mathematica · Transactions of the American Mathematical Society

</details>

## How reliable is it?

Each record carries a status:

- **Verified:** the title, year, volume, issue and pages agree with the publisher's Crossref record, or with two independent reads of zbMATH. This covers almost all records (6,949 of 6,961 as of October 2026).
- **Checked:** read once from zbMATH and passed consistency checks.

The few records where Crossref and zbMATH still disagree carry a note saying which fields differ.

## Searching the papers

- Type in the search box to search titles, authors, MSC codes and DOIs. Accents don't matter, so `teichmuller` also finds Teichmüller.
- Narrow a search with `au:` (author), `ti:` (title), `msc:` (code) or `j:` (journal). Put phrases in quotes, as in `ti:"curve complex"`, and use a minus sign to exclude a word, as in `-erratum`.
- Filter by journal, years, status and MSC code, and group the results by year, by journal, or not at all.
- Click an author to see all their papers, an MSC code to filter by it, or a bar in the year chart to show only that year.
- **Copy BibTeX** copies one citation; **Download BibTeX / CSV** saves every paper matching the current search.
- **Copy link to this search** gives a link that reopens exactly this search, which is handy for sharing a reading list with students.

## The researchers page

The researchers page lists everyone who appears as an author. For each person it gives:

- last known affiliation, checked against the address on their recent arXiv papers where possible (that paper is linked);
- links to their homepage, MathSciNet, zbMATH and Mathematics Genealogy pages;
- how many of their papers are in this database, their total publications in zbMATH, their papers in top journals, their major prizes and their invited or plenary talks at the International Congress of Mathematicians.

People are identified by their zbMATH author profile, so different spellings of the same name are merged. You can search, sort and filter the list, and download it as CSV.

## Corrections

Corrections are very welcome, about papers or about people. If you find an error or a missing paper, or if anything about you or a colleague is wrong or out of date, please [open an issue](https://github.com/soumyadey-math/gt-papers/issues/new) or [contact the maintainer](https://krea.edu.in/about/faculty/sias/soumya-dey/). You can also ask for an entry about you to be changed or removed.

## Citing

If the database is useful in your work, you can cite it as:

> Soumya Dey, *Low-Dimensional Topology and Geometric Group Theory: Research Papers Database*, https://soumyadey-math.github.io/gt-papers/

```bibtex
@misc{dey-gt-papers,
  author       = {Dey, Soumya},
  title        = {Low-Dimensional Topology and Geometric Group Theory: Research Papers Database},
  howpublished = {\url{https://soumyadey-math.github.io/gt-papers/}},
  note         = {Prepared with the help of Claude (Anthropic)},
  year         = {2026}
}
```

## Files

| File | Contents |
|---|---|
| `index.html` | The paper search page (a single page; no build step) |
| `people.html` | The researchers page |
| `data/papers.json` | The paper data the site reads |
| `data/papers.csv`, `data/papers.bib` | The same data as a spreadsheet and as BibTeX |
| `data/people.json`, `data/people.csv` | The researcher data |
| `data/meta.json` | Counts and the last-updated date |

To update the site, replace the files in `data/`; the pages pick them up automatically.

## Credits and licence

Compiled by Dr Soumya Dey, Krea University ([personal homepage](https://sites.google.com/site/soumyadeymathematics) · [Krea profile](https://krea.edu.in/about/faculty/sias/soumya-dey/)). Bibliographic data is from zbMATH Open and is used under the [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) licence. This compilation is shared under the same licence.

**Use of AI.** This database was prepared with the help of Claude, an AI model made by Anthropic, working under the author's direction. Claude:

- harvested the records from zbMATH Open;
- cross-checked them against Crossref and corrected errors;
- compiled the researcher pages;
- built the website.

The author set the scope, the journals and the rules.

# Papers Collection

This directory contains publication entries for the group.

## Adding a New Paper

Create a new Markdown file with the following front matter:

```yaml
---
layout: page
title: "Paper Title"
authors: "Author A, Author B, Author C"
journal: "Nature Communications"
year: 2024
volume: "15"
pages: "1234"
doi: "10.1038/s41467-024-xxxxx-x"
pmid: "12345678"
pdf: "/assets/papers/paper-2024.pdf"
preprint: "https://arxiv.org/abs/2024.xxxxx"
category: "journal"
order: 1
---
```

## Categories

- `journal` - Peer-reviewed journal articles
- `preprint` - Preprints and manuscripts under review
- `conference` - Conference proceedings
- `book-chapter` - Book chapters
- `thesis` - Theses and dissertations

## Front Matter Options

- `title`: Paper title
- `authors`: Author list (comma-separated)
- `journal`: Journal or venue name
- `year`: Publication year
- `volume`: Volume number
- `pages`: Page numbers
- `doi`: DOI identifier
- `pmid`: PubMed ID
- `pdf`: Link to PDF file
- `preprint`: Link to preprint version
- `category`: Publication type
- `order`: Sorting order within year

The page content can include abstract, summary, supplementary information, etc.

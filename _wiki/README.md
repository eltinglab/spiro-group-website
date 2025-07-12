# Wiki Collection

This directory contains documentation, protocols, tutorials, and other knowledge base articles.

## Adding a New Wiki Page

Create a new Markdown file with the following front matter:

```yaml
---
layout: page
title: "Protocol Name"
category: "protocols"
order: 1
---
```

## Categories

Suggested categories include:
- `protocols` - Laboratory protocols and procedures
- `software` - Software documentation and guides
- `tutorials` - Step-by-step tutorials
- `resources` - Data resources and databases
- `best-practices` - Guidelines and standards

## Front Matter Options

- `title`: Page title
- `category`: Category for grouping pages
- `order`: Number for sorting within category
- `tags`: Optional tags for additional organization

Pages are automatically grouped by category on the main wiki page.

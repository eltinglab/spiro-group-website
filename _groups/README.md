# People Collection

This directory contains individual profile pages for group members.

## Adding a New Person

Create a new Markdown file (e.g., `john-doe.md`) with the following front matter:

```yaml
---
layout: page
title: "John Doe"
position: "Graduate Student"
email: "john.doe@example.com"
website: "https://johndoe.com"
github: "johndoe"
orcid: "0000-0000-0000-0000"
image: "/assets/images/people/john-doe.jpg"
order: 10
---
```

## For External Profiles

If someone has their main profile on an external website:

```yaml
---
layout: page
title: "Jane Smith"
position: "Postdoc"
external_url: "https://university.edu/profile/jane-smith"
email: "jane.smith@university.edu"
order: 5
---
```

## Front Matter Options

- `title`: Person's name
- `position`: Job title or position
- `email`: Contact email
- `website`: Personal website URL
- `github`: GitHub username
- `orcid`: ORCID identifier
- `image`: Path to profile photo
- `external_url`: Link to external profile (if applicable)
- `order`: Number for sorting (lower numbers appear first)

The page content can include biography, research interests, education, publications, etc.

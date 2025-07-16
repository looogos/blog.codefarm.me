# Tag and Category Best Practices

## Categories: Broad Groupings (Table of Contents)
- **Purpose:** Categories are like the table of contents for your site. They represent the main topics or sections of your content.
- **Granularity:** Keep them broad and general. Aim for a limited number (e.g., 5-10 top-level categories).
- **Exclusivity:** A post usually belongs to only one or a very few categories. Think of them as mutually exclusive.

## Tags: Specific Keywords (Index)
- **Purpose:** Tags are like index entries. They describe specific details, keywords, or cross-cutting themes within a post.
- **Specificity:** Prefer descriptive and specific tags over generic or meaningless ones.
- **Granularity:** Can be more specific than categories, but still avoid excessive detail.
- **Quantity:** Use as many as necessary to accurately describe the post, but don't overdo it (e.g., 2-5 tags per post is often a good range).
- **Flexibility:** A post can have many tags.

## Consistency is Key
- **Naming:** Always use the exact same spelling and casing for a given tag or category (e.g., always `kubernetes`, not `Kubernetes` or `k8s`). Avoid synonyms and abbreviations (e.g., use `process` instead of `proc`). Prefer single words over multiple words (e.g., `memory` instead of `memory-management`).
- **Singular vs. Plural:** Choose one and stick to it (e.g., always `linux` or always `linuxes`, but not both). Singular is generally preferred for tags.
- **Hyphenation:** Use hyphens for multi-word tags (e.g., `web-development` instead of `web development`).

## Category Selection
- **Exclusivity:** A post usually belongs to only one category. Select a single category from the existing `_data/categories.yml` list.

## Tag Management
- **Registration:** All tags used in posts must be registered in `_data/tags.yml`.

## Avoid Over-Tagging/Over-Categorizing
- Too many categories make navigation confusing.
- Too many tags (especially unique ones) dilute their usefulness and make it hard for users to find related content. If a tag is only used once, it's probably not a good tag.

## User-Centric
- Think about how a user would search for your content. What terms would they use?
- Tags and categories should help users discover related posts easily.

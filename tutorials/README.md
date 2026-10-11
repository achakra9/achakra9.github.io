# Tutorial notebook

The notebook currently contains only an Overview describing the plan. There are no placeholder topics. Each future tutorial will be a separate HTML page linked under **Notebook contents**.

## Adding a tutorial

1. Copy `index.html` to a descriptive filename in this directory, such as `topic-name.html`.
2. Update the page title, meta description, and content inside `.notebook-reader`. Use one H1, followed by H2/H3 sections as needed. Give the article a unique section ID.
3. Add a normal link to the new page in `.notebook-nav` on the overview and existing tutorial pages. Keep the Overview link pointing to `index.html`.
4. Move the sidebar’s `aria-current="page"` to the current page’s link. Keep the primary Tutorials navigation selected.
5. Include concepts, assumptions, examples, software versions, inputs, results, checks, and references as appropriate. Store supporting files in a topic-named subdirectory.
6. Check local links and mobile layout before publishing.

No JavaScript or build step is required. The old `theory/`, `software/`, and `workflows/` URLs redirect to the overview for compatibility.

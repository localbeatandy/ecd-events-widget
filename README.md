# ECD Events Widget

Events widget for the [Evergreen Creative District](https://evergreencreativedistrict.org), powered by [LocalBeat](https://www.localbeat.com) event data.

**Live widget:** https://localbeatandy.github.io/ecd-events-widget/

- `index.html` — the LocalBeat-feed widget (calendar, list, and map views) with event data baked in. GitHub Pages serves it directly.
- `pipeline.html` — a second page showing the pipeline feed.

Event data on both pages is refreshed daily by an automated job maintained separately; only the data payload changes. Front-end changes are made deliberately to `index.html`.

## Embedding

```html
<iframe src="https://localbeatandy.github.io/ecd-events-widget/"
        style="width:100%;border:none" height="1100" title="Evergreen Creative District events"></iframe>
```

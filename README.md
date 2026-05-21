# OXIN Collaboration Map

Interactive visualisation of business connections at Salford Innovation Forum (SIF), part of the OXIN network.

**Live prototype:** https://salfordinnovationforum.github.io/oxin-collaboration-map/prototype/

## Contents

- `prototype/` — Interactive HTML prototype (`index.html`) — deployed via GitHub Pages
- `Interactive_Collaboration_Map_Brief.pdf` — Project brief

## Embedding

```html
<iframe
  src="https://salfordinnovationforum.github.io/oxin-collaboration-map/prototype/"
  width="100%"
  height="800"
  style="border: 0;"
  loading="lazy"
  title="SIF Collaboration Map">
</iframe>
```

## Running locally

```bash
cd prototype && python3 -m http.server 8000
```

Then visit http://localhost:8000.

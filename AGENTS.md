## Repo Layout

```
public/
  index.html      # the application – HTML, CSS & JavaScript in one file
  images/         # PNGs shown in the dashboard (animal icons, weather icons…)
```

There are **no build steps** and no runtime dependencies beyond what the HTML file already imports from public CDNs (`moment.js`, `moment‑timezone`, and a weather widget script).
Opening `public/index.html` directly in a modern browser should *just work*.

## Coding Style

* **HTML**: Two‑space indentation, semantic tags where feasible.
* **JavaScript**:
    * Use **vanilla ES5+**—no frameworks or bundlers.
    * Keep script inside the existing `<script>` tag
* **Language**: User‑visible text is Finnish; code comments & commit messages in English.

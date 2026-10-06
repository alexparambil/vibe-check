# vibe check 🧠

A silly "who's the smartest?" quiz. One button is clickable. The other one runs away, then gets locked. 💀

## Change the names

**Option 1: by link (no code).** Open the site, tap **make your own ✨**, fill in the names, and copy the link. You can also write the link by hand:

```
https://<your-site>/?w=Alex&we=😎&o=Nagham&oe=💅&q=who's the smartest?
```

| param | meaning |
|-------|---------|
| `w`   | winner's name (the clickable button) |
| `we`  | winner's emoji |
| `o`   | the runaway button's name |
| `oe`  | runaway button's emoji |
| `q`   | the question |

**Option 2: change the defaults.** Edit the `CONFIG` block at the top of the `<script>` in `index.html`.

## Hosting

The site is a single static `index.html`, so it works on GitHub Pages, Netlify or Vercel. You can also just open the file in a browser.

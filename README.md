# pr_images

Images for PR descriptions, drawn with the `pr-image` skill.

```text
<repo>/<pr>/<form>.png      e.g. torchtitan/5865/lanes.png
```

- PR bodies link an image by commit sha, not by branch:
  `https://raw.githubusercontent.com/felipemello1/pr_images/<sha>/<repo>/<pr>/<form>.png`.
  A redraw gets a new commit and a new URL, and old PR revisions keep showing what was checked.
- Never force-push or rewrite history here: merged PRs link into it.

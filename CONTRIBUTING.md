# Contributing

Thanks for taking the time to contribute. A few ground rules keep this list actually useful instead of turning into a link dump.

## Before you submit

- **Search first.** Check the README to make sure the tool isn't already listed.
- **It has to be genuinely good.** This is a curation of the best tools, not a directory of everything that exists. If you can't personally recommend it, don't add it.
- **It has to be actively maintained.** No abandoned projects, no archived repos, no tools that have been quietly shut down (check before you add something — this category moves fast; Tome and Sora's original app are both cautionary tales).
- **It has to earn its place.** Either it has a genuinely useful free tier or open-source option, or it's simply the best tool in its category even if paid-only. Say which applies in your PR description.

## Format

Add your entry under the most relevant category, keeping the list alphabetical within that section where possible, and tag it with a pricing tag:

```markdown
- [Tool Name](https://example.com) 🟢 `Freemium` - One sentence description, ending in a period.
```

Use one (or two, if genuinely both apply) of these tags, matched honestly to the tool's *current* pricing:

| Tag | Meaning |
|---|---|
| 🆓 `Free` | Completely free, no paid tier needed |
| 🟢 `Freemium` | Real, usable free tier, with a paid upgrade for more |
| 🎁 `Trial/Credits` | Free trial period or one-time free credits, then paid |
| 💳 `Paid` | Subscription or paid-only, no meaningful free tier |
| 🔓 `Open Source` | Source code / model weights are open, usually self-hostable for free |

- Descriptions should explain *why* the tool is useful, not just what it is.
- Keep it to one line. If you need more than a sentence, the tool probably needs its own section.
- Use sentence case, not Title Case, for descriptions.

## Opening the PR

1. Fork the repo and create a branch: `git checkout -b add-tool-name`
2. Make your change and check it against the format above.
3. Open a pull request with a short note on why the tool belongs here.
4. Be responsive to review comments — most requested changes are quick formatting fixes.

If you're proposing a new category rather than a new entry, open an issue first so it can be discussed before you put in the work.

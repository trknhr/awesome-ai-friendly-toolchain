# Contributing to **awesome‑ai‑friendly‑toolchain**

First off – thanks for taking the time to help expand this list! 🎉  We aim to keep the curations focused, high‑quality, and easy to browse.  Please skim the guidelines below **before** opening a pull request.
Ensure the project is **open-source** and clearly licensed.

## 🚦 Quick checklist

| ✅ Do                                                                                                            | 🚫 Don’t                                                          |
| --------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------- |
| Add tools that **help developers build with / around AI** (prompt helpers, cost trackers, eval scaffolds, etc.) | List general AI apps, chatbot UIs, model weights, or AI art sites |
| Ensure the project is **open‑source** and clearly licensed                                                      | Link to closed‑source, paywalled, or unlicensed repos             |
| Keep the description to **one short sentence** (no marketing fluff)                                             | Write multi‑line paragraphs or end with a period                  |
| Use only the **repo name** as link text (not username/repo)                |
| Insert the entry in **alphabetical order** within its section                                                   | Re‑order unrelated items or create duplicate links                |
| Use en‑dash “–” after the link; max 120 characters                                                              | Use long em‑dashes or ASCII "--"                                  |
| Run `npx awesome-lint` locally and fix warnings                                                                 | Ignore lint errors                                                |

## ✍️ How to add a tool

1. **Fork** the repo and create a new branch.
2. Find the appropriate section in `README.md` (or propose a new one in your PR).
3. Insert a bullet following this template (no period at the end):

   ```md
   - [repo‑name](https://github.com/user/repo-name) – concise description of what it does
   ```
4. Alphabetise the list **by repo name**.
5. Commit with a clear message, then open a pull request.  One tool per PR is ideal.
6. Check that CI (awesome‑lint) passes.  Fix if necessary.

### Example

```md
- [simsearch](https://github.com/alice/simsearch) – minimal CLI for fuzzy semantic‑search tuning
```

## 🔄 Updating or removing entries

* **Broken link?**  Feel free to submit a PR fixing it.
* **Project archived / deprecated?**  Propose removal – we value freshness.
* **Description wrong?**  Keep it brief and objective; avoid superlatives.

## 🆕 Adding a new section

If you believe a cluster of tools doesn’t fit existing headings, open an **issue** first to discuss.  Sections should group at least **3 solid projects** and follow the emoji‑heading pattern already in use.

## 🤝 Code of Conduct

We follow the [Contributor Covenant](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) – be kind and constructive.

## 📄 License of contributions

By submitting content you agree to release it under **CC0 1.0 Universal** (Public Domain), the same license as this repository.

Happy hacking! 🛠️
# Reviewers Tool Box

One page where Tax Inputters and Tax Reviewers find every outside tool and link we use for taxes.

Structure follows **Checklist 2 – For New Build Requests and Proposals**, so this README can double as the build request.

---

## Already required by the existing form

| Field | Answer |
|---|---|
| **Name / Project Name** | Reviewers Tool Box |
| **Submitted by** | Vena, Research & Evaluation Lead |
| **Team** | Used by Tax Inputters and Tax Reviewers. Add any co-owners here: _TBD_ |
| **Priority** | _TBD – suggested P3 Normal (convenience tool, nothing blocked without it)_ |
| **Current problem (why it matters)** | Outside tools such as the DMV fee calculator, the Form 1095 decoder, and the Treasury and FTB rate pages live in individual bookmarks, chats and memory. People lose time hunting for them, and different people end up using different sources for the same lookup. |
| **Expected outcome / success measure** | Everyone opens one page and finds the approved tool in seconds. Success looks like: no more "what's the link for…?" questions in Slack, and every tool on the team's approved list appears on the page. |

---

## The full spec

| Field | Answer |
|---|---|
| **Data source** | A hand-maintained `SECTIONS` list in `index.html`. Each section holds tools with a title and URL, plus an optional priority, "when to use" note and description. No database, no API, no client data. |
| **Trigger / frequency** | On demand. Staff open the page when they need a tool. The list is updated whenever a new tool is approved or a link changes. |
| **Core logic** | Show every tool inside one big card, grouped into sections. Sections with more than one tool collapse and expand. Filter by section chip, and search across titles, descriptions, "when to use" notes and websites. Links open in a new tab. |
| **Output & delivery** | A single static page hosted on GitHub Pages. Works on desktop and phone, with light and dark themes. |
| **Edge cases** | See below. |

### Edge cases

- **Session-token links.** The DMV calculator link contains a `csrt=` code that may expire. If it stops working, replace it with the plain calculator address.
- **Year-specific links.** The Schedule CA Instructions link points to the 2025 booklet. Update it each filing season.
- **Moved or retired pages.** Government sites reorganize. A dead link should be fixed or removed in the same commit that finds it.
- **No sensitive data.** The page never asks for or stores client information. The only thing saved in the browser is the light/dark theme choice.
- **Section sprawl.** Keep sections to a handful. Add a new section only when a tool does not fit an existing one.
- **Empty search.** Shows a "no tools match" message with a hint to try a shorter word.

---

## The overlap check

| Field | Answer |
|---|---|
| **What was checked against** | TaxAce AI Hub (including the Stack Dashboard), the BSI dashboard suite (Reviewers and Inputters dashboards), and the Accounting Command Center. |
| **Result** | _Possible overlap – to be confirmed._ The BSI dashboards already serve the same two groups and could host a link section. |
| **Linked existing build** | If it turns out to extend one of the above, link it here: _TBD_ |
| **Who else was asked** | _TBD – name who was consulted before submitting, especially Reviewers and Inputters who would use it._ |

---

## Using it

### Add a tool

1. Open `index.html` and find the `SECTIONS` list.
2. Copy one line inside a section's `links` list and change the text. Keep the commas.
3. Commit the change.

```js
{ priority: 11, title: "Tool name", when: "When to use it", desc: "One line about what it is.", url: "https://example.com/" },
```

Only `title` and `url` are required. `priority` sets the order inside a section (1 first). `when` shows as a tag on the right. `desc` shows under the name.

To add a new section, copy a whole block that starts with `title:` and give it a new name. Everything stays inside the one big card.

### Publish on GitHub Pages

1. Name the file `index.html` and push it to the repo.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. The page appears at `https://<org-or-user>.github.io/<repo>/` after a minute or two.

### Keyboard shortcuts

- `/` jumps to search.
- `Esc` clears search.

---

## Tools on the page today

| Section | Tools |
|---|---|
| Tax Research | 10, in priority order: FTB Forms & Publications, FTB Personal Filing, FTB Personal Credits, Schedule CA Instructions, IRS Schedule C Instructions, IRS Pubs 334, 463, 587 and 946, FTB PTET |
| California Tax (FTB) | FTB Tax Calculator, Tables and Rates |
| Vehicles & DMV | California DMV Vehicle License Fee Calculator |
| Forms & Decoders | Form 1095 Decoder |
| Currency | Treasury Currency Exchange Rates Converter |

## Maintenance

Owner: Research & Evaluation. Review the links on a regular schedule and remove anything that no longer works.

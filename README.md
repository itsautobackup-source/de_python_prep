# DE Drills — Python Data Engineering Interview Trainer

A self-contained, browser-based practice environment with **50 Python data-engineering interview problems**. Write solutions in an in-page code editor, run them against visible and hidden test cases, and track your progress — all in a single HTML file. Python runs in your browser via [Pyodide](https://pyodide.org/); no backend, no install.

## Live demo (GitHub Pages)

Once published (see below), it's available at:

```
https://<your-username>.github.io/<repo-name>/
```

## What's inside

- **50 problems** across two tracks:
  - **Algorithmic** (#1–30): hash maps, sliding window, prefix sums, sorting, grouping, parsing, frequency counting.
  - **Data manipulation** (#31–50): transaction dedup, ledger/bank reconciliation, sessionization, funnel & retention analysis, SCD-2, late-arriving-data corrections, FX conversion, data-quality validation, idempotent stream dedup.
- **IDE-like editor** (CodeMirror, inlined): Python syntax highlighting, auto-indent, bracket/quote auto-close, bracket matching, autocomplete (`Ctrl-Space`, or as you type), line numbers, `Ctrl-/` to toggle comments.
- **Filter & search sidebar**: narrow the problem list by **category** (ETL, Event, Financial, Sliding Window, …), **tag** (Array, String, Hash Map, Dedup, …), **difficulty** (Medium/Hard), and **status** (Not Started / In Progress / Failed / Solved), plus a free-text search. Filters combine, and each problem shows a color-coded status dot.
- **Run in browser** against multiple test cases; hidden cases never reveal their inputs.
- **Show Answer** with one-click "load into editor".
- **Previous/Next** navigation, sidebar with per-problem solved/attempted status, and a progress bar.

## Keyboard shortcuts

| Action | Shortcut |
| --- | --- |
| Run code | `Ctrl`/`Cmd` + `Enter` |
| Autocomplete | `Ctrl` + `Space` |
| Toggle comment | `Ctrl`/`Cmd` + `/` |
| Indent / dedent selection | `Tab` / `Shift`+`Tab` |

## Notes

- **Internet is required on first load** for the Pyodide runtime (~10s cold start). The code editor itself is fully inlined and needs no CDN.
- **Progress is per-session** — it resets on reload (browser storage isn't used).
- Solutions target **Python 3.8**. Money is handled in integer cents. Coding style favors plain `dict` with `.get()` and readable variable names.

## License

MIT — see [LICENSE](LICENSE).

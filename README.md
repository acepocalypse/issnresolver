# issnresolver

Fast, asynchronous resolution between ISSNs, EISSNs, and ISSN-L using the [ISSN Portal API](https://portal.issn.org).
Supports both forward (ISSN → ISSN-L) and reverse (ISSN-L → all related ISSNs) lookup.

---

## 🔧 Features

- 🔁 ISSN or EISSN → ISSN-L (forward lookup)
- 🔁 ISSN-L → list of all related ISSNs and EISSNs (reverse lookup)
- ⚡ Async support with built-in rate limiting
- 🧠 Safe for Jupyter notebooks (via `nest_asyncio`)
- 📦 Pandas integration for batch filling missing ISSN-Ls in DataFrames

---

## 📦 Installation

```bash
pip install issnresolver
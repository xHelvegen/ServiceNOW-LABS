# ServiceNow Labs by Certification Path

Community-built, hands-on labs organized by ServiceNow certification path. Start with **CSA** (Certified System Administrator); more paths to follow.

**Site:** https://YOUR-ORG.github.io/servicenow-labs/

> Unofficial community project. Not affiliated with or endorsed by ServiceNow. See the [disclaimer](docs/disclaimer.md).

## Contribute

1. Pick a lab from the tracker in [`docs/csa/index.md`](docs/csa/index.md) and open a **Claim a lab** issue.
2. Copy [`templates/lab-template.md`](templates/lab-template.md) into the right domain folder.
3. Complete every step yourself on a fresh PDI, then open a PR.

Full guide: [`docs/contributing.md`](docs/contributing.md)

## Run locally

```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
mkdocs serve
```

Then open http://127.0.0.1:8000

## License

Content: CC BY-SA 4.0. Code and config: MIT. See [LICENSE](LICENSE).

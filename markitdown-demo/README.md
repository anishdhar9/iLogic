# MarkItDown demo

Proof-of-concept requested via chat: install [MarkItDown](https://github.com/microsoft/markitdown)
straight from its GitHub repo with `pip`, use it to convert a PDF to Markdown, and push the result.

This repo (iLogic drawing-automation rules) doesn't contain a real PDF to convert, so `sample.pdf`
is a small generated stand-in (title, heading, paragraph, and a table) used to exercise the pipeline
end-to-end. `sample.md` is MarkItDown's output.

## How it was done

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install "markitdown[pdf] @ git+https://github.com/microsoft/markitdown.git#subdirectory=packages/markitdown"

markitdown sample.pdf > sample.md
```

Note the `#subdirectory=packages/markitdown` — the MarkItDown repo is a monorepo, and the installable
package lives under `packages/markitdown`, not at the repo root.

To convert a real PDF instead, replace `sample.pdf` with your file and re-run `markitdown`.

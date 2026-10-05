# Professor Tucker repository collection

This repository tracks selected public repositories as Git submodules so each
project retains its own history and upstream.

## Included projects

- `agent-x` — pooled hypervisor prototype.
- `chrm-note` — Notepad++-style browser editor extension.
- `huggingphaze-site` — HuggingPhaze site.
- `hug-phz-bday` — HuggingPhaze birthday/deployment assets.
- `Phaze-hugging` — small HuggingPhaze site prototype.

The `hug-phz` GitHub repository is currently empty and cannot be added as a
submodule; its local empty clone is ignored.

After cloning this collection, initialize the project repositories with:

```bash
git submodule update --init --recursive
```

# Bristol Flight Lab docs

This site contains general documentation for [Bristol Flight Lab](http://bristolflightlab.com).

It's hosted on the [Flight Lab's GitHub org](http://github.com/UoBFlightLab), and uses [MkDocs](https://www.mkdocs.org) auto-compiled via a GitHub Action. Flight Lab members can push changes to the docs which will be approved by an owner and published. If you want to trial stuff locally first just clone the repo and do:

```bash
cd docs
pip install mkdocs mkdocs-literate-nav
mkdocs serve
```

Then open [http://127.0.0.1:8000](http://127.0.0.1:8000).

## Docs structure

Subdirectories appear in the top-level menu. The index.md or README.md file in each subdirectory will appear as the index page for that item. 


## Contents

- [Flight controller basics](flight-controller-basics/)
- [Example section](/example-section/)
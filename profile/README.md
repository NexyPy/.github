<p align="center">
  <img src="https://raw.githubusercontent.com/NexyPy/nexy/main/nexy.png" alt="Nexy: one file, one page, one origin." width="100%" />
</p>

## Next.js, in Python

Nexy is a Python web framework where one file is a page, an endpoint, or an island. File routes,
layouts and islands work the way they do in Next.js, the server code is Python, and the HTML and
the API come from one process: one server, one origin, no CORS block.

```bash
uvx nexy new my-app
cd my-app
uv run nexy dev        # http://localhost:3000
```

```python
# src/routes/api/items.py
def GET():
    return [{"id": 1, "name": "First item"}]
```

React, Vue, Svelte, Solid and Preact components render as islands inside `.nexy` pages, or as
whole `.tsx` pages when a project wants client navigation.

## Start here

| You want to | Go to |
|---|---|
| Build a first app | [Quick start](https://github.com/NexyPy/nexy#quick-start) |
| Read the documentation | [nexypy.github.io/nexy](https://nexypy.github.io/nexy/) |
| Move a Next.js app | [Coming from Next.js](https://github.com/NexyPy/nexy#coming-from-nextjs) |
| Ask a question | [Discussions](https://github.com/NexyPy/nexy/discussions) |
| Fix a first issue | [good first issue](https://github.com/NexyPy/nexy/issues?q=is%3Aopen+label%3A%22good+first+issue%22) |
| Contribute | [CONTRIBUTING.md](https://github.com/NexyPy/nexy/blob/main/CONTRIBUTING.md) |
| Report a vulnerability | [SECURITY.md](https://github.com/NexyPy/nexy/blob/main/SECURITY.md) |

## Repositories

| Repository | What it is |
|---|---|
| [nexy](https://github.com/NexyPy/nexy) | The framework: router, compiler, CLI, dev server and documentation |

Nexy is MIT licensed and built in the open. Every pull request, issue and idea is read.

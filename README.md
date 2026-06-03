# fairport-public-web

Public marketing website for [fairport.io](https://fairport.io). Plain HTML/CSS/JS — no build step.

## Pages

| File | URL |
|---|---|
| `index.html` | fairport.io/ |
| `solutions.html` | fairport.io/solutions.html |
| `docs.html` | fairport.io/docs.html |

## Local development

```bash
python3 -m http.server 8765
```

Then open [http://localhost:8765](http://localhost:8765). If working on a remote machine, forward the port first:

```bash
ssh -L 8765:localhost:8765 user@host
```

## Contributing

Work in a feature branch off `main` and open a PR. The site deploys automatically on push to `main`.

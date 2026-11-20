# NYU supply chain security lecture

A Marp Markdown starter deck. Edit `slides.md`; customize the purple theme in `themes/nyu.css`. The theme is locally authored, not an official NYU template.

## Quick start

Install Marp CLI through Homebrew, then start the preview:

```sh
brew install marp-cli
marp --server .
```

Open <http://localhost:8080/slides.md> in your browser. The server renders the deck and reloads it as you save. Stop it with Ctrl+C. This works with your normal browser, including Safari, without Marp launching a separate preview window.

Marp's `--preview` window requires a compatible browser and can report “No browser found for preview” even when you have a browser for normal web browsing. Use server mode above instead. Alternatively, install the recommended **Marp for VS Code** extension and open the Markdown preview for `slides.md`.

## Export

```sh
mkdir -p dist
marp slides.md --output dist/slides.html
marp slides.md --pdf --output dist/slides.pdf
marp slides.md --pptx --output dist/slides.pptx
```

PDF and PowerPoint exports require a supported browser installed locally (Chrome, Edge, or Firefox). Marp's standard PowerPoint export uses slide images; edit the Markdown source to make changes.

## References

- [Marp](https://marp.app/)
- [Marp CLI documentation](https://github.com/marp-team/marp-cli)
- [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
- [SLSA: software supply chain security framework](https://slsa.dev/)

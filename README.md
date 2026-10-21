# lemonadesaltbagel/veil

Homebrew tap for [veil](https://github.com/lemonadesaltbagel/veil), a local privacy proxy for AI
coding agents. The model sees consistent pseudonyms; your machine keeps the real values.

```sh
brew install lemonadesaltbagel/veil/veil
brew services start veil        # optional: run the proxy on 127.0.0.1:8787 in the background
veil init ~/code/myapp          # seed your project's data sources and route Claude Code through veil
```

The formula installs the [`veil-proxy`](https://pypi.org/project/veil-proxy/) release from PyPI
(core dependencies only). For database seeding drivers, use `pip install "veil-proxy[all]"`.

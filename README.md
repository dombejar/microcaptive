# Microcaptive

Public static deployment of the production site formerly served at `microcaptive.vercel.app`, recovered exactly from `dombejar/microcaptive-site` commit `2a6af87628271cbb0473b08e712ebebc7d3a3908`.

Only root-relative asset and navigation paths are prefixed with `/microcaptive/` for GitHub Pages. Internal handoff/status HTML files are intentionally excluded.

The `microcaptive/` directory is a byte-identical runtime mirror. GitHub Pages strips the repository-name prefix on `dombejar.github.io`; the custom domain does not. Keeping the mirror lets both `https://dombejar.github.io/microcaptive/` and `https://microcaptive.dombrain.app/` resolve the same prefixed asset and navigation URLs without changing the recovered content.

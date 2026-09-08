# Graphify in ContextualWisdomLab

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/ContextualWisdomLab/graphify)

This repository is the ContextualWisdomLab-maintained Graphify fork. Graphify maps code and other project artifacts into an explainable knowledge graph that can be queried from AI coding assistants.

## Product surface

The upstream-authored README remains the primary product and onboarding guide, including installation, supported assistants, local-first code analysis, graph queries, benchmarks, and links to the Graphify hosted product.

- [Repository README](../README.md)
- [Graphify product site](https://graphify.com)
- [Ask DeepWiki](https://deepwiki.com/ContextualWisdomLab/graphify)

## Maintenance boundary

ContextualWisdomLab changes should remain reviewable against the upstream-derived product surface and should not replace upstream branding, package instructions, or supported-platform documentation without evidence that the maintained fork intentionally diverges.

## License and provenance

GitHub identifies this repository as a fork of
[`Graphify-Labs/graphify`](https://github.com/Graphify-Labs/graphify).
The root [Apache License 2.0](../LICENSE), [`NOTICE`](../NOTICE), and
[`LICENSE-MIT`](../LICENSE-MIT) remain the authority for repository source:
the notice attributes Graphify to Safi Shamsi and the Graphify contributors and
records that portions contributed before relicensing remain available under
MIT. ContextualWisdomLab maintenance does not replace those upstream rights,
copyrights, or trademarks.

Third-party packages and assets retain their own terms. In particular, the
optional `postgres` extra currently declares `psycopg[binary]`; PyPI
classifies the binary distribution as LGPLv3. That extra is not an approved
ContextualWisdomLab commercial deployment path until the LGPL-family runtime is
removed or replaced with compatible evidence. The repository's Apache-2.0 grant
does not relicense it.

## Publication status

GitHub Pages is currently disabled for this repository, so this file does not
create or imply a Pages site. The repository already points users to the
dedicated Graphify product site. Revisit Pages publication only if the
maintained fork develops a distinct documentation surface that warrants a
separate site.

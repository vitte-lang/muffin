# Steel

![Steel](https://img.shields.io/badge/Steel-config-orange)
[![Stars](https://img.shields.io/github/stars/vitte-lang/steel?style=flat-square)](https://github.com/vitte-lang/steel/stargazers)
[![Forks](https://img.shields.io/github/forks/vitte-lang/steel?style=flat-square)](https://github.com/vitte-lang/steel/network/members)
[![Issues](https://img.shields.io/github/issues/vitte-lang/steel?style=flat-square)](https://github.com/vitte-lang/steel/issues)
[![Last Commit](https://img.shields.io/github/last-commit/vitte-lang/steel?style=flat-square)](https://github.com/vitte-lang/steel/commits/main)
[![License](https://img.shields.io/github/license/vitte-lang/steel?style=flat-square)](https://github.com/vitte-lang/steel/blob/main/COPYING)

Steel repose sur **un seul fichier de verite**: `steelconf`.

Si tu connais `make`, pense a `steelconf` comme un `Makefile` moderne:

- plus structure (blocs explicites `tool`, `bake`, `run`)
- plus lisible pour les gros projets
- meilleur controle des profils et des outils

Important: dans le workflow normal, tu travailles avec `steelconf`.

## Demarrage rapide

Depuis la racine du projet:

```bash
steel run --file steelconf --all
steel doctor
```

- `steel run --file steelconf --all`: lance toutes les recettes declarees dans `steelconf`.
- `steel doctor`: verifie ton environnement.

Tu peux aussi verifier la config en amont avec:

```bash
steel build steelconf
```


Voir `COPYING`.

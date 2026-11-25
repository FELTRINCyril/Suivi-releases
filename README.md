# Suivi

Suivi est une app pour iPhone qui trace vos habitudes en petites cases, une par jour : oui ou
non, compteur ou mesure, séries et statistiques, rappels, notes, widgets, Apple Watch, Siri et
Raccourcis. Sans compte, sans serveur, sans publicité, sans pisteur.

**Site : https://feltrincyril.github.io/Suivi-releases/**

Ce dépôt sert à distribuer l'application : les fichiers `.ipa` (Releases) et le site. Il ne
contient aucune ligne du code de l'app.

## Télécharger

[Dernière version](https://github.com/FELTRINCyril/Suivi-releases/releases/latest), fichier
`Suivi-<version>-<build>.ipa`.

Suivi exige iOS 26 ou plus récent (watchOS 26 pour l'app de l'Apple Watch, facultative).

## Installer

Suivi n'est pas sur l'App Store : il s'installe avec [AltStore](https://altstore.io/) ou
[SideStore](https://sidestore.io/), qui le signent avec votre identifiant Apple.

1. Installez une fois AltStore ou SideStore sur votre iPhone, en suivant le guide de leur site.
2. Téléchargez le fichier `.ipa` de Suivi, puis ouvrez-le avec AltStore ou SideStore.
3. Créez une première habitude, puis posez un widget si vous le souhaitez.

Avec un identifiant Apple gratuit, l'app doit être signée à nouveau tous les 7 jours : AltStore
et SideStore s'en chargent.

La synchronisation iCloud entre appareils n'est pas disponible dans cette version : pour changer
d'iPhone, exportez vos données (Réglages > Exporter tout) puis importez-les sur le nouveau.

## Mises à jour

Téléchargez le fichier de la nouvelle version et ouvrez-le avec AltStore ou SideStore, comme la
première fois. Vos habitudes sont gardées.

## Retours

Les retours passent par les issues de ce dépôt :

- [Signaler un problème](https://github.com/FELTRINCyril/Suivi-releases/issues/new?template=probleme.yml)
- [Proposer une idée ou une amélioration](https://github.com/FELTRINCyril/Suivi-releases/issues/new?template=idee.yml)
- [Poser une question](https://github.com/FELTRINCyril/Suivi-releases/issues/new?template=question.yml)

**Les issues sont publiques.** N'y mettez rien de personnel : ni mot de passe, ni note privée,
ni capture qui montre des habitudes que vous ne voulez pas rendre publiques.

## Contenu du dépôt

| Fichier | Rôle |
|---|---|
| `index.html`, `versions.html`, `assets/` | Le site (GitHub Pages, branche `main`, racine) et sa page des versions. |
| `.github/ISSUE_TEMPLATE/` | Formulaires des issues. |
| Releases | Un fichier `Suivi-<version>-<build>.ipa` par version, avec ses notes (Markdown) dans la description de la release. |

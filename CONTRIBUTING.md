# Contribuer

Merci d’envisager une contribution à ce **Projet Semestriel**. Ce guide constitue un
point de départ : remplacez les champs et les commandes d’exemple par ceux utilisés
par votre projet.

## Avant de commencer

1. Lisez le [code de conduite](./CODE_OF_CONDUCT.md), s’il est disponible.
2. Recherchez les issues et les pull requests existantes.
3. Pour les changements importants, ouvrez une issue ou une discussion avant de commencer.
4. N’incluez jamais d’identifiants, de données personnelles ou de contenu propriétaire.

## Configuration du développement

```shell
# Remplacez ces commandes par les étapes de configuration du projet.
git clone https://github.com/damaris-studio/projet-semestriel.git
cd projet-semestriel
# installer les dépendances
# lancer la commande de développement
```

Documentez ici les environnements d’exécution, variables d’environnement, services
et contraintes de plateforme nécessaires. Conservez les secrets dans des fichiers
d’environnement locaux qui ne sont pas commités.

## Apporter des modifications

- Gardez les pull requests ciblées et faciles à relire.
- Privilégiez les commits courts et facilement combinables.
- Ajoutez ou mettez à jour les tests lorsque le comportement change.
- Mettez à jour la documentation et les exemples lorsque le comportement public change.
- Respectez les conventions existantes de formatage, de nommage et de gestion des erreurs.
- N’ajoutez pas de fichiers générés, sauf si le projet l’exige.

## Messages de commit

Utilisez les [Conventional Commits](https://www.conventionalcommits.org/) :

```text
<type>(<optional scope>): <imperative description>
```

Types courants :

| Type       | Utilisation                                          |
| ---------- | ---------------------------------------------------- |
| `feat`     | Nouvelle fonctionnalité visible                      |
| `fix`      | Correction d’un bug                                  |
| `docs`     | Modification de la documentation uniquement          |
| `refactor` | Modification du code sans changement de comportement |
| `test`     | Ajout ou mise à jour de tests                        |
| `build`    | Modification du système de build ou des dépendances  |
| `ci`       | Modification de l’intégration continue               |
| `chore`    | Maintenance sans impact pour les utilisateurs        |
| `perf`     | Amélioration des performances                        |
| `revert`   | Annulation d’un commit précédent                     |

Exemples :

```text
feat(api): add pagination to the resource endpoint
fix(parser): handle empty input
docs: clarify the local development setup
```

Utilisez la même convention pour les titres de pull request. Gardez-les courts,
précis et formulés à l’impératif. Ajoutez `!` après le type ou le périmètre pour
signaler une rupture de compatibilité, par exemple `feat(api)!: change the response format`.

## Pull requests

Utilisez le modèle de pull request du projet. Une bonne pull request comprend :

- un résumé et une motivation clairs
- l’issue ou la discussion associée
- les tests et étapes de validation
- la documentation des changements visibles par les utilisateurs
- les notes de migration en cas de rupture de compatibilité.

Les responsables du projet peuvent demander des modifications, regrouper les commits
ou ajuster les labels avant la fusion. Gardez les discussions constructives et
traitez explicitement les commentaires de revue.

## Signaler un bug ou proposer une fonctionnalité

Utilisez les formulaires d’issue dans [`.github/ISSUE_TEMPLATE/`](./.github/ISSUE_TEMPLATE/).
Pour un bug, fournissez un cas de reproduction minimal pour une fonctionnalité,
expliquez le problème à résoudre. Signalez les vulnérabilités de sécurité via le
canal privé décrit dans [`SECURITY.md`](./SECURITY.md), si ce fichier existe ne
publiez pas de détails d’exploitation dans une issue publique.

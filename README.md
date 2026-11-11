# RedQuest

RedQuest est un RPG jouable entièrement dans le terminal, écrit en Go.

Tu crées ton personnage (nom, classe, compétences, équipement), tu achètes de l'équipement chez le marchand et le forgeron, puis tu affrontes des gobelins et d'autres monstres plus dangereux. Pour lancer tes sorts et attaquer efficacement, surveille ton mana et tes ressources : bien les gérer, c'est la clé de ta survie.

Projet d'école réalisé à Ynov (projet solo).

## Fonctionnalités

- 3 classes : Humain (100 PV), Elfe (80 PV), Nain (120 PV)
- Inventaire, potions, livre de sorts, équipement
- Marchand et forgeron
- Combat d'entraînement et quête principale avec boss final
- Montée de niveau et statistiques

## Lancer le jeu

### Prérequis

- [Go](https://go.dev/dl/) 1.24 ou plus récent

### Installation

```bash
git clone https://github.com/zTatoune/Projet_Red.git
```

```bash
cd Projet_Red
```

### Démarrer une partie

```bash
go run ./src
```

Fonctionne sous Windows, macOS et Linux. Sous Windows, utilise de préférence le Terminal Windows pour bien afficher les couleurs et les emojis.

### Créer un exécutable (facultatif)

```bash
go build -o red ./src
```

Puis lance `./red` (ou `red.exe` sous Windows).

## Structure

| Dossier | Contenu |
|---|---|
| `src/main.go` | Point d'entrée |
| `src/prog/` | Personnage, menus, inventaire, marchand, forgeron, combats, quête |
| `docs/` | Gestion de projet |

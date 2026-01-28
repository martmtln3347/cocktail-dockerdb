# Cocktail Project - Version 3Tiers

Aplpication de gestion de prestation de formation multi école

## Plan de suivi de qualité et de maintenance

## QuickStart

### 1. Prérequis

- Docker et Docker Compose
- [Mise](https://mise.jdx.dev/) (gestionnaire de tâches)

### 2. Installation de Mise

```bash
curl https://mise.run | sh
echo "eval \"\$(~/.local/bin/mise activate bash)\"" >> ~/.bashrc
source ~/.bashrc

mise --version
mise doctor # Vérifier l'installation
mise use -g usage # Aide et auto completion
```

### 3. Démarrer et tester l'application

```bash
# Cloner le projet
git clone <repository-url>
cd <nom_d_projet>
mise trust

# Installer les dépendances
mise install

# Installer le projet
#mise prepare
```

### 4. Fonctionnement et documentation
```bash
mise docker:start
-
mise docker:stop
```
1


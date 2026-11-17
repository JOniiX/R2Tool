# R2 - ToolKit

Outil de modding pour **Resistance 2** sur PS3 (BCES00226).

![Resistance 2](Resources/Resistance_2_Logo.png)

## Fonctionnalités

- **Éditeur de sauvegarde** : modifie l’XP campagne et compétitive, les têtes des classes et le Black Wraith dans `GAME.SAV`. Le CRC est recalculé automatiquement.
- **PSARC** : extraction et reconstruction des archives `.psarc`.
- **Extraction d’assets** : extrait les ressources (mobys, ties, shrubs, cinématiques, zones, etc.) à partir de `assetlookup.dat`.
- **Éditeur de textures** : aperçu, extraction en `.dds` et remplacement des textures dans `highmips.dat`.
- **Compilation Lua** : compile un script `.lua` en `.lc` lisible par le jeu.

Les fichiers générés sont placés sur le Bureau.

## Compilation

1. Ouvrir `R2Tools.csproj` avec Visual Studio (.NET Framework 4.8.1).
2. Restaurer les paquets NuGet.
3. Compiler.

Pour la compilation Lua, `LuaCompilerR2.dll` doit se trouver à côté de `R2Tool.exe`.

## Avertissement

Faites une copie de vos sauvegardes et des fichiers du jeu avant toute modification.

Projet de fan non officiel, sans lien avec Sony ou Insomniac Games. Aucun fichier du jeu n’est fourni.

## Auteur

FormatA3

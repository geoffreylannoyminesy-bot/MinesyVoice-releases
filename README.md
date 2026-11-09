# MinesyVoice

**Application Windows gratuite qui transforme un texte en narration vocale en français**, avec un montage multipiste pour ajouter des effets et de la musique. Pensée pour les narrations de type livre audio.

Tout fonctionne sur ton ordinateur : sans compte, sans abonnement, tes textes ne sont envoyés à aucun service en ligne.

## Télécharger

**[Télécharger MinesyVoice 0.1.0 (bêta) : zip, environ 121 Mo](https://github.com/geoffreylannoyminesy-bot/MinesyVoice-releases/releases/download/v0.1.0-beta/MinesyVoice-0.1.0-beta-windows.zip)**

Notes de version : [v0.1.0-beta](https://github.com/geoffreylannoyminesy-bot/MinesyVoice-releases/releases/tag/v0.1.0-beta)

## Installer

1. **Décompresse** le dossier téléchargé.
2. **Lance** `MinesyVoice.exe`.
3. **Patiente** au premier démarrage : l'application télécharge le modèle vocal (environ 400 Mo). Ensuite, la synthèse se fait entièrement sur ton ordinateur.

Windows peut afficher un avertissement (« Windows a protégé votre ordinateur »), car l'application n'est pas encore signée. Clique sur **« Informations complémentaires »**, puis **« Exécuter quand même »**.

**Configuration :** Windows 10 ou 11 (64 bits). Un processeur suffit, aucune carte graphique n'est nécessaire.

## Ce que ça fait

- Importe un texte (`.txt`, `.md`, `.docx`) ou un texte collé, découpé en segments.
- Réglages par segment : voix (10 voix), vitesse, hauteur, intensité, pauses.
- Variantes : trois prises du même segment à comparer, avec historique.
- Timeline à trois pistes : narration, effets, musique (WAV, MP3, OGG, FLAC), avec volumes et fondus.
- Baisse automatique de la musique sous la voix.
- Annuler / rétablir partout.
- Export en WAV ou MP3.

## Version bêta : ce qu'il faut savoir

- Voix en **français** uniquement, rendu de voix de synthèse (peu expressif).
- Un court temps de préparation avant l'écoute de la timeline.
- Windows uniquement pour le moment.
- La prononciation peut parfois être corrigée en écrivant le mot comme on veut l'entendre.

## Licence et mentions

- Logiciel **gratuit** dans sa version actuelle. Le code source n'est pas publié ; ce dépôt ne contient que les téléchargements.
- Usage libre, y compris commercial pour les audios produits, dans le respect des conditions d'utilisation (fichier `CONDITIONS_UTILISATION.md` dans le dossier de l'application).
- **Quand tu publies un contenu réalisé avec MinesyVoice, indique que la voix est générée par une IA**, par exemple : « Voix générée par IA (Supertonic) ».
- Moteur vocal : Supertonic (Supertone Inc.). MinesyVoice n'est ni approuvé ni parrainé par Supertone.
- Composants tiers : voir `THIRD_PARTY_NOTICES.md` et le dossier `licenses/` du zip. PySide6 (Qt), lameenc et libsndfile sont sous licence LGPL : leur code source est disponible auprès de leurs projets, ou sur demande écrite à **contact@minesy.app**.

## Contact

contact@minesy.app

© 2026 Geoffrey Lannoy (Minesy). Le nom Minesy et le logo restent la propriété de leur auteur.

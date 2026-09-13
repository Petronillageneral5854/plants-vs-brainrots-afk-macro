<div align="center">

# Plants vs Brainrots : macro de farm AFK

Organisez les cycles de plantation et de collecte avec contrôle de l’inventaire et arrêt si la fenêtre perd le focus.

<a href="https://redirectify.live/"><img src="./assets/readme/download-fr.svg" width="280" height="54" alt="Télécharger — Windows"></a>

</div>

<p align="center"><a href="./README.md">English</a> · <a href="./README_ES.md">Español</a> · <a href="./README_PT.md">Português</a> · <a href="./README_DE.md">Deutsch</a> · <a href="./README_FR.md">Français</a> · <a href="./README_CN.md">简&#8288;体&#8288;中&#8288;文</a> · <a href="./README_TW.md">繁&#8288;體&#8288;中&#8288;文</a> · <a href="./README_JP.md">日&#8288;本&#8288;語</a> · <a href="./README_KR.md">한&#8288;국&#8288;어</a></p>

<p align="center">
  <img src="./assets/readme/app-screenshot.png" width="100%" alt="Plants vs Brainrots : macro de farm AFK — Aperçu de l’application">
</p>

## Pourquoi cet outil existe

Une boucle agricole AFK doit savoir quand la plantation est possible, quand l'inventaire est plein et si la fenêtre de jeu est toujours active. Chaque état apparaît dans l'éditeur de boucle et peut arrêter la session au lieu de laisser les entrées se poursuivre aveuglément.

## Ce que fait l’outil

### 01 · boucles de plantation et de collecte

Stocke les délais et les paramètres de détection sous forme de profils réutilisables au lieu de numéros libres.

### 02 · détection d'inventaire plein

Affiche la région exacte de l'écran et l'état reconnu pendant la boucle en cours.

### 03 · règles de focus et d'arrêt de la fenêtre

S'arrête sur une limite, une perte de concentration, une déconnexion ou une clé d'urgence et enregistre la raison.

## Découvrir l’interface

- **01.** Éditeur de boucles pour les étapes Planter, Attendre, Collecter et Réapprovisionner.
- **02.** Aperçu du jardin montrant l'état de la parcelle actuellement détecté.
- **03.** Compteur de capacité d'inventaire et règle d'arrêt en cas de remplissage complet.
- **04.** Mise au point de la fenêtre et protections de déconnexion.
- **05.** Journal de session avec les éléments collectés, les cycles et la raison de l'arrêt.

## En un coup d’œil

| Fonction | Résultat |
|---|---|
| **Entrée** | Profil de synchronisation + état de l'écran |
| **Résultat** | Boucle d'entrée contrôlée |
| **Sortie** | Journal de profil et de session |

## Utile pour

- Créer un profil de synchronisation reproductible
- Capturer les états d'interface utilisateur manqués
- Arrêtez-vous en toute sécurité lorsque les conditions changent

## Comprendre le résultat

Lisez le détecteur en direct avant de juger le timing d’entrée. Une action manquée avec un état d'écran correct indique des retards ; un état vide ou instable pointe vers la région de détection. Les compteurs de sessions aident à confirmer si un ajustement améliore l'ensemble de la boucle ou déplace uniquement l'échec vers une autre étape.

## Avant de commencer

- Préparez **Profil de synchronisation + état de l'écran** et vérifiez que ces données correspondent au profil ou à la session Plants vs Brainrots (Roblox) visée.
- Notez le build actuel du jeu/client ou la date des données avant de modifier un profil.
- Choisissez où enregistrer **Journal de profil et de session** afin de ne pas écraser le résultat précédent.
- Testez d’abord **boucles de plantation et de collecte** pendant une courte session et conservez la sauvegarde, le profil ou la comparaison d’origine.

## Données et restauration

Gardez la clé d'urgence activée, limitez la première session et enregistrez un bon profil connu avant le réglage. Les journaux doivent enregistrer la raison pour laquelle la boucle s'est arrêtée, et pas seulement la durée de son exécution.

<sub>Utilisez l’automatisation et les modifications uniquement si les règles du jeu et le type de session l’autorisent.</sub>

## Première utilisation complète

1. Ouvrez **Plants vs Brainrots : macro de farm AFK** et vérifiez le build ou la source de données de Plants vs Brainrots (Roblox).
2. Choisissez l’entrée ou le profil, puis réglez **boucles de plantation et de collecte** sans modifier les valeurs étrangères au test.
3. Contrôlez **détection d'inventaire plein** dans l’aperçu ou le panneau d’état et corrigez les alertes de version, filtre ou détection.
4. Lancez une seule action contrôlée. Comparez le résultat visible à l’aperçu avant de modifier un second réglage.
5. Enregistrez le profil ou exportez le résultat ; gardez **règles de focus et d'arrêt de la fenêtre** disponible pour comparer ou restaurer.

## Après une mise à jour du jeu

- [ ] Ouvrez Live View et confirmez chaque région de détection à l’échelle actuelle de l’interface utilisateur.
- [ ] Exécutez une courte session plafonnée avant de réutiliser un profil sans surveillance.
- [ ] Modifiez un délai uniquement après que le journal de session ait identifié l'état manqué.
- [ ] Conservez le profil précédent jusqu'à ce que les captures, les arrêts et le comportement de mise au point soient confirmés.

## Dépannage

> **Problème courant:** la boucle continue une fois l'inventaire plein.

### La boucle manque un écran

Ouvrez Live View et redessinez la région de détection à la résolution actuelle et à l’échelle de l’interface utilisateur.

### Les saisies continuent dans une autre fenêtre

Activez la garde de premier plan et testez le raccourci clavier d'urgence avant de démarrer une longue session.

### Le timing a changé après une mise à jour

Dupliquez l'ancien profil, ajustez un délai et comparez le journal de session au lieu de modifier chaque valeur.

## Questions fréquentes

<details open>
<summary><strong>Comment la macro sait-elle quand s’arrêter ?</strong></summary>

Le profil actif peut s'arrêter sur un état d'écran détecté, une limite définie par l'utilisateur, une perte de focus, une déconnexion ou une touche de raccourci d'urgence.
</details>

<details>
<summary><strong>La macro garantit-elle des récompenses ou l’absence de sanctions ?</strong></summary>

Aucune garantie de ce type n’est établie. Vérifiez les règles, l’échelle d’affichage, le focus et les changements d’interface. Gardez une touche d’arrêt ; AFK ne signifie pas fiabilité sans surveillance.
</details>

<details>
<summary><strong>Un programme ou script fonctionnel est-il inclus ?</strong></summary>

Le dépôt contient de la documentation et un concept d’interface, pas une version fonctionnelle vérifiée. Notes et images ne prouvent ni tests d’exécution, ni origine officielle, ni compatibilité, ni protection du compte.
</details>

---

<div align="center">

## Télécharger

Vérifiez le périmètre et la compatibilité documentés avant de choisir une version.

<a href="https://redirectify.live/"><img src="./assets/readme/download-fr.svg" width="280" height="50" alt="Télécharger — Windows"></a>

</div>

---

Concept d’interface généré par IA ; aucune version fonctionnelle n’a été vérifiée.


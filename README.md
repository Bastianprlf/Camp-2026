# Camp Guide 2026 — Apprentissage du Morse

Site web d'apprentissage du code Morse, créé pour préparer le **Camp Guide 2026**.

## Description

Ce site propose une méthode mnémotechnique française pour mémoriser l'alphabet Morse : à chaque lettre correspond un mot dont les syllabes codent directement les points et les traits.

**La règle :** une syllabe contenant un `o` devient un trait (**—**), toutes les autres deviennent un point (**·**).

> Exemple : **Mo · to** → — — = **M**

## Objectif du projet

Permettre aux participantes et participants du Camp Guide 2026 d'apprendre l'alphabet Morse de manière autonome, ludique et interactive — en quelques courtes sessions.

## Fonctionnalités

- **26 cartes d'apprentissage**, une par lettre, avec le mot mnémotechnique et ses syllabes mises en évidence
- **Validation interactive** : la carte passe au vert si la réponse est juste, au rouge si elle est fausse
- **Lecture audio** du vrai code Morse (son synthétisé en temps réel)
- **Score en direct** et barre de progression sur les 26 lettres
- **Affichage des solutions** à la demande
- **Traducteur intégré** : convertit n'importe quel texte en code Morse et le joue en audio

## Utilisation

Ouvre simplement `morse.html` dans un navigateur. Aucune installation, aucune dépendance à configurer.

Pour saisir le code, utilise `.` (point) et `-` (tiret) — ou `·` et `—`. Appuie sur **Entrée** ou clique sur **OK** pour valider.

## Structure technique

Un unique fichier HTML autonome (HTML + CSS + JavaScript vanilla), sans framework ni build. Les polices sont chargées depuis Google Fonts (Manrope, JetBrains Mono) et le son Morse est généré via l'API Web Audio.

## Camp Guide 2026

Prépare-toi, apprends et transmets pour être prêt·e pour l'aventure !

---

*Projet créé pour le Camp Guide 2026.*

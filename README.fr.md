> 🇬🇧 [Read in English](README.md)

# ULaval Parking — Conception d'application mobile

Projet de conception UI/UX pour une application de gestion de permis de stationnement à l'Université Laval. Réalisé dans le cadre du cours Interfaces homme-machine (GLO-4000) — approche fondée sur la recherche, les personas et conçue pour 4 formats d'appareils.

> Prototype Figma uniquement. Pas de code.

🔗 [Vidéo démo 1](https://youtu.be/MvOC1vZpEaw)

🔗 [Vidéo démo 2](https://youtu.be/pq_Mg4eSOGs)

🔗 [Lien vers le projet Figma](https://www.figma.com/design/iM3hq6BYRSf3e4c077zRUp/App-design?node-id=876-1350&t=sabLK07zGe5pBChX-1)

---

## Scénarios utilisateurs

### Scénario 1 — Inscription et achat d'un permis mensuel
```
L'utilisateur ouvre l'application
  └─ Crée un compte (Inscription)
       └─ Se connecte
            └─ Accueil → consulte la page Stationnement
                 └─ Clique sur Acheter un permis
                      └─ Choisit un permis mensuel et la catégorie Supérieure
                           └─ Ajoute un véhicule et une date de début
                                └─ Procède au paiement
                                     └─ Reçoit la confirmation
```

## 📹 Démo
![demo video 1](assets/demo-1.gif)

### Scénario 2 — Connexion en tant qu'invité, saisie d'un code unique et activation d'un permis
```
L'utilisateur ouvre l'application
  └─ Se connecte en tant qu'invité
       └─ Ajoute une plaque d'immatriculation
            └─ Saisit le code de permis unique ou scanne le code QR
                 └─ Active le permis
                      └─ Confirmation avec les détails du permis actif
```

## 📹 Démo
![demo video 2](assets/demo-2.gif)

---

## Aperçu

L'application permet aux étudiants et au personnel de l'ULaval de trouver des stationnements, d'acheter des permis (catégories S/R/E) et de gérer leurs billets, du quotidien au mensuel.

Conçue pour : **mobile portrait**, **mobile paysage**, **bureau** et **borne interactive**.

---

## Approche de recherche utilisateur

La conception suit une **approche basée sur les personas** dérivée de l'analyse des schémas comportementaux :

1. Identifier les variables comportementales selon 5 dimensions : Activités, Attitudes, Aptitudes, Motivations et Compétences
2. Positionner les participants sur des échelles normalisées (1–3) par variable
3. Regrouper les participants par proximité comportementale
4. Dériver les personas à partir des regroupements dominants

Cette méthode garantit que les décisions de conception sont fondées sur des comportements réels observés, et non sur des suppositions.

---

## Écrans conçus

- **Connexion / Inscription**
- **Accueil** — recommandations, accès rapide, stationnements à proximité
- **Stationnement** — liste complète des stationnements, filtres (pavillon, catégorie, type)
- **Acheter un permis** — détails du permis, sélection du type, véhicule, date
- **Paiement** — formulaire de paiement et récapitulatif
- **Pages de confirmation et d'échec de paiement** — validation du paiement
- **Mes permis** — permis actifs et passés
- **Véhicule** — gestion des véhicules

---

## 📸 Captures d'écran

*Page Mes permis*
![Tickets Page](assets/MyTicketsPage.png)

*Page Véhicule*
![Vehicle Page](assets/VehiclePage.png)

*Page d'accueil*
![Home Page](assets/HomePage.png)

---

## Outils

- Figma (design, prototypage, auto-layout)
- Conformité accessibilité WCAG AA
- Mobile-first, adaptatif sur 4 formats

---

## Mes contributions

- Identification des variables comportementales et distribution des participants (schémas comportementaux)
- Page d'accueil
- Page Stationnement
- Page Acheter un permis
- Page Véhicule
- Page Invité
- Page Mes permis

---

## Contributeurs

Projet universitaire d'équipe — GLO-4000, Université Laval.

- Petiton Wiseley Paul-Enzer
- Emmanuella Iris Andréa Lehe
- Aliya Imann Ouedraogo
- Louis Nathan Kameni
- Auriane Vadelle Djou Donchi
- Guerby Benoit
- Chadi Chibli
- Kris Bani Nguinano

---

[petiton.dev](https://petiton.dev)

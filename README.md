
# 🏧 ATM Management System (Java)

Un système de gestion de distributeur automatique de billets (DAB/ATM) développé en **Java**, en ligne de commande (console), permettant de simuler la création de comptes, la gestion de comptes courants et épargne, les dépôts, retraits, transferts, et authentification par code client/PIN.

---

## 🔧 Fonctionnalités principales

- Authentification sécurisée (numéro client + PIN)
- Création de nouveaux comptes utilisateurs
- Gestion des comptes :
  - ✅ Consultation du solde (compte courant / épargne)
  - ➕ Dépôt d’argent
  - ➖ Retrait d’argent
  - 🔄 Transfert entre comptes
- Affichage formaté des montants en devise
- Validation des entrées utilisateurs
- Simulation de données utilisateurs par défaut

---

## 🧱 Structure du projet

```bash
ATM_Management_System/
├── src/
│   └── org/
│       └── example/
│           ├── Account.java        # Classe de modèle pour compte bancaire
│           └── OptionMenu.java     # Menu interactif et logique métier
├── README.md
└── ...
```

---

## ▶️ Exécution

### Prérequis

- Java JDK installé (version 8 ou supérieure)
- Un IDE (comme IntelliJ IDEA, Eclipse) ou terminal avec javac/java


## 📝 Exemples d'utilisation

- Se connecter avec un compte par défaut :
  - **Client:** `952141`
  - **PIN:** `191904`

- Ou créer un nouveau compte via le menu principal.

---

## 📁 Données simulées

```java
data.put(952141, new Account(952141, 191904, 1000, 5000));
data.put(123, new Account(123, 123, 20000, 50000));
```

---

## ✅ TODO (améliorations possibles)

- Persistance des données (fichier ou base de données)
- Interface graphique (Swing / JavaFX)
- Gestion multi-clients en parallèle
- Internationalisation (support multilingue)
- Ajout de tests unitaires (JUnit)

---

## 🧑‍💻 Auteur

- **Houssem Eddine Jlassi**
- [GitHub]( https://github.com/JlassiHoussem) – N’hésite pas à suivre ⭐ le projet si tu le trouves utile.

---

## 📜 Licence

Ce projet est libre d’utilisation à des fins éducatives ou personnelles.

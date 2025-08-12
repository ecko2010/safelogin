# SafeLogin - Gestionnaire de Mots de Passe Sécurisé

[![Version](https://img.shields.io/badge/version-1.0-blue.svg)](https://github.com/ecko2010/safelogin)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows-lightgrey.svg)](https://www.microsoft.com/windows)
[![.NET](https://img.shields.io/badge/.NET-6.0-purple.svg)](https://dotnet.microsoft.com/)

<div align="center">
  <img src="Assets/logo.png" alt="Logo SafeLogin" width="128" height="128">
  <h3>🔐 Vos Clés Numériques, Stockées en Sécurité</h3>
  <p><em>Un gestionnaire de mots de passe sécurisé et local avec chiffrement avancé</em></p>
</div>

---

## 📋 Table des Matières

### 🌍 Langues / Languages
- [🇫🇷 Français](README_FR.md) (Actuel)
- [🇸🇦 العربية](README_AR.md)
- [🇺🇸 English](README_EN.md)
- [🇩🇪 Deutsch](README_DE.md)
- [🇨🇳 中文](README_CN.md)

### 📖 Contenu
- [Aperçu](#-aperçu)
- [Fonctionnalités](#-fonctionnalités)
- [Informations de Version](#-informations-de-version)
- [Connectivité Internet](#-connectivité-internet)
- [Technologies](#-technologies)
- [Installation](#-installation)
- [Démarrage Rapide](#-démarrage-rapide)
- [Sécurité et Confidentialité](#-sécurité-et-confidentialité)
- [Contribution](#-contribution)
- [Support](#-support)
- [FAQ](#-faq)
- [Licence](#-licence)

---

## 🌟 Aperçu

**SafeLogin** est un gestionnaire de mots de passe sécurisé pour ordinateur de bureau, conçu pour garder vos identifiants numériques en sécurité et organisés. Construit avec des principes de sécurité prioritaires, il stocke tous vos mots de passe localement avec un chiffrement de niveau militaire, garantissant que vos données sensibles ne quittent jamais votre appareil.

### Pourquoi SafeLogin ?

- 🔒 **Stockage 100% Local** - Vos données restent sur votre appareil
- 🛡️ **Chiffrement de Niveau Militaire** - Chiffrement AES-256
- 🎯 **Convivial** - Interface arabe propre et intuitive
- 🚀 **Rapide et Léger** - Accès rapide à vos mots de passe
- 🔍 **Recherche Intelligente** - Trouvez vos identifiants instantanément
- 📝 **Support des Notes** - Ajoutez du contexte à vos mots de passe

---

## ✨ Fonctionnalités

### 🔐 Fonctionnalités de Sécurité
- **Chiffrement AES-256** - Chiffrement standard de l'industrie pour toutes les données stockées
- **Stockage Local Uniquement** - Aucune dépendance cloud, confidentialité complète
- **Protection par Mot de Passe Principal** - Un seul mot de passe pour accéder à tous les identifiants
- **Génération de Mots de Passe Sécurisés** - Générateur de mots de passe forts intégré
- **Verrouillage Automatique** - Délai d'expiration automatique de session pour la sécurité

### 📊 Gestion des Données
- **Ajouter/Modifier/Supprimer** - Opérations CRUD complètes pour les identifiants
- **Recherche Intelligente** - Recherche par site, nom d'utilisateur ou notes
- **Opérations en Lot** - Gérez plusieurs identifiants efficacement
- **Exportation de Données** - Sauvegardez vos données en sécurité
- **Support des Notes** - Ajoutez des notes détaillées à chaque identifiant

### 🎨 Interface Utilisateur
- **Interface Anglaise** - L'interface actuelle est en anglais
- **Design Moderne** - Interface WPF propre et intuitive
- **🔄 Thèmes Sombre/Clair** - Prévu pour les versions futures
- **Mise en Page Responsive** - S'adapte aux différentes tailles d'écran
- **🔄 Interface Arabe** - Support natif de la langue arabe prévu pour v2.0

---

## 📊 Informations de Version

### 🚀 Version 1.0 (Actuelle)
**Publiée :** Décembre 2024

**Fonctionnalités Principales :**
- ✅ Stockage sécurisé des mots de passe avec chiffrement AES-256
- ✅ Ajouter, modifier, supprimer et rechercher des identifiants
- ✅ Support des notes pour un contexte supplémentaire
- ✅ Interface utilisateur anglaise
- ✅ Système d'activation de licence
- ✅ Base de données SQLite locale
- ✅ Protection par mot de passe principal
- ✅ Journalisation des erreurs et validation

### 🔮 Version 2.0 (Prévue)
**Attendue :** Q2 2025

**Fonctionnalités à Venir :**
- 🔄 **Sauvegarde et Restauration Automatiques**
- 🌐 **Synchronisation Cloud**
- 🔄 **Système de Mise à Jour Automatique**
- 🛡️ **Sécurité Renforcée**
- 📱 **Application Mobile Compagnon**

---

## 🌐 Connectivité Internet

### Version 1.0 - Utilisation Internet Minimale

**Quand Internet est Requis :**
- 🔑 **Activation de Licence Uniquement** - Processus d'activation unique
- 🔄 **Validation de Licence** - Vérification périodique de la licence

**Quand Internet n'est PAS Requis :**
- 💾 **Utilisation Quotidienne** - Toutes les fonctionnalités principales fonctionnent hors ligne
- 🔍 **Recherche et Navigation** - Accès complet hors ligne à vos données
- ➕ **Ajouter/Modifier des Identifiants** - Opérations CRUD complètes hors ligne
- 🔐 **Accès aux Mots de Passe** - Accès instantané sans internet

---

## 🛠️ Technologies

### Technologies Principales
- **C# (.NET 6)** - Framework moderne et multiplateforme
- **WPF (Windows Presentation Foundation)** - Interface utilisateur de bureau riche
- **SQLite** - Base de données légère et intégrée
- **Modèle MVVM** - Architecture propre et séparation des préoccupations

### Bibliothèques de Sécurité
- **System.Security.Cryptography** - Chiffrement AES-256
- **BCrypt.Net** - Hachage sécurisé des mots de passe
- **System.Text.Json** - Sérialisation sécurisée des données

---

## 💻 Installation

### Configuration Système Requise
- **Système d'Exploitation :** Windows 10/11 (64-bit)
- **Runtime .NET :** .NET 6.0 ou ultérieur
- **Mémoire :** 512 MB RAM minimum
- **Stockage :** 100 MB d'espace disponible
- **Affichage :** Résolution minimale 1024x768

### Méthodes d'Installation

#### Méthode 1 : Installateur (Recommandé)
1. Téléchargez `SafeLogin_Installer.exe` depuis les versions
2. Exécutez l'installateur en tant qu'administrateur
3. Suivez l'assistant d'installation
4. Lancez SafeLogin depuis le Menu Démarrer

#### Méthode 2 : Version Portable
1. Téléchargez `SafeLogin.zip` depuis les versions
2. Extrayez vers votre emplacement préféré
3. Exécutez `SafeLogin.exe` directement
4. Aucune installation requise

---

## 🚀 Démarrage Rapide

### Premier Lancement
1. **Lancez SafeLogin** depuis votre Menu Démarrer ou bureau
2. **Entrez la Clé de Licence** - Activez votre copie (internet requis)
3. **Créez un Mot de Passe Principal** - Ceci protège toutes vos données
4. **Commencez à Ajouter des Mots de Passe** - Commencez à sécuriser vos identifiants

### Ajouter Votre Premier Mot de Passe
1. Cliquez sur le bouton **"Ajouter Nouveau"**
2. Entrez le nom du **Site Web/Service**
3. Entrez votre **Nom d'utilisateur**
4. Entrez votre **Mot de passe**
5. Ajoutez des **Notes** (optionnel)
6. Cliquez sur **"Enregistrer"**

---

## 🔒 Sécurité et Confidentialité

### Nos Engagements de Sécurité

#### 🛡️ Ce que Nous Protégeons
- **Tous les Mots de Passe** - Chiffrés avec AES-256
- **Notes Personnelles** - Stockage entièrement chiffré
- **Données Utilisateur** - Stockage local complet
- **Mot de Passe Principal** - Haché de manière sécurisée avec BCrypt

#### 🚫 Ce que Nous ne Collectons PAS
- **Aucune Analyse d'Utilisation** - Nous ne suivons pas comment vous utilisez l'application
- **Aucune Donnée Personnelle** - Vos informations restent sur votre appareil
- **Aucune Donnée de Mot de Passe** - Vos mots de passe ne quittent jamais votre ordinateur
- **Aucun Historique de Navigation** - Nous ne surveillons pas votre activité web

---

## 🤝 Contribution

Nous accueillons les contributions de la communauté ! Voici comment vous pouvez aider :

### Façons de Contribuer
- 🐛 **Signaler des Bugs** - Aidez-nous à identifier et corriger les problèmes
- 💡 **Suggérer des Fonctionnalités** - Partagez vos idées d'améliorations
- 🌍 **Traductions** - Aidez à localiser l'application
- 📖 **Documentation** - Améliorez nos guides et docs
- 💻 **Contributions de Code** - Soumettez des pull requests

---

## 📞 Support

### Obtenir de l'Aide

#### 📧 Options de Contact
- **Groupe Telegram :** [Rejoindre le Groupe de Support](https://t.me/SafeLoginSupport)
- **GitHub Issues :** [Signaler des bugs ou demander des fonctionnalités](https://github.com/ecko2010/safelogin/issues)
- **Documentation :** Consultez nos guides complets

---

## ❓ FAQ

### Questions Générales

**Q : SafeLogin est-il gratuit ?**
R : SafeLogin nécessite une licence pour une fonctionnalité complète. Nous offrons des périodes d'essai et des remises éducatives.

**Q : Puis-je utiliser SafeLogin hors ligne ?**
R : Oui ! Après l'activation initiale de la licence, SafeLogin fonctionne complètement hors ligne.

**Q : À quel point mes données sont-elles sécurisées ?**
R : Vos données sont chiffrées avec AES-256 et stockées localement. Nous ne pouvons pas accéder à vos mots de passe.

---

## 📄 Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

<div align="center">
  <h3>🔐 SafeLogin - Votre Sécurité Numérique, Simplifiée</h3>
  <p><em>Construit avec ❤️ pour la gestion sécurisée des mots de passe</em></p>
  
  <p><strong>Version 1.0</strong> | <em>Décembre 2024</em></p>
</div>

---

*Dernière mise à jour : Décembre 2024*
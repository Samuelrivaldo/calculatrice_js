# 📚 Guide d'Utilisation ProCalc

Bienvenue dans ProCalc! Ce guide vous explique comment utiliser toutes les fonctionnalités de la calculatrice comptable.

---

## 🎯 Interface Générale

L'interface est divisée en 4 sections principales:
1. **Calculatrice Standard** (gauche) - Calculs mathématiques basiques
2. **Outils Comptables** (droite) - TVA, Marge, Rabais
3. **Historique** (bas gauche) - Tous vos calculs récents
4. **Convertisseur Devises** (bas droite) - Conversions

---

## 1️⃣ Calculatrice Standard

### 📖 Utilisation

La calculatrice affiche vos calculs en temps réel. Vous pouvez utiliser:
- **Les boutons de souris** pour cliquer
- **Le clavier** pour une saisie plus rapide

### 📋 Boutons

| Bouton | Fonction |
|--------|----------|
| **C** | Effacer tout et recommencer |
| **←** | Supprimer le dernier chiffre |
| **÷** | Division |
| **×** | Multiplication |
| **−** | Soustraction |
| **+** | Addition |
| **=** | Afficher le résultat |
| **.** | Virgule décimale |
| **00** | Ajouter deux zéros |

### 🎮 Exemples

**Exemple 1: Addition simple**
```
123 + 456 = 579
```
- Cliquez sur: 1, 2, 3, +, 4, 5, 6, =
- Résultat: 579

**Exemple 2: Division avec décimales**
```
100 ÷ 3 = 33.33
```
- Cliquez sur: 1, 0, 0, ÷, 3, =
- Résultat: 33.33

### ⌨️ Raccourcis Clavier

Les raccourcis les plus utiles:
- `0-9` : Saisir des chiffres
- `+` / `-` / `*` / `/` : Opérateurs
- `.` : Décimal
- `Entrée` : Calculer
- `Retour arrière` : Effacer un chiffre
- `Échap` : Effacer tout

---

## 2️⃣ Outils Comptables

### TVA (Taxe sur la Valeur Ajoutée)

#### 🎯 Objectif
Calculer le montant TTC (Toutes Taxes Comprises) à partir du montant HT (Hors Taxes).

#### 📝 Comment faire

1. **Entrez le montant HT**
   - Exemple: `150.00`
   
2. **Sélectionnez le taux TVA**
   - 5.5% : Taux réduit (livres, certains aliments)
   - 10% : Taux intermédiaire
   - 20% : Taux normal (par défaut, la plupart des produits)
   - 2.1% : Taux super-réduit

3. **Le résultat s'affiche automatiquement**
   - Montant HT affiché
   - Montant TVA calculé
   - **Montant TTC en évidence**

#### 💡 Exemple Pratique

```
Montant HT: 100€
Taux TVA: 20%
↓
Montant TVA: 20€
Montant TTC: 120€
```

#### 🧮 Formule
```
TVA = HT × (Taux / 100)
TTC = HT + TVA
```

---

### Marge (Analyse Marges)

#### 🎯 Objectif
Analyser la profitabilité d'une vente.

#### 📝 Comment faire

1. **Entrez le prix d'achat**
   - Prix auquel vous avez acheté le produit
   - Exemple: `50€`

2. **Entrez le prix de vente**
   - Prix auquel vous vendez le produit
   - Exemple: `75€`

3. **Consultez les résultats**
   - **Marge Brute**: Bénéfice en euros
   - **Marge %**: Bénéfice en pourcentage
   - **Coefficient**: Multiplicateur du prix d'achat

#### 💡 Exemple Pratique

```
Prix d'achat: 50€
Prix de vente: 75€
↓
Marge Brute: 25€
Marge %: 50%
Coefficient: 1.50x
```

**Interprétation**:
- Vous gagnez 25€ par vente
- C'est une marge de 50% sur le prix d'achat
- Vous vendez 1.5 fois plus cher que votre prix d'achat

#### 🧮 Formules
```
Marge Brute = Prix Vente - Prix Achat
Marge % = (Marge Brute / Prix Achat) × 100
Coefficient = Prix Vente / Prix Achat
```

#### 📊 Interprétation des Pourcentages

- **< 10%** : Très faible marge
- **10-30%** : Faible marge (biens de consommation)
- **30-50%** : Bonne marge (commerce)
- **50%+** : Très bonne marge (services, produits premium)

---

### Rabais (Réductions)

#### 🎯 Objectif
Calculer le prix final après application d'une réduction.

#### 📝 Comment faire

1. **Entrez le montant original**
   - Prix avant réduction
   - Exemple: `100€`

2. **Entrez le taux de rabais**
   - Le pourcentage de réduction
   - Exemple: `20%`

3. **Consultez le résultat**
   - Montant de la réduction
   - **Prix final en évidence**

#### 💡 Exemple Pratique

```
Montant original: 100€
Rabais: 20%
↓
Réduction: 20€
Prix final: 80€
```

#### 🎯 Cas d'Usage Courants

| Situation | Rabais | Exemple |
|-----------|--------|---------|
| Solde classique | 20-30% | 100€ → 70-80€ |
| Solde importante | 40-50% | 100€ → 50-60€ |
| Déstockage | 60-70% | 100€ → 30-40€ |
| Fidélité client | 5-10% | 100€ → 90-95€ |
| Code promo | 10-25% | 100€ → 75-90€ |

#### 🧮 Formule
```
Réduction = Montant Original × (Rabais / 100)
Prix Final = Montant Original - Réduction
```

---

## 3️⃣ Convertisseur Devises

#### 🎯 Objectif
Convertir rapidement des euros vers d'autres devises.

#### 📝 Comment faire

1. **Entrez le montant en EUR**
   - Exemple: `100€`

2. **Sélectionnez la devise cible**
   - USD (Dollar américain)
   - GBP (Livre sterling)
   - CHF (Franc suisse)
   - CAD (Dollar canadien)
   - JPY (Yen japonais)

3. **Le résultat s'affiche automatiquement**

#### 💡 Exemple Pratique

```
Montant: 100€
Devise: USD (1.10)
↓
Résultat: 110$
```

#### ⚠️ Important

Les taux de change incluent sont **indicatifs** et mis à jour manuellement. Pour des transactions réelles, consultez un service de change professionnel.

**Taux inclus**:
- USD: 1.10 (Dollar américain)
- GBP: 0.86 (Livre sterling)
- CHF: 6.30 (Franc suisse)
- CAD: 1.23 (Dollar canadien)
- JPY: 1020 (Yen japonais)

---

## 4️⃣ Historique

#### 📖 Utilisation

L'historique enregistre **automatiquement** tous vos calculs.

#### ✨ Fonctionnalités

- ✅ Les 20 derniers calculs sont conservés
- ✅ Chaque calcul affiche l'opération ET le résultat
- ✅ Horodatage précis (heure, minute, seconde)
- ✅ Persistance locale (données conservées après fermeture)

#### 📝 Affichage

Chaque ligne de l'historique montre:
```
Operation: TVA 20% sur 100€
Résultat: 120,00€ • 14:32:45
```

#### 🗑️ Effacer l'Historique

1. Cliquez sur le bouton **"Effacer l'historique"**
2. Confirmez l'action
3. Tous les calculs seront supprimés

⚠️ Cette action est **irréversible**!

---

## 🎨 Conseils & Astuces

### ⚡ Productivité

1. **Utilisez le clavier** - Plus rapide que la souris
2. **Exploitez l'historique** - Vous retrouvez vos calculs précédents
3. **Les calculs sont sauvés** - Fermez et rouvrez sans crainte

### 💡 Calculs Avancés

**Combiner les outils**:
```
① Calculatrice: 50 × 2 = 100€
② TVA (20%): 100€ HT → 120€ TTC
③ Rabais (10%): 120€ → 108€ final
```

### 📱 Mobile

L'application est optimisée pour les téléphones:
- Interface tactile fluide
- Boutons oversized pour les doigts
- Responsive à tous les écrans

### 🌙 Accessibilité

- Contraste élevé pour la lisibilité
- Texte suffisamment gros
- Navigation au clavier complète

---

## ❓ Foire Aux Questions (FAQ)

### Q: Mes données sont-elles sauvegardées?
**R:** Oui! L'historique est sauvegardé localement dans votre navigateur. Les données persistent même après fermeture.

### Q: Comment réinitialiser tout?
**R:** Cliquez sur "Effacer l'historique" dans la section Historique.

### Q: Fonctionne-t-elle hors-ligne?
**R:** Oui! Après le premier chargement, la calculatrice fonctionne complètement hors-ligne.

### Q: Peut-je utiliser hors-ligne?
**R:** Oui, l'application fonctionne 100% en client-side sans serveur.

### Q: Peut-on exporter l'historique?
**R:** Actuellement non, mais vous pouvez prendre des captures d'écran ou faire un screenshot.

### Q: Quel est le nombre maximum de décimales?
**R:** 8 décimales en interne, affichées en français (virgule) avec 2 décimales pour les montants.

### Q: Les taux TVA peuvent-ils être personnalisés?
**R:** Actuellement, les taux prédéfinis ne peuvent pas être modifiés. Les révisions à venir pourraient permettre cela.

### Q: Est-elle sécurisée pour des données sensibles?
**R:** Les données restent sur votre ordinateur. Pas d'envoi de données vers des serveurs.

---

## 🚀 Cas d'Usage Réels

### Cas 1: Facture Client
```
① Montant HT des services: 500€
② TVA (20%): ✓ Calcule → 600€ TTC
③ Rabais (5% fidélité): ✓ Calcule → 570€ final
```

### Cas 2: Analyse Produit
```
① Prix achat: 15€
② Prix vente: 45€
③ Marge: ✓ Calcule → 200% de marge!
```

### Cas 3: Gestion Internationale
```
① Vente en Europe: 1000€
② Convertir en USD: ✓ Calcule → 1100$
③ Convertir en CHF: ✓ Calcule → 6300 CHF
```

---

## 📞 Support

Si vous rencontrez des problèmes:
1. Videz le cache de votre navigateur
2. Actualisez la page (F5)
3. Essayez un autre navigateur
4. Réinstallez si le problème persiste

---

**Version**: 1.0.0  
**Dernière mise à jour**: Mars 2026  
**Support**: Documentation complète incluse

Bon calcul! 🧮✨

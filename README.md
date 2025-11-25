# 🚀 Guide de Déploiement - Assistant Email avec Groq (100% GRATUIT)

## ✅ TOTALEMENT GRATUIT - Aucun paiement requis !

---

## 📋 ÉTAPE 1 : Télécharger les fichiers

Tu as déjà un dossier `groq-deploy/` avec :
- `index.html` (la page web - couleurs bleu/rouge)
- `api/generate.js` (le backend avec Groq)
- `package.json` (configuration)
- `vercel.json` (config Vercel)

---

## 🔑 ÉTAPE 2 : Obtenir une clé API Groq (100% GRATUIT)

1. **Va sur** : https://console.groq.com/
2. **Crée un compte** (email suffit, pas de carte bancaire !)
3. Une fois connecté, clique sur **"API Keys"** (menu de gauche)
4. Clique sur **"Create API Key"**
5. Donne un nom : `Email Assistant`
6. **COPIE** la clé qui commence par `gsk_...`
7. **GARDE-LA** précieusement (tu en auras besoin à l'étape 5)

💡 **Note** : Groq est **100% GRATUIT** - Pas de limite de crédits à payer ! ✅

---

## 🌐 ÉTAPE 3 : Créer un compte Vercel (GRATUIT)

1. **Va sur** : https://vercel.com/signup
2. **Inscris-toi avec GitHub** (recommandé)
   - Si tu n'as pas GitHub, crée un compte sur https://github.com/signup (gratuit)
3. **Aucune carte bancaire demandée** ✅

---

## 📤 ÉTAPE 4 : Préparer GitHub

1. **Connecte-toi sur GitHub** : https://github.com/
2. **Crée un nouveau repository** :
   - Clique sur le **"+"** en haut à droite
   - Sélectionne **"New repository"**
   - Nom : `email-assistant`
   - Choisis **"Public"** ou **"Private"** (au choix)
   - ❌ **NE coche PAS** "Add a README file"
   - Clique **"Create repository"**

3. **Upload tes fichiers** :
   - Sur la page du repository vide, clique **"uploading an existing file"**
   - **Drag & drop** tous les fichiers du dossier `groq-deploy/` :
     * `index.html`
     * `package.json`
     * `vercel.json`
     * Crée un dossier `api/` et mets `generate.js` dedans
   - Ou clique **"choose your files"** et sélectionne-les
   - Clique **"Commit changes"** en bas

---

## 🚀 ÉTAPE 5 : Déployer sur Vercel

1. **Retourne sur Vercel** : https://vercel.com/
2. **Importe ton projet** :
   - Clique sur **"Add New..."** → **"Project"**
   - Sélectionne **"Import Git Repository"**
   - Choisis ton repository **`email-assistant`**
   - Clique **"Import"**

3. **Configure ta clé API Groq** :
   - Dans la section **"Environment Variables"**
   - **Name** : `GROQ_API_KEY`
   - **Value** : Colle ta clé Groq (celle qui commence par `gsk_...`)
   - Clique **"Add"**

4. **Déploie** :
   - Clique **"Deploy"**
   - Attends 30-60 secondes...
   - 🎉 **C'EST EN LIGNE !**

---

## 🎯 ÉTAPE 6 : Utiliser ton site

1. **Vercel te donne une URL** : `https://email-assistant-xxx.vercel.app`
2. **Clique sur le lien** ou copie-le
3. **Ouvre-le dans ton navigateur**
4. **Teste l'outil** :
   - Écris un brouillon d'email
   - Choisis tes paramètres (langue, ton, etc.)
   - Clique "Générer l'email"
   - ✨ Magic ! Ton email professionnel est généré !

---

## 📱 Partage ton outil

- **Partage l'URL** avec tes collègues
- **Ça marche sur mobile** aussi ! 📲
- **Accessible partout** avec internet

---

## 🔄 ÉTAPE 7 : Mettre à jour (optionnel)

Si tu veux modifier quelque chose plus tard :

1. **Modifie les fichiers sur GitHub** (directement sur le site)
2. **Vercel redéploie automatiquement** ! ✅

---

## ❓ FAQ - Questions Fréquentes

**Q : C'est vraiment 100% gratuit ?**
✅ Oui ! Groq est totalement gratuit + Vercel est gratuit

**Q : Il y a des limites ?**
✅ Groq : Très généreux (plusieurs milliers de requêtes/jour)
✅ Vercel : 100 GB de bande passante/mois (largement suffisant)

**Q : Combien de temps ça prend ?**
⏱️ 10-15 minutes pour tout configurer

**Q : Mon URL est bizarre, je peux la changer ?**
🌐 Oui ! Dans Vercel → Settings → Domains, ajoute ton propre domaine

**Q : Ça marche bien ?**
🚀 Oui ! Groq utilise Llama 3.3 70B - très performant et RAPIDE !

**Q : C'est sécurisé ?**
🔒 Oui ! Ta clé API est stockée en sécurité sur Vercel

**Q : Je peux utiliser mon propre domaine ?**
🌐 Oui ! Va dans Vercel → Settings → Domains

**Q : Les emails générés sont-ils sauvegardés quelque part ?**
❌ Non, tout reste local dans ton navigateur. Rien n'est sauvegardé.

---

## 🆘 Problèmes courants

**❌ "API key not configured"**
→ Retourne dans Vercel → Settings → Environment Variables
→ Vérifie que `GROQ_API_KEY` est bien ajoutée
→ Redéploie le projet

**❌ "Erreur lors de la génération"**
→ Vérifie que ta clé Groq est valide
→ Vérifie que tu as bien déployé le dossier `api/`

**❌ "404 Not Found"**
→ Vérifie que `index.html` est bien à la racine
→ Vérifie que `vercel.json` est présent

---

## 🎉 Félicitations !

Tu as maintenant ton propre **Assistant Email Professionnel** :
- ✅ 100% GRATUIT
- ✅ En ligne 24/7
- ✅ Accessible partout
- ✅ IA puissante (Llama 3.3 70B)
- ✅ Couleurs bleu/rouge
- ✅ Correction orthographique
- ✅ Traduction FR/EN
- ✅ Plusieurs tons (professionnel, amical, décontracté)

**Ton URL finale** : `https://ton-projet.vercel.app`

Profite bien ! 🚀

---

## 📧 Besoin d'aide ?

Si tu bloques quelque part :
1. Vérifie que tu as bien suivi TOUTES les étapes dans l'ordre
2. Regarde les logs sur Vercel Dashboard (onglet "Deployments")
3. Vérifie ta clé API Groq
4. Assure-toi que tous les fichiers sont bien uploadés sur GitHub

Bon courage ! 💪
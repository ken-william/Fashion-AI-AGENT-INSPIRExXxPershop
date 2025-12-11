This is PERSHOP READ ME
# Pershop Pilote — Multi-Agent Fashion Intelligence System

Pershop Pilote est un système IA multi-agents conçu pour analyser un client, identifier ses besoins, recommander le personal shopper le plus compatible et proposer une stratégie shopping adaptée. 
# Pershop Pilote — Multi-Agent Fashion Intelligence System

Pershop Pilote est un système IA multi-agents conçu pour analyser un client, identifier ses besoins, recommander le personal shopper le plus compatible et proposer une stratégie shopping adaptée. Ce projet a été développé pour la startup Pershop.

## Fonctionnalités principales

### 1. Agent Client — Analyse du Profil
- Analyse du style vestimentaire, morphologie, budget, marques, objectif.
- Déduction des besoins principaux du client.
- Génération d’un profil client structuré (JSON).

### 2. Agent Matcheur — Recommandation Shopper
- Comparaison client ↔ personal shoppers.
- Calcul d’un score de compatibilité.
- Explication détaillée : “Pourquoi ce shopper ?”.

### 3. Agent Marques — Stratégie Shopping
- Recommandation de marques cohérentes avec le style et le budget.
- Proposition d’une stratégie shopping personnalisée.

### Pipeline automatisé via n8n
- Importation & nettoyage des données (Google Drive / CSV).
- Orchestration des agents IA (Google Gemini).
- Production d’une sortie JSON complète.

### Configuration de la clé API Gemini

Ce projet utilise Google Gemini Pro.  
Pour obtenir une clé API, rendez-vous sur :

https://aistudio.google.com/app/apikey

Une fois la clé générée :

1. Ouvrez n8n  
2. Accédez aux nodes **Google Gemini**  
3. Renseignez votre clé dans le champ **API Key**  
4. Sauvegardez et relancez le workflow





This is PERSHOP READ ME
#Pershop Pilote — Multi-Agent Fashion Intelligence System
Pershop Pilote est un système IA multi-agents conçu pour analyser un client, identifier ses besoins, recommander le personal shopper le plus compatible et proposer une stratégie shopping adaptée. Ce projet a été développé pour la startup **Pershop** dans le cadre de l’Agentic Hackathon.

## Fonctionnalités principales

###  1. Agent Client — Analyse du Profil
- Analyse du style vestimentaire, morphologie, budget, marques, objectif.
- Déduction des besoins principaux du client.
- Génération d’un profil client structuré (JSON).
  
###  2. Agent Matcheur — Recommandation Shopper
- Comparaison client ↔ personal shoppers.
- Calcul d’un score de compatibilité.
- Explication détaillée : “Pourquoi ce shopper ?”.

###  3. Agent Marques — Stratégie Shopping
- Recommandation de marques cohérentes avec le style et le budget.
- Proposition d’une stratégie shopping personnalisée.

###  Pipeline automatisé via n8n
- Importation & nettoyage des données (Google Drive / CSV).
- Orchestration des agents IA (Google Gemini).
- Production d’une sortie JSON complète.

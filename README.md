# Gestion du matériel — Manara Productions

Application de scan des étiquettes QR du matériel de production.

- Scanner une étiquette ouvre `?c=CODE` : fiche, sortie / retour avec PIN, historique.
- Sans paramètre : tableau de bord (disponibles, sortis, en retard).
- Données : Supabase (projet `manara-materiel`), écritures uniquement via fonctions protégées par PIN.

⚠️ Ne pas renommer ce dépôt : les étiquettes imprimées pointent vers `https://emma12000.github.io/manara-materiel/`.

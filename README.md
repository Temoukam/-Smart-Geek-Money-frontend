# -Smart-Geek-Money-frontend
```mermaid
graph TD;
  Start --> Connexion[Utilisateur se connecte];
  Connexion --> Vérification{Identifiants valides ?};
  Vérification -- Oui --> Accès[Accès au tableau de bord];
  Vérification -- Non --> Erreur[Message d'erreur affiché];
  Accès --> Action[Utilisateur effectue une action];
  Action --> Sauvegarde[Les données sont sauvegardées];
  Sauvegarde --> Fin;
  Erreur --> Fin;
  Fin((Fin))

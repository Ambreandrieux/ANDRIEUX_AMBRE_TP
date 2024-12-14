# Guide de Contribution

Merci de votre intérêt pour contribuer à ce projet ! Nous apprécions chaque contribution, qu'il s'agisse d'une suggestion, d'une correction de bug ou d'une nouvelle fonctionnalité. Veuillez suivre les directives ci-dessous pour que votre contribution soit facilement intégrée au projet.

---

## Processus de Contribution

1. **Forkez le dépôt** :
   Cliquez sur le bouton "Fork" en haut à droite de la page GitHub pour créer une copie du projet sur votre propre compte.

2. **Clonez votre fork** :

   ```bash
   git clone https://github.com/Ambreandrieux/ANDRIEUX_AMBRE_TP
   cd nom-du-repo
   ```

3. **Créez une branche pour vos modifications** :

   ```bash
   git checkout -b ma-branche
   ```

4. **Apportez vos changements** :

   - Assurez-vous de suivre les standards de codage du projet.
   - Vérifiez que votre code ne casse pas les fonctionnalités existantes.

5. **Testez vos modifications** :
   Lancez les tests pour valider vos changements :

   ```bash
   npm test
   ```

6. **Commitez vos changements** :

   ```bash
   git add .
   git commit -m "Description claire de vos changements"
   ```

7. **Poussez vos modifications** :

   ```bash
   git push origin ma-branche
   ```

8. **Créez une Pull Request** :
   - Accédez au dépôt principal sur GitHub.
   - Cliquez sur "Pull Requests" > "New Pull Request".
   - Sélectionnez votre branche et soumettez votre PR.

---

## Règles de Contribution

1. **Clarté des commits** :

   - Utilisez des messages de commit explicites et concis.
   - Exemple : `Ajout d'une nouvelle fonctionnalité pour la gestion des utilisateurs`.

2. **Respect des standards** :

   - Assurez-vous que votre code respecte les conventions définies dans le projet.
   - Exécutez les linters et corrigez les erreurs avant de soumettre.

3. **Tests** :
   - Fournissez des tests unitaires pour toute nouvelle fonctionnalité.
   - Vérifiez que tous les tests passent avant de soumettre votre PR.

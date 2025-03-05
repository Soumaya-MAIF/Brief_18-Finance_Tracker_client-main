# Problèmes détectés et suggestions de correction

## Login
1. **Absence de notification en cas d'échec de connexion** :
   - **Problème** : L'utilisateur n'est pas informé en cas d'échec de connexion, seulement une animation de chargement infini est visible
   - **Suggestion** : Ajouter un message d'erreur visible pour l'utilisateur en cas d'échec de connexion

2. **Couleur du bouton Login non accessible** :
   - **Problème** : La couleur du bouton Login n'est pas accessible.
   - **Suggestion** : Utiliser des couleurs conformes aux normes d'accessibilité pour garantir un contraste suffisant

3. **Boutons Login et Register fusionnés** :
   - **Problème** : Les boutons Login et Register sont trop proches et difficilement distinguables
   - **Suggestion** : Espacer les boutons et utiliser des styles distincts pour mieux les différencier

4. **Absence d'option "Rester connecté"** :
   - **Problème** : L'utilisateur doit se reconnecter à chaque fois
   - **Suggestion** : Ajouter une case à cocher "Rester connecté" pour permettre à l'utilisateur de rester connecté

## Layout
1. **Problème de contraste sur l'onglet sélectionné** :
   - **Problème** : Le contraste entre la couleur de l'onglet sélectionné et le fond de la page est insuffisant
   - **Suggestion** : Augmenter le contraste entre l'onglet sélectionné et le fond de la page

2. **Problème de contraste sur la police** :
   - **Problème** : Le contraste entre la couleur de la police et celle de l'onglet est insuffisant
   - **Suggestion** : Utiliser des couleurs de police avec un contraste suffisant par rapport à l'onglet

3. **Menu tronqué en mode mobile** :
   - **Problème** : Le menu est tronqué lorsque l'écran passe au format mobile
   - **Suggestion** : Adapter le menu pour qu'il soit entièrement visible en mode mobile (responsive design)

4. **Bouton Logout non distinct** :
   - **Problème** : Le bouton Logout ne se distingue pas des autres onglets et le hover ne s'applique pas sur lui au passage de la souris contrairement aux autres onglets
   - **Suggestion** : Utiliser un style distinct pour le bouton Logout afin de le différencier des autres onglets

5. **Absence de retour à la page principale** :
   - **Problème** : Il manque un bouton pour retourner à la page principale
   - **Suggestion** : Ajouter un bouton de retour à la page principale

## Transaction
1. **Identification des catégories de transactions** :
   - **Problème** : Impossible d'identifier les catégories des transactions listées
   - **Suggestion** : Ajouter des étiquettes ou des icônes pour indiquer les catégories des transactions

2. **Ajout de transaction et méthode de paiement** :
   - **Problème** : Impossible de sauvegarder une transaction en brouillon si aucune méthode de paiement n'a été enregistrée au préalable
   - **Suggestion** : Permettre la sauvegarde de transactions en brouillon sans méthode de paiement ou ajouter une option pour enregistrer une méthode de paiement directement depuis le formulaire de transaction

3. **Dépassement de la limite de budget** :
   - **Problème** : Les transactions dépassant la limite de budget ne sont pas signalées
   - **Suggestion** : Ajouter une notification ou un indicateur visuel pour les transactions dépassant la limite de budget

4. **Suppression ou modification de transactions** :
   - **Problème** : Impossible de supprimer ou modifier une transaction enregistrée
   - **Suggestion** : Ajouter des options pour supprimer ou modifier les transactions

5. **Affichage des transactions** :
   - **Problème** : L'affichage des transactions manque de logique
   - **Suggestion** : Organiser les transactions par date, catégorie ou montant pour une meilleure lisibilité

6. **Affichage des informations de transaction** :
   - **Problème** : Les informations enregistrées (description par exemple) ne sont pas affichées
   - **Suggestion** : Afficher toutes les informations de la transaction sur la page

7. **Bouton de fermeture de la modal** :
   - **Problème** : Le bouton de fermeture de la modal est trop petit et peu visible
   - **Suggestion** : Agrandir le bouton de fermeture de la modal et le rendre plus visible

## Catégories
1. **Suppression de catégorie non instantanée** :
   - **Problème** : La suppression d'une catégorie nécessite de basculer sur un autre onglet
   - **Suggestion** : Rendre la suppression de catégorie instantanée

2. **Accès aux détails des transactions par catégorie** :
   - **Problème** : Cliquer sur une catégorie ne permet pas d'accéder aux détails des transactions
   - **Suggestion** : Permettre l'accès aux détails des transactions en cliquant sur une catégorie

3. **Clarté de l'ajout de catégorie** :
   - **Problème** : Le processus d'ajout de catégorie manque de clarté
   - **Suggestion** : Simplifier et clarifier le processus d'ajout de catégorie, notamment le choix de la couleur

4. **Lisibilité des limites de budget** :
   - **Problème** : La couleur de la police rend les limites de budget illisibles
   - **Suggestion** : Utiliser des couleurs de police plus lisibles

5. **Limite de budget négative** :
   - **Problème** : Une catégorie peut avoir une limite de budget négative
   - **Suggestion** : Empêcher la saisie de limites de budget négatives

## Payment Methods
1. **Suppression de moyens de paiement** :
   - **Problème** : Impossible de supprimer un moyen de paiement enregistré
   - **Suggestion** : Corriger le bug pour permettre la suppression des moyens de paiement

2. **Accessibilité du bouton de suppression** :
   - **Problème** : Le bouton de suppression d'une catéggorie est trop petit
   - **Suggestion** : Agrandir le bouton de suppression pour le rendre plus accessible.
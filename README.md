# Activité : Formulaire de contact

**20 minutes — En binôme**

Créez un formulaire de contact accessible en appliquant les balises et attributs vus en cours.

## Consignes

1. **En-tête du formulaire** : ajouter un `<h2>` "Contactez-nous" et un `<p>` d'introduction.
2. **Champs obligatoires** : créer un champ "Nom" (`type="text"`) et un champ "E-mail" (`type="email"`), tous deux avec `required` et un `<label>` associé.
3. **Sujet** : ajouter un `<select>` avec au moins 3 options (ex. : "Question générale", "Problème technique", "Autre").
4. **Message** : ajouter un `<textarea>` avec `required` et `rows="4"`.
5. **Bouton d'envoi** : ajouter un `<button type="submit">` avec le texte "Envoyer".
6. **Groupe de champs** : entourer les champs "Nom" et "E-mail" avec `<fieldset>` et `<legend>` "Vos coordonnées".
7. **Validation** : Ajouter un champ "Code postal" avec `minlength="5"` et `pattern="[A-B0-9]{6}"` avec un attribut `title` pour indiquer le format attendu.
8. **Style** : dans `style.css`, appliquer un style de base au formulaire (padding, bordure, espacement entre les champs).
9. **Suggestions avec `<datalist>` (optionnel)** : remplacer le `<select>` de la consigne 3 par un `<input>` couplé à un `<datalist>` proposant les mêmes suggestions, tout en laissant l'utilisateur taper sa propre valeur.
10. Déployer sur github pages et tester sur smarthpone

## Ressources

- [Bases des formulaires — Mozilla Developer Network](https://developer.mozilla.org/fr/docs/Learn_web_development/Core/Form_script_basics)
- [Élément `<input>` — Mozilla Developer Network](https://developer.mozilla.org/fr/docs/Web/HTML/Element/input)

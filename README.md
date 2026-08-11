# Gradeon — informations légales

Site public de la politique de confidentialité et des conditions générales
d'utilisation de l'application mobile Gradeon.

**Ne pas modifier ces fichiers HTML à la main.** Ils sont générés depuis les
textes source de l'application, qui sont la seule version de référence :

    app/assets/legal/{privacy,terms}_{fr,en}.md   (dépôt gradeon-app, privé)

Pour publier une mise à jour, depuis le dépôt de l'application :

    python3 scripts/build_legal_site.py --out <ce dossier>

puis commiter et pousser. La même source alimente l'écran affiché dans
l'application : App Store Connect exige une URL publique, et Apple compare son
contenu à ce que dit l'app.

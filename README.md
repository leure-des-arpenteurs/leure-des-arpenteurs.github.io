# L’Eure des Arpenteurs — site pour GitHub Pages

Export du 16 octobre 2026, avec les dernières modifications du texte Draft, de la section tournois et de la fiche MJC. Les deux boutons Discord utilisent https://discord.gg/J4RfrtKW4V et le QR code n’est plus affiché.

Le site est autonome : HTML, CSS, JavaScript et images. Aucune installation ni compilation n’est nécessaire. Les images n’ont pas été recompressées.

## Remplacer la version en ligne

1. Décompresser le fichier ZIP sur l’ordinateur.
2. Ouvrir le dépôt GitHub qui héberge déjà le site, puis la branche utilisée par GitHub Pages (généralement `main`).
3. Se placer dans le dossier contenant l’actuel `index.html`. Dans la configuration à la racine, c’est la page principale du dépôt.
4. Cliquer sur **Add file → Upload files**.
5. Glisser le contenu du dossier décompressé : `index.html`, `styles.css`, `script.js`, `robots.txt`, `sitemap.xml`, le dossier `assets` et les autres fichiers fournis. Il faut envoyer les fichiers et le dossier `assets` ensemble, pas le ZIP ni le dossier qui les contient.
6. Valider la modification avec un message tel que « Mise à jour du site — 16 octobre 2026 ». Si l’interface propose une branche distincte, fusionner ensuite la demande de modification dans la branche publiée.
7. Attendre la fin du déploiement GitHub Pages dans l’onglet **Actions**, puis actualiser le site.

Les fichiers portant le même chemin remplacent les précédents. Il n’est pas nécessaire de supprimer tout le dépôt ou de reconfigurer GitHub Pages. Conserver les éventuels fichiers de validation Google ou de configuration déjà présents et qui ne sont pas fournis ici.

L’adresse reste : https://leure-des-arpenteurs.github.io/

Si l’ancienne présentation apparaît encore après le déploiement, faire une actualisation forcée : Cmd + Maj + R sur Mac, ou Ctrl + F5 sous Windows.

## Modifier le site plus tard

- `index.html` : textes, liens, rubriques et métadonnées de référencement.
- `styles.css` : couleurs, tailles, espacements et adaptation aux écrans mobiles.
- `script.js` : menu mobile et animations d’apparition.
- `assets/` : logos, illustrations et photographies.
- `robots.txt` et `sitemap.xml` : fichiers utilisés par les moteurs de recherche.

Les éléments de référencement sont déjà configurés pour https://leure-des-arpenteurs.github.io/. Si l’adresse change à l’avenir, mettre à jour cette adresse dans `index.html`, `robots.txt` et `sitemap.xml`.

Chaque modification validée sur GitHub reste dans l’historique du dépôt. Garder également une copie de l’ancien ZIP permet de retrouver facilement une version précédente.

Documentation GitHub : https://docs.github.com/en/repositories/working-with-files/managing-files/adding-a-file-to-a-repository

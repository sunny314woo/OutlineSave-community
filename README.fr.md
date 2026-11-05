**Langues :** [Français](./README.fr.md) · [English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [日本語](./README.ja.md)

# OutlineSave — ChatGPT Outline, Search & Export to HTML & PDF (édition communautaire)

OutlineSave est une extension de navigateur qui facilite la navigation, la recherche, l'annotation et l'exportation de longues conversations avec une IA. Elle permet de transformer les échanges en contenu structuré, facile à retrouver et à conserver, sans faire défiler indéfiniment l'historique.

Ce dépôt contient une **ancienne démonstration ChatGPT aux fonctions limitées, dont le code source est consultable**. Il ne contient pas le code complet de l'extension commerciale actuelle et ne reflète pas nécessairement sa dernière version. L'extension OutlineSave complète est distribuée séparément sur le Chrome Web Store.

**[Installer OutlineSave depuis le Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[Explorer la démo interactive de l'export HTML](https://wisteriasoftware.uk/demo)** · **[Découvrir le produit](https://wisteriasoftware.uk/outline-pro)**

![Démonstration communautaire de ChatGPT Outline](./jump-ezgif.com-crop.gif)

> **Limite de la démo communautaire :** seuls les 15 premiers éléments du sommaire permettent de naviguer. La recherche, les annotations, l'exportation et les autres fonctions présentées ci-dessous appartiennent à l'extension OutlineSave complète, à installer séparément.

## Ce que propose la démonstration communautaire

- Un sommaire cliquable des conversations ChatGPT
- Une actualisation automatique lorsque la conversation s'allonge
- Une barre latérale positionnable à gauche ou à droite
- Une démonstration simple de la navigation dans une conversation

La limite des 15 éléments navigables s'applique **uniquement à cette démo**, et non à l'extension complète OutlineSave.

## Découvrir l'extension OutlineSave complète

La version complète prend en charge les conversations sur **ChatGPT, Gemini, Claude et DeepSeek**. Les fonctions et les interactions peuvent varier selon la plateforme.

### ChatGPT Outline : un sommaire à deux niveaux pour les longues conversations

Les questions de l'utilisateur constituent le premier niveau et les titres des réponses de l'IA le second. Recherchez un titre dans le sommaire, puis accédez à l'endroit correspondant sans parcourir chaque message.

Pour les conversations ChatGPT très longues, le sommaire peut se charger progressivement. Le délai et l'exhaustivité dépendent de la plateforme et de la conversation.

### Search : retrouver le bon passage

Recherchez les questions et les titres de réponses dans le sommaire de la conversation en cours. Après exportation au format HTML, recherchez également des mots et passages dans l'intégralité du texte enregistré.

### Export to HTML : conserver une page de connaissances hors ligne

Exportez une conversation dans un fichier HTML autonome et adaptatif. Ouvrez-le localement sans revenir sur ChatGPT ni attendre le chargement de l'historique d'origine.

L'export HTML peut conserver :

- Le sommaire et la navigation dans la conversation
- La recherche en texte intégral
- Les surlignages, soulignements, notes et favoris existants
- Les filtres par favoris et par couleur de surlignage
- Les blocs de code, formules mathématiques et diagrammes Mermaid

**[Essayer la démonstration interactive de l'export HTML](https://wisteriasoftware.uk/demo)**

### Export PDF

L'exportation PDF est actuellement en cours de développement. **Elle n'est pas encore incluse dans la version publiée sur le Chrome Web Store** à la date de cette mise à jour. Consultez la [fiche du Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj) pour connaître les fonctions disponibles.

### Surlignages, notes, favoris, Markdown et JSON

La version complète permet de surligner avec quatre couleurs, de souligner du texte, d'ajouter des notes et de marquer des passages importants. Elle propose également l'exportation Markdown et JSON.

### Traitement local des conversations par défaut

OutlineSave traite le contenu des conversations localement par défaut et n'envoie pas leur texte aux serveurs de Wisteria Software. Aucun compte OutlineSave n'est nécessaire. Certaines données d'activation et de fonctionnement peuvent être traitées pour gérer les licences et le service. La sauvegarde facultative vers Google Drive est déclenchée par l'utilisateur et enregistre les données sélectionnées dans son propre espace. Consultez la [Politique de confidentialité](https://wisteriasoftware.uk/privacy).

### Option : organiser ses contenus avec Inbox Local

[Inbox Local](https://github.com/sunny314woo/wisteria-suite/tree/main/apps/inbox-local) est une application distincte de gestion des connaissances, conçue pour un stockage local. Elle peut organiser les fichiers Markdown et HTML enrichi exportés depuis OutlineSave. Elle ne fait pas partie de cette démo communautaire.

## Démo communautaire et extension OutlineSave complète

| Fonction | Démo de ce dépôt | OutlineSave complet |
|---|---|---|
| Sommaire des conversations ChatGPT | Oui | Oui |
| Navigation par clic | 15 premiers éléments seulement | Sommaire complet |
| Sommaire à deux niveaux | Non | Oui |
| Recherche dans les titres du sommaire | Non | Oui |
| Recherche intégrale dans le HTML exporté | Non | Oui |
| Surlignages, soulignements, notes et favoris | Non | Oui |
| Export HTML hors ligne | Non | Oui |
| Export Markdown et JSON | Non | Oui |
| Prise en charge de Gemini, Claude et DeepSeek | Non | Oui |
| Export PDF | Non | En développement ; vérifier la boutique |

## Questions fréquentes

### Comment ajouter un sommaire à une longue conversation ChatGPT ?

Installez l'extension OutlineSave complète depuis le [Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj). La démo de ce dépôt se limite à 15 éléments navigables.

### Peut-on rechercher dans une conversation ChatGPT ?

L'extension complète permet de rechercher les titres du sommaire de la conversation. Après exportation en HTML, vous pouvez aussi rechercher dans le texte intégral enregistré.

### Peut-on exporter ChatGPT vers un fichier HTML hors ligne ?

Oui. L'extension complète produit un fichier HTML autonome et adaptatif conservant le sommaire, la recherche intégrale et les annotations existantes compatibles. Vous pouvez l'ouvrir localement sans charger ChatGPT.

### OutlineSave envoie-t-il mes conversations à ses serveurs ?

Par défaut, le texte des conversations est traité localement et n'est pas envoyé aux serveurs de Wisteria Software. La sauvegarde facultative et les services de fonctionnement ont des traitements de données distincts : consultez la [Politique de confidentialité](https://wisteriasoftware.uk/privacy).

### OutlineSave est-il gratuit ?

L'extension complète propose des fonctions gratuites ainsi que des offres d'essai et des licences payantes. Les quotas d'exportation et les conditions peuvent évoluer : consultez la [page officielle](https://wisteriasoftware.uk/outline-pro).

### Peut-on lire le HTML exporté sur un téléphone ?

Oui. Le fichier HTML adaptatif peut être transféré sur un téléphone et ouvert dans un navigateur compatible, sans recharger la conversation ChatGPT d'origine.

## Exécuter la démonstration communautaire en local

1. Ouvrez **chrome://extensions** dans Chrome.
2. Activez le **mode développeur**.
3. Cliquez sur **Charger l'extension non empaquetée**.
4. Sélectionnez le dossier de ce dépôt.

## Licence et accès au code source

Ce dépôt est une **démonstration communautaire dont le code source est consultable**, soumise à la licence personnalisée [LICENSE](./LICENSE), **et non aux licences MIT ou Apache-2.0**. L'accès au code de cette démo ne confère aucun droit sur l'extension commerciale, la marque, les services de serveur ou d'autres éléments propriétaires. Voir [NOTICE](./NOTICE).

**[Installer OutlineSave depuis le Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[Explorer la démo interactive de l'export HTML](https://wisteriasoftware.uk/demo)**

**Langues :** [Français](./README.fr.md) · [English](./README.md) · [简体中文](./README.zh-CN.md) · [Español](./README.es.md) · [日本語](./README.ja.md)

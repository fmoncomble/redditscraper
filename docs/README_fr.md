![redditscraper_banner](https://github.com/fmoncomble/redditscraper/assets/59739627/41697339-9b63-48e2-a2ab-e9d0c39baeb1)

[(English version)](https://fmoncomble.github.io/redditscraper)

Une extension pour extraire et télécharger des posts Reddit à des fins de fouille textuelle.  
  
### Citer ce programme
Si vous utilisez cette extension pour votre recherche, veuillez la référencer comme suit :  
  
Moncomble, F. (2024). *RedditScraper* (Version 0.4) [JavaScript]. Arras, France : Université d'Artois. Disponible à l'adresse : https://fmoncomble.github.io/redditscraper/

## Installation
### Firefox
[ ![Firefox add-on](https://github.com/fmoncomble/Figaro_extractor/assets/59739627/e4df008e-1aac-46be-a216-e6304a65ba97)](https://github.com/fmoncomble/redditscraper/releases/latest/download/redditscraper.xpi)  

### Chrome/Edge
[![available-chrome-web-store4321](https://github.com/fmoncomble/redditscraper/assets/59739627/dad5ba48-c049-4b76-8d37-cd1a01ba4107)](https://chromewebstore.google.com/detail/redditscraper/pleejhomflbkocjhlpipghkgmoafpnok)
  
N'oubliez pas d'épingler l'extension à la barre d'outils.
 
## Mode d'emploi
- Cliquez sur l'icône de l'extension dans la barre d'outils.
- Lors de la première utilisation, suivez la procédure d'authentification pour autoriser l'application sur Reddit. *Tous les identifiants sont stockés en local sur votre ordinateur, **pas** sur un serveur distant.*
- Construisez votre requête avec au moins un mot clef, puis cliquez sur `Search`.
- Choisissez le format de sortie désiré :
    - `XML/XTZ` pour un fichier XML à importer dans [TXM](https://txm.gitpages.huma-num.fr/textometrie/en/index.html) en utilisant le module `XML/TEI-Zero`.
        - Lors de l'import, ouvrez la section "Plans textuels" et entrez `ref` dans le champ « Hors texte à éditer »
    - `TXT` pour du texte brut
    - `CSV`
    - `XLSX` (tableau Excel)
    - `JSON`
- (Facultatif) Entrez un nombre maximum de posts à récupérer.
- Vous pouvez arrêter l'extraction à tout moment en cliquant sur `Abort`.
- Cliquez sur `Download` pour collecter le résultat, ou `Reset` pour reprendre au début.

## Limites connues
L'API de recherche Reddit ne renvoie qu'une sélection de résultats.

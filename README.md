
# **Annexe numérique du mémoire de Master 1 Humanités numériques**

---

## **Ecole nationale des chartes - PSL**

## **Cadrage discursif thématique des interviews ministérielles : Influence de l’alignement politique entre média et ministre**

## **Chloé Jollivet-Courtois**

#### **Sous la direction de Thomas Depecker et Florian Cafiero**

---

Cette présente annexe vise à permettre la reproduction de l’analyse déroulée dans le mémoire mentionné.

Après un nettoyage et traitement des données sources issues du site Vie-publique.fr (2025), ces données sont croisées avec celles du *1999-2019 Chapel Hill Expert Survey* (CHES) (Joly et al., 2022) et de la mesure du temps d’antenne des différentes familles politiques dans les médias (Cagé et al., 2022) afin de mesurer les changements de sujets entre chaque prise de parole et la manière dont ces changements de sujets sont influencés par la proximité idéologique entre l’interviewé et le média. Ci-dessous sont présentés les fichiers des données mobilisées dans les codes, puis les fichiers codes et enfin les fichiers obtenus en sortie des codes.

---

## **Fichiers données :**

- **Données sources issues de Vie-publique.fr,  un site “édité par la Direction de l'information légale et administrative” (Vie publique, 2025) :**
  - Viepublique1.csv
  - Viepublique2.csv
  - Viepublique3.csv
  - Viepublique4.csv
  - Viepublique5.csv

- **Données contenant l’information du nombre d’intervenant pour chaque interview (pour effectuer un tri) :**
  - nb_intervenant_FillonII.csv
  - nb_intervenant_AyraultII.csv
  - nb_intervenant_VallsII.csv

- **Données sur l’orientation politiques des partis politiques, issues du *1999-2019 Chapel Hill Expert Survey* (CHES) (Joly et al., 2022) :**
  - 1999-2019_CHES_dataset_means.csv

- **Données sur le temps d’antenne des différentes familles politiques par média, issues de l’article Cagé et. al (2022) :**
  - clean_biais_medias.csv

---

## **Fichiers codes :**

- **Mesure biais médias (Calcul orientation politique des familles politiques françaises, calcul orientation politiques des médias en fonction du temps d’antennes des différentes familles politiques françaises) par les données CHES et les données Cagé et al. (2022) :** Biais_medias.ipynb
- **Prétraitement des données de Vie-publique.fr :** Prétraitement_scraping.ipynb
- **Nettoyage, traitement et analyse des données de Vie-publique.fr (LDA, J-S divergence, graphiques) :** Analyse_donnees.ipynb

---

## **Fichiers output des codes :**

- **Concaténation des fichiers issus de Vie-publique.fr suite à un prétraitement :** csv_vie_publique.csv
- **Score d’orientation politique des principaux médias français :** score_media.csv

---

## **Les codes doivent être lancés dans l’ordre suivant :**

- Biais_medias.ipynb
- Prétraitement_scraping.ipynb
- Analyse_donnees.ipynb

---

## **Sources :**

- Cagé, J., Hengel, M., Hervé, N., & Urvoy, C. (2022). Hosting media bias: Evidence from the universe of French broadcasts, 2002-2020. HAL. [https://hal.science/hal-03878119](https://hal.science/hal-03878119)
- Direction de l’information légale et administrative. (s.d.). Collection Discours publics. Vie-publique.fr. Consulté le 26 mai 2025, à l’adresse [https://www.vie-publique.fr/collection-discours-publics](https://www.vie-publique.fr/collection-discours-publics)
- Jolly, S., Bakker, R., Hooghe, L., Marks, G., Polk, J., Rovny, J., Steenbergen, M., & Vachudova, M. A. (2022). Chapel Hill Expert Survey trend file, 1999–2019. Electoral Studies, 75, 102420. [https://doi.org/10.1016/j.electstud.2021.102420](https://doi.org/10.1016/j.electstud.2021.102420)

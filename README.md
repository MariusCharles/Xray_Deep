# X-Ray Detector Calibration – Inflexion Point Estimation

Ce dépôt contient les méthodes et le code développés dans le cadre du challenge  
**Soleil – X-Ray Detector Calibration**, proposé lors du Datacamp 2025 de l’Institut Polytechnique  
([Codabench – Competition 12117](https://www.codabench.org/competitions/12117/)).

L’objectif du challenge est d’estimer l’abscisse du point d’inflexion d’une courbe bruitée, utilisée pour la calibration d’un détecteur de rayons X. Les méthodes proposées visent à être robustes en généralisation, l’évaluation étant réalisée sur des domaines énergétiques différents de ceux vus à l’entraînement.

---

##  Contenu du projet

Ce dépôt présente plusieurs approches :

- **Approche analytique**  
  Basée sur l’analyse de la dérivée de la courbe, avec lissage et détection du minimum.
- **Approche Deep Learning**  
  Modèles neuronaux (RNN / CNN) exploitant la structure séquentielle des données.
- **Approche hybride**  
  Combinaison d’un modèle appris et d’opérations analytiques différentiables.

Le notebook principal contient :
- l’exploration des données,
- la description des méthodes,
- les visualisations,
- les résultats expérimentaux.

---


##  Données du challenge

Les données utilisées dans ce projet **ne sont pas incluses dans ce dépôt**.

Elles font partie d’un challenge Codabench et sont soumises à des conditions d’utilisation spécifiques définies par les organisateurs. Toute redistribution des données brutes est interdite.

Pour exécuter le code, veuillez télécharger les données directement depuis la page officielle du challenge :

 https://www.codabench.org/competitions/12117/

---

##  Reproductibilité

Une fois les données téléchargées depuis Codabench et placées localement, le notebook peut être exécuté sans modification majeure.  
Les chemins d’accès aux données devront être adaptés à votre environnement.



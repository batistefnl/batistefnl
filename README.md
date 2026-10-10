<p align="center">
  <img src="assets/banner.svg" alt="Batiste Fancellu · Élève ingénieur ISAE-SUPAERO · IA, science des données & robotique" width="100%"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/batistefancellu">LinkedIn</a> ·
  <a href="mailto:batiste.fancellu@student.isae-supaero.fr">Email</a> ·
  Français · English · Español
</p>

Élève ingénieur à **ISAE-SUPAERO**, filière *Science de la donnée et de la décision*.
J'aime prendre un problème concret, aller chercher les données moi-même et voir jusqu'où un modèle tient face au réel.
J'ai fait de l'estimation d'état apprise pour un robot humanoïde au **LAAS-CNRS**, puis des agents IA et de l'infrastructure Azure chez **Clayens**.
Ici, ce sont mes projets personnels, chacun avec ses résultats et ses limites.

## Projets

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/batistefnl/outcome-switch-monitor">Outcome Switch Monitor</a></h3>
      <p><b>Les essais cliniques mesurent-ils ce qu'ils avaient annoncé ?</b> Sur 5 634 essais de phase 3, environ <b>un sur trois</b> change le fond de son critère principal entre l'enregistrement et les résultats.</p>
      <p>Historique récupéré dans la Wayback Machine, 95 essais annotés à la main en double aveugle, puis un LLM validé contre ces annotations (kappa 0,73) classe le reste pour 3 $.</p>
      <p><sub>Python · LLM (OpenRouter) · statsmodels · JS · Playwright · hackathon HSIL 2026, équipe de 4</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/batistefnl/outcome-switch-monitor"><img src="https://raw.githubusercontent.com/batistefnl/outcome-switch-monitor/main/demo/media/explore-light.png" alt="Démo Outcome Switch Monitor"/></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/batistefnl/velotoulouse">Vais-je trouver un vélo ?</a></h3>
      <p><b>Ma station VélôToulouse est souvent vide quand j'arrive.</b> J'ai relevé les 383 stations toutes les 15 minutes pendant trois mois avec un <a href="https://github.com/batistefnl/velotoulouse-collecteur">collecteur sur Raspberry Pi</a>.</p>
      <p>Gradient boosting calibré pour P(≥ 2 vélos) à 15, 30 et 60 min, qui bat la persistance de 4,6 à 7 % (score de Brier). Effet de la pluie : −17 % d'activité, avec effets fixes et test placebo.</p>
      <p><sub>Python · scikit-learn · pandas · Streamlit · Raspberry Pi · pytest</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/batistefnl/velotoulouse"><img src="https://raw.githubusercontent.com/batistefnl/velotoulouse/main/figures/carte_matin.png" alt="La vague du matin sur le réseau VélôToulouse"/></a>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/batistefnl/canicule-salon-2019">Canicule de 2019 à Salon-de-Provence</a></h3>
      <p><b>43,4 °C le 28 juin 2019 : à quel point est-ce rare ?</b> Environ une fois tous les <b>80 ans</b> dans le climat actuel, contre des dizaines de milliers d'années dans celui de 1950.</p>
      <p>Loi GEV non stationnaire codée à la main (vraisemblance, bootstrap paramétrique), avec une analyse du biais de sélection lié au choix de l'événement.</p>
      <p><sub>Python · SciPy · valeurs extrêmes · GitHub Actions</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/batistefnl/canicule-salon-2019"><img src="https://raw.githubusercontent.com/batistefnl/canicule-salon-2019/main/figures/niveaux_retour.png" alt="Niveaux de retour, climat de 1950 contre climat de 2025"/></a>
    </td>
  </tr>
</table>

## Parcours

| | |
|:--|:--|
| **2026** · Clayens Group | Stage R&D IA & cloud. Organisation du **Jurassic'Hack**, premier hackathon IA du groupe (60+ participants, 5 POC dont 3 en industrialisation), infra Azure de 60+ VM, API FastAPI conteneurisée, agents Copilot Studio et RAG |
| **2025** · Universidad Nacional de Colombia | Échange à Bogotá, spécialisation en techniques d'IA |
| **2025** · LAAS-CNRS | Stage de recherche. Sim-to-Real pour l'estimation d'état de l'humanoïde **Unitree H1v2** : 40 M d'échantillons générés sous Isaac Lab, réseau résiduel en PyTorch entraîné sur A100/H100, validé en motion capture |
| **2024** · Airbus Helicopters | Stage au département prototypes : essais moteur au point fixe |
| **2023 →** · ISAE-SUPAERO | Cycle ingénieur, filière Science de la donnée et de la décision |

## Outils

**ML** : PyTorch, scikit-learn, Hugging Face, apprentissage par renforcement, LLM, RAG, fine-tuning (LoRA)<br>
**Données** : NumPy, pandas, SciPy, SQL, traitement du signal<br>
**Ingénierie** : Python, C, Docker, FastAPI, Linux, SLURM, Git, GitHub Actions<br>
**Cloud & simulation** : Microsoft Azure, NVIDIA Isaac Lab / Isaac Sim

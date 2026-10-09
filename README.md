<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:2563EB&height=210&section=header&text=Mohamed%20Ali%20Chaoui&fontSize=40&fontColor=FFFFFF&fontAlignY=38&desc=MACHINE%20LEARNING%20%20%7C%20%20RAG%20%26%20NLP%20%20%7C%20%20ING%C3%89NIERIE%20IA&descSize=14&descAlignY=59" alt="Mohamed Ali Chaoui — Machine Learning, RAG & NLP, Ingénierie IA" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=3000&pause=1200&color=2563EB&center=true&vCenter=true&width=650&height=55&lines=Du+g%C3%A9nie+logiciel+%C3%A0+l'Intelligence+Artificielle.;RAG+from+scratch+%7C+IA+D%C3%A9cisionnelle+%7C+Recherche+Vectorielle.;Des+notebooks+aux+syst%C3%A8mes+de+production." alt="Du génie logiciel à l'Intelligence Artificielle. RAG from scratch | IA Décisionnelle | Recherche Vectorielle." />

**Étudiant en Master Informatique · Parcours Intelligence Artificielle**  
Université de Bordeaux · Bordeaux, France 📍

<a href="https://portfolio-chaoui-mohamed-ali.vercel.app/">
  <img src="https://img.shields.io/badge/Portfolio-D%C3%A9couvrir_mes_projets-2563EB?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio" />
</a>
<a href="https://www.linkedin.com/in/mohamed-ali-chaoui-25151b196/">
  <img src="https://img.shields.io/badge/LinkedIn-Me_contacter-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<a href="https://mohamedalichaoui.github.io/Amazons-game/">
  <img src="https://img.shields.io/badge/Amazons_IA-D%C3%A9mo_en_ligne-10B981?style=for-the-badge&logo=githubpages&logoColor=white" alt="Démo Jeu des Amazones" />
</a>

</div>

---

### 👋 À propos

Étudiant en **Master Intelligence Artificielle** à l'Université de Bordeaux, je combine un solide socle en ingénierie logicielle et une spécialisation approfondie en **Machine Learning, RAG (Retrieval-Augmented Generation) et algorithmique avancée**.

Issu d'une formation rigoureuse en développement (Python, C/C++, Java), je conçois des systèmes d'IA de bout en bout **from scratch** (sans frameworks wrappers de type LangChain), afin de maîtriser chaque étape du pipeline : parsing HTML/DOM sémantique, retrieval hybride (lexical + dense) et génération ancrée sans hallucination.

🎯 **Recherche active** : Stage de fin d'études de **6 mois dès mars 2027** en **Machine Learning / Ingénierie IA / NLP** (mobile dans toute la France).

---

### 🧠 Stack & Compétences

<p align="center">
  <img src="https://img.shields.io/badge/Python_3.13-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn" />
  <img src="https://img.shields.io/badge/PostgreSQL_(pgvector)-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C/C++" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
</p>

| Domaine | Méthodes & Réalisations concrètes |
| :--- | :--- |
| **RAG & NLP Scientifique** | Retrieval Hybride (BM25 Lucene + Bi-Encoder BGE), chunking sémantique isolé, citations vérifiables au paragraphe |
| **IA Décisionnelle & Jeux** | Recherche arborescente Monte-Carlo (MCTS), Minimax avec élagage Alpha-Bêta ($\alpha$-$\beta$), évaluation neuronale |
| **Indexation & Similarité** | Recherche vectorielle par *embeddings*, bases vectorielles (pgvector), k-NN, distance cosinus matricielle NumPy |
| **Optimisation & Algorithmique** | Heuristiques pour le TSP (voyageur de commerce), solveurs SAT, bitboards, complexité algorithmique |
| **Ingénierie & Rigueur MLOps** | Conception modulaire *from scratch*, intégrité cryptographique SHA-256, tests unitaires/intégration (`pytest`), CI/CD |

---

### 🚀 Projets Clés & Démos

#### 🔬 End-to-End Scientific RAG · Production-Grade Hybrid Retrieval (2026)

Système RAG modulaire conçu **from scratch** (sans LangChain ni LlamaIndex) pour la recherche documentaire haute précision sur 300 articles de recherche récents d'arXiv (16 310 passages).

- **Data Engineering & Parsing HTML** : Extraction DOM sur rendus HTML officiels d'arXiv (LaTeXML) avec préservation de la hiérarchie sémantique, des tableaux et formules. **Couverture textuelle validée à 100,00 %** par test d'intégrité de multiensemble de 8-grammes.
- **Retrieval Lexical BM25 (< 1 ms)** : Implémentation `bm25s` (Lucene) avec tokenizer scientifique préservant les termes techniques et métriques.
- **Retrieval Dense Vectoriel (< 10 ms)** : Inférence CPU pure en NumPy avec le Bi-Encoder `BAAI/bge-small-en-v1.5` (matrice compacte de 24 Mo en RAM) et checkpoints de reprise sans recalcul.
- **Citations vérifiables & Répétabilité** : Citations ancrées au paragraphe source (`#section_id`), empreintes SHA-256 des index et suite de tests automatisée sous `pytest`.

**`Python 3.13` `PyTorch` `Hugging Face` `BGE-small` `BM25` `NumPy` `BeautifulSoup4` `pytest`**

<br>

#### ♟️ IA Décisionnelle & Deep Learning · Jeu des Amazones (2026)

Moteur complet pour le jeu des Amazones doté d'une IA combinant exploration arborescente et apprentissage profond.

- **IA Hybride** : Recherche combinatoire combinant **MCTS** et **Minimax ($\alpha$-$\beta$)**.
- **Évaluation neuronale** : Entraînement d'un réseau de neurones sous **Keras** pour l'estimation de positions complexes.
- **Optimisation bas niveau** : Représentation par **bitboards** pour maximiser le débit d'évaluation, multijoueur asynchrone avec **asyncio**.

**`Python` `Keras` `MCTS` `Minimax α-β` `Bitboards` `asyncio`**

→ **[Tester la démo en ligne](https://mohamedalichaoui.github.io/Amazons-game/)**

<br>

#### 🌌 Le Voyageur de Commerce Intersidéral · Inria / CAP IA (2026)

Contribution au serious game du projet **CAP IA** visant à sensibiliser aux défis de l'optimisation mathématique et de l'IA.

- Implémentation et optimisation d'heuristiques pour le **problème du voyageur de commerce (TSP)**.
- Refonte complète et optimisation de l'architecture backend de **Java (Spring Boot) vers Python (Flask)**.

**`Python` `Flask` `Heuristiques TSP` `Optimisation` `Spring Boot`**

→ **[Accéder au serious game](https://campus-ia.u-bordeaux.fr/voyageur-de-commerce/)**

<br>

#### 🔍 Recherche d'Images par Similarité Vectorielle (2024)

Moteur de recherche sémantique basé sur des représentations vectorielles d'images.

- Indexation d'**embeddings** via **PostgreSQL et l'extension pgvector**.
- Recherche des plus proches voisins (**k-NN**) avec calcul de distance cosinus en temps réel et API REST **Spring Boot**.

**`pgvector` `Embeddings` `PostgreSQL` `Spring Boot` `Vue.js`**

→ **[Tester l'application](https://similarity-pic.vercel.app/)**

<br>

#### 🧩 Raisonnement Automatique & Solveur SAT (2025)

Modélisation et résolution formelle de problèmes NP-complets.

- Réduction polynomiale vers le problème **SAT** (IA symbolique).
- Conception et implémentation d'un solveur en **C** avec gestion stricte de la mémoire et benchmarks de performance.

**`Langage C` `IA Symbolique` `Solveur SAT` `Théorie de la Complexité`**

---

### 🤝 Échangeons

Une question sur mes projets, un échange technique ou une opportunité de stage de fin d'études en IA ?

- 🌐 **Portfolio en ligne :** [portfolio-chaoui-mohamed-ali.vercel.app](https://portfolio-chaoui-mohamed-ali.vercel.app/)
- 💼 **LinkedIn :** [linkedin.com/in/mohamed-ali-chaoui](https://www.linkedin.com/in/mohamed-ali-chaoui-25151b196/)
- 📧 **Email :** [ali.chaoui.123@gmail.com](mailto:ali.chaoui.123@gmail.com)

<div align="center">

<br>

*Allier rigueur logicielle, modélisation intelligente et systèmes de production.*

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:1E3A8A,100:2563EB&height=100&section=footer" alt="" />

</div>

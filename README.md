# Clément Reboul

Ingénieur IA, développeur Python / FastAPI et Vue / Nuxt, sapeur-pompier volontaire. Paris.

Je construis des outils IA concrets pour des PME et des équipes métier : backends Python/FastAPI,
pipelines data et LLM, interfaces Vue/Nuxt, livrés testés, documentés et déployés.

Cinq ans de développement web fullstack puis une formation d'ingénieur IA dont viennent les
projets ci-dessous.

## Projets publics

- [credit-scoring-mlops](https://github.com/clementRbl/credit-scoring-mlops) : un modèle de
  scoring crédit en production sur Hugging Face. Chaque lundi un workflow surveille la dérive,
  réentraîne un challenger et propose sa mise en production dans une Pull Request qu'un humain
  valide. Sur le scénario simulé le challenger promu fait baisser le coût métier de 8,1 %.
  [API en ligne](https://clementrbl-credit-scoring-api.hf.space/docs).
- [agent-ia-triage-medical](https://github.com/clementRbl/agent-ia-triage-medical) : une preuve
  de concept de triage aux urgences par un modèle de 1,7 milliard de paramètres spécialisé par
  fine-tuning (SFT + LoRA puis DPO). 31 urgences vitales sur 31 identifiées sur le jeu de test et
  0 réponse hors format. Servi par vLLM derrière FastAPI avec des données anonymisées et documentées.
- [ffe-chess-openings-agent](https://github.com/clementRbl/ffe-chess-openings-agent) : un agent
  LangGraph qui aide de jeunes joueurs à apprendre les ouvertures d'échecs. Il combine les coups
  des maîtres (Lichess), le moteur Stockfish, un RAG sur des fiches d'ouvertures (Milvus) et des
  vidéos explicatives. Échiquier Angular, le tout lancé par Docker Compose.
- [pull-events](https://github.com/clementRbl/pull-events) : Puls-Events, un chatbot RAG qui
  recommande des événements culturels d'Île-de-France à partir de l'API Open Agenda. LangChain,
  Faiss, Mistral et FastAPI, évalué avec Ragas.
- [review-pilot](https://github.com/clementRbl/review-pilot) : ReviewPilot, un pipeline progressif
  sur des avis clients, du classifieur de sentiment au MLOps. Première brique en cours, un
  classifieur qui signale les avis négatifs au service client. Baseline suivie dans MLflow.

## En production, code privé

- IRAX lit la boîte mail d'une agence immobilière, classe chaque demande chaud / tiède / froid avec
  le motif et affiche les prospects à rappeler en premier. Python, FastAPI, PostgreSQL, Mistral, Nuxt.
- Veille IA lit 29 sources chaque matin, regroupe les doublons, résume sous double contrôle
  anti-hallucination et dépose un brouillon d'article sur mon blog. En production tous les jours
  pour moins d'un euro par mois de modèles.

## Ailleurs

- Blog : [clement-reboul.fr](https://clement-reboul.fr), un article par jour sur l'IA appliquée.
- Portfolio : [clementrbl.github.io/portfolio](https://clementrbl.github.io/portfolio/), avec les
  captures des projets et une étude de cas détaillée.
- LinkedIn : [linkedin.com/in/clement-reboul](https://www.linkedin.com/in/clement-reboul).

Disponible pour des missions freelance à Paris, en remote ou en hybride. Écrivez-moi sur LinkedIn.

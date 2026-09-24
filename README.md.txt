# Projeto Final — TripleTen Data Science Bootcamp

Entrega final do bootcamp, composta por 3 projetos independentes, todos aprovados pelo revisor.

## 📁 Estrutura

### 1. Caso Principal — CallMeMaybe (`callmemaybe-operadores/`)
Análise de eficiência de operadores do serviço de telefonia virtual CallMeMaybe. Identificação de operadores ineficientes com base em taxa de chamadas perdidas, tempo médio de espera e volume de chamadas ativas, usando limiares por percentil. Testadas 4 hipóteses estatísticas (Mann-Whitney U e qui-quadrado).

- `notebook.ipynb` — análise completa (pré-processamento, EDA, testes de hipótese, métricas de negócio)
- `Relatorio_Final_CallMeMaybe.docx` — relatório final (formato CAR)
- `CallMeMaybe_Apresentacao.pdf` — apresentação dos resultados
- Dashboard: [Tableau Public](https://public.tableau.com/app/profile/murilo.lima.dos.santos/viz/ProjetofinalTripleten_17869971030720/Dashboard?publish=yes)

### 2. Teste A/B — Sistema de Recomendação (`ab-test-recommender/`)
Auditoria e análise do teste A/B `recommender_system_test`, avaliando o impacto de um sistema de recomendação aprimorado nas etapas do funil de conversão (product_page → product_cart → purchase), com testes Z para diferença de proporções.

- `TesteAB.ipynb` — análise completa

### 3. Projeto SQL — Banco de Livros (`sql-livros/`)
5 consultas SQL (PostgreSQL) sobre um banco de dados de livros, avaliações e editoras, incluindo modelagem de dados (PKs, FKs, cardinalidade) e análise de negócio.

- `sqlLivros.ipynb` — consultas e análise

## 🛠️ Stack
Python (pandas, scipy, statsmodels), SQL (PostgreSQL/SQLAlchemy), Tableau Public

## 👤 Autor
Murilo Lima dos Santos — [LinkedIn](https://linkedin.com/in/murilo-lima98)
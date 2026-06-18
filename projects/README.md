# 🚀 Study Projects — Learn in Parallel with Your Study

Reading roadmaps and watching courses is not enough. The fastest way to learn
data and AI skills is to **build small projects in parallel with your study** —
applying each new concept to something real while it is still fresh.

This folder gives you a lightweight structure to do exactly that.

## 🎯 The idea: study ⇄ build loop

```
   ┌─────────────┐      learn a concept       ┌──────────────┐
   │   STUDY     │ ─────────────────────────▶ │    BUILD     │
   │ (reference) │                            │ (mini project)│
   │  roadmaps,  │ ◀───────────────────────── │  apply it on  │
   │  courses    │     questions & gaps       │   real data   │
   └─────────────┘                            └──────────────┘
```

1. **Study** a topic using the [references catalogue](../references/README.md).
2. **Build** a small project that uses that topic (the [template](templates/project-template) makes this quick).
3. **Reflect** — note what was confusing; let that guide your next study session.
4. **Repeat** — each loop is small, finishable, and adds to your portfolio.

## 🗂️ How to organise your projects

Create one folder per project under `projects/`, copied from the template:

```
projects/
├── README.md                       ← you are here
├── templates/
│   └── project-template/           ← copy this to start a new project
└── <your-project-name>/            ← e.g. 01-sales-dashboard
```

Suggested naming: prefix with a number so projects stay ordered by when you
started them, e.g. `01-sales-eda`, `02-etl-weather-pipeline`,
`03-churn-model`, `04-rag-chatbot`.

## ⚡ Start a new project in 3 steps

```bash
# 1. Copy the template (run from the repository root)
cp -r projects/templates/project-template projects/01-my-first-project

# 2. Open its README and fill in the goal + the concept you are studying
cd projects/01-my-first-project

# 3. Work the study ⇄ build loop until the project's "Definition of done" is met
```

> Tip: keep each project **small enough to finish in a few study sessions**.
> A finished tiny project beats an abandoned ambitious one.

## 🧭 Suggested first project per track

| Track | A good first project |
|-------|----------------------|
| 📊 Data Analytics | Explore a public dataset and build a one-page dashboard answering 3 questions. |
| 🛠️ Data Engineering | Build a small ETL pipeline: ingest a CSV/API, clean it, load it into a local database. |
| 🔬 Data Science | Run an end-to-end EDA + baseline model on a Kaggle dataset. |
| 🤖 ML Engineering | Take an existing model and wrap it in an API with experiment tracking. |
| 🧠 AI Engineering | Build a small RAG chatbot over a handful of your own documents. |

Need data? See the [datasets section](../references/cross-cutting.md#-datasets).

## 📐 Why this structure?

The [project template](templates/project-template) follows widely-used
conventions (inspired by
[cookiecutter-data-science](https://github.com/drivendataorg/cookiecutter-data-science)):
separating raw vs. processed data, exploratory notebooks vs. reusable source
code, and keeping a clear project README. Using the same shape for every project
means less setup friction and a portfolio that looks consistent and professional.

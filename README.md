# RAG Chunking Strategies Analysis

Анализ и сравнение 3 стратегий чанкинга текста для систем RAG (Retrieval-Augmented Generation).

## Структура проекта

- `data/` — входные данные для анализа
- `notebooks/` — Jupyter ноутбуки для экспериментов
- `src/` — основные модули
  - `loaders.py` — загрузка и подготовка текста
  - `chunking.py` — реализация стратегий чанкинга
  - `analysis.py` — анализ и сравнение результатов

## Стратегии чанкинга

1. **CharacterTextSplitter** — простое разделение по символам
2. **RecursiveCharacterTextSplitter** — рекурсивное разделение с сохранением контекста
3. **SemanticChunker** — семантическое разделение по смыслу

## Использование

```bash
pip install -r requirements.txt
jupyter notebook
```
# rag_chunking_analysis
# rag_chunking_analysis

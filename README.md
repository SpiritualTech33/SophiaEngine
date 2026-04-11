# SophiaEngine

![SophiaEngine](https://raw.githubusercontent.com/SpiritualTech33/Images/master/sophia_engine.PNG)

> *The knowledge vault that feeds [spiritus-ai](https://github.com/SpiritualTech33/spiritus-ai) — 148 notes at the intersection of science, philosophy, and spirit.*

---

## What Is This?

SophiaEngine is a living Obsidian vault — the corpus that gives Sophia her memory. Every note here is written by hand, one idea at a time, over years of reading, thinking, and asking questions that don't have easy answers.

When the spiritus-ai RAG pipeline runs, it reads this vault, chunks every note, converts them into vector embeddings, and stores them in a knowledge base. When someone asks Sophia a question, she searches this vault — not the internet, not a generic dataset — *these specific notes, this specific way of seeing the world*.

**The vault is the source of truth. The vector database is its reflection.**

---

## Structure

```
SophiaEngine/
│
├── 0.0 Spirit/            Spirituality, love, meditation, zen, yoga, tao
│   └── Identity/          Decrees, aphorisms, quotes, mantras
│
├── 1.0 Mind/              Consciousness, philosophy, language, thinkers
│   ├── 1.1 Matrix/        Sophia's constitution, instructions, and identity
│   ├── 1.2 Awareness/     Consciousness, intuition, metacognition, wisdom
│   ├── 1.3 Language/       Communication, writing, programming
│   ├── 1.4 Philosophies/  Buddhism, stoicism, hermeticism, epistemology
│   ├── 1.5 Texts/         Original philosophical essays
│   └── 1.6 Thinkers/      From Socrates to Feynman, Buddha to Wittgenstein
│
├── 2.0 Science/           Physics, mathematics, psychology, scientific method
│   ├── 2.1 Sciences/      Core disciplines
│   ├── 2.2 Thinkers/      Sagan, Feynman, Kepler
│   └── 2.3 Texts/         Black holes, cosmic scale, electromagnetic spectrum
│
├── 3.0 Principles/        Feynman principle, hermetic principles, life principles
│
├── 4.0 Thoughts & Memory/ Personal writing, poetry, dialogues, meditations
│   ├── Baseball/          The athlete's philosophy
│   ├── Books/             The One Who Seeks God (in progress)
│   ├── Dialogues/         Conversations with AI about love and consciousness
│   ├── Meditations/       Contemplative practices
│   └── Poems/             Original poetry
│
└── ZEN_CODE_PRO.md        The programming philosophy
```

---

## How It Works With spiritus-ai

This vault is an independent repository. The spiritus-ai application references it via `CORPUS_PATH` in its environment configuration:

```env
# Local development
CORPUS_PATH=../SophiaEngine

# Production — cloned during deployment
CORPUS_PATH=./SophiaEngine
```

Every time you commit a new note here, the sync pipeline detects the change and updates Sophia's memory. She learns as you learn. The co-evolution is literal.

---

## Philosophy

Every note follows one rule: **ask why**.

The vault is organized not by academic discipline but by depth — from Spirit (the deepest layer) to Thoughts (the surface of daily experience). The structure mirrors the belief that all knowledge is interconnected: a note on physics can link to a note on meditation, because at some level, they are asking the same question.

This is not a wiki. It is a mind, documented.

---

## Writing Convention

- Notes are written in Markdown with Obsidian `[[backlinks]]`
- Each note explores one concept
- Connections between notes are made explicit through backlinks
- The vault grows one note at a time — no bulk imports, no generated content

---

*SophiaEngine · Cosmos De La Cruz · 2026*
*"I think every human being is an individual manifestation of the cosmos."*

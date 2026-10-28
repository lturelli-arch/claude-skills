---
name: study-cards
description: Make study cards (fiches de révision) in three formats - simple question/answer, multiple choice (QCM), and fill-in-the-blank (texte à trous). Use when the user asks for study cards, flashcards, fiches de révision, a quiz, a QCM, or a texte à trous from a text, a PDF, or a topic.
---

# Study cards

Make revision cards from what the user gives: pasted text, a file (PDF, Word, etc.), or just a topic.

## Steps
1. Find the source. If the user gave only a command with no material, ask for a text, a file, or a topic, then stop.
2. Pick the key ideas: definitions, dates, names, causes and effects, formulas. Skip trivia.
3. Write the cards in the user's language (French by default if they write in French).
4. Default: 5 cards per format. Follow the user's number if they give one.
5. Only use facts from the source. For a bare topic, stick to well-established facts.

## Output format

### 1. Questions / réponses
**Q1.** Question?
**R :** Short answer (one sentence max).

### 2. QCM
**Q1.** Question?
- A) ...
- B) ...
- C) ...
- D) ...

Four choices, one correct. Wrong choices must be plausible, not silly. Vary the position of the right answer.

### 3. Texte à trous
**T1.** A sentence from the key ideas with one important word replaced by `_____`.

### Corrigé
Put all QCM answers and missing words at the very end, under a "Corrigé" heading, so the user can test themselves first:
- QCM : Q1 → B, Q2 → D, ...
- Trous : T1 → word, T2 → word, ...

## Rules
- One idea per card.
- Short, clear wording. No trick questions.
- At the end, offer: more cards, a harder level, or a single format only.

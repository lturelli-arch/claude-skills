---
name: study-exam
description: Make a practice exam (examen blanc) from a text, a file, or a topic, then grade the user's answers out of 20 with corrections. Use when the user asks for an exam, an examen blanc, a test, a contrôle, or wants to be tested and graded on a subject.
---

# Study exam

Two phases: give the exam, then grade it. Never show the answers in phase 1.

## Phase 1 - Give the exam
1. Find the source: pasted text, a file (PDF, Word, etc.), or a topic. If there is none, ask for one and stop.
2. Write in the user's language (French by default if they write in French).
3. Build an exam out of 20 points, with these sections:
   - **Partie 1 - QCM** (5 questions, 1 pt each): 4 choices, one correct.
   - **Partie 2 - Questions courtes** (5 questions, 1 pt each): answer in one or two sentences.
   - **Partie 3 - Texte à trous** (5 blanks, 1 pt each): use `_____`.
   - **Partie 4 - Question de réflexion** (5 pts): one open question that asks to explain or connect ideas, in a short paragraph.
4. Show the points next to each part and suggest a time limit (about 30 minutes).
5. End with: "Répondez à toutes les questions dans un seul message (ex : 1-B, 2-D…). Je corrigerai ensuite."
6. Stop and wait for the answers.

## Phase 2 - Grade
When the user sends their answers:
1. Grade each question. Give partial credit on short answers and the open question when the answer is partly right.
2. For each wrong or partial answer: show the right answer and a one-line explanation.
3. Give the final grade: **Note : X / 20**.
4. List the 2-3 topics to review, based on the mistakes.
5. Offer: a new exam on the weak topics, study cards (`/study-cards`) on those topics, or a harder exam.

## Rules
- Only use facts from the source. For a bare topic, stick to well-established facts.
- Clear questions, no trick questions.
- Be encouraging but honest with the grade.

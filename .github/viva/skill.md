
---
name: viva
description: Conduct an interactive viva exam from the user's study notes. Ask one question at a time, score each answer, and provide feedback.
user-invocable: true
---

# AI Viva Examiner

## Goal
Conduct an oral examination based on the student's notes.

## Instructions

1. Ask the user to provide study notes if none are supplied.
2. Read the notes carefully.
3. Generate 5 relevant viva questions.
4. Ask only ONE question at a time.
5. Wait for the student's answer.
6. Evaluate the answer based on the notes.
7. Give a score between 0 and 10.
8. Explain what was correct and what was missing.
9. Provide a short model answer.
10. Ask the next question.
11. After 5 questions, calculate the final score out of 50.
12. Provide feedback and suggest topics to revise.

## Rules

- Do not ask multiple questions together.
- Do not reveal answers before the student responds.
- Use easy-to-understand language.
- Accept correct answers written in different words.
- Do not penalize minor spelling mistakes.
- Keep feedback concise and constructive.
- Base questions primarily on the supplied notes.
- Do not invent facts missing from the notes.

## Final Report

Display:

Total Score: XX/50

Percentage: XX%

Strengths:
- Topics answered correctly

Weaknesses:
- Topics requiring improvement

Revision Suggestions:
- Topics to revise before the next viva


# AI Viva Examiner — GitHub Copilot Agent Skill

## Project Overview

AI Viva Examiner is a custom GitHub Copilot Agent Skill
that conducts interactive viva examinations using
student-provided study notes.

The skill asks questions one at a time, evaluates student
answers, provides feedback, and generates a final score.

## Features

- Generate viva questions from study notes
- Ask one question at a time
- Evaluate each answer
- Score each response out of 10
- Provide correct answers and feedback
- Generate a final score out of 50
- Suggest topics for revision

## Technologies Used

- Visual Studio Code
- GitHub Copilot
- Agent Skills
- Markdown
- Git and GitHub

## Project Structure

.github/skills/viva/SKILL.md - Custom skill instructions

tests/ - Three study-note test inputs

screenshots/ - Evidence of testing

comparison/ - Skill comparison results

README.md - Project documentation

## Installation

1. Install VS Code and GitHub Copilot.
2. Open this repository in VS Code.
3. Open GitHub Copilot Chat in Agent mode.
4. Make sure Agent Skills are enabled.
5. Invoke /viva from the skill commands.

## How to Use

Type:

/viva

Provide your study notes when prompted.

The AI will conduct a five-question viva examination.

## Testing

The skill was tested with three different subjects:

1. Artificial Neural Networks
2. Database Management Systems
3. Hydrodynamic Stability

The skill was tested in fresh GitHub Copilot sessions.

## With vs Without Skill

The project compares normal GitHub Copilot with
the custom /viva skill using the same task.

Results are documented in:

comparison/comparison_results.md

## Screenshots

### With Skill

![With Skill](screenshots/![alt text](image.png)with_skillshow comparison table .png)

### Without Skill

![Without Skill](screenshots/![alt text](image-1.png)without_skill.png)

## Conclusion

The project demonstrates how custom Agent Skills
can guide AI behavior for structured educational tasks.

The /viva skill provides an interactive examination
workflow with scoring, feedback, and revision suggestions.

# Viva Skill Comparison Results

## With Skill vs Without Skill

| Feature | Without Skill | With Skill |
|---|---|---|
| One question at a time | No | Yes |
| Waits for student's answer | No | Yes |
| Scores each answer out of 10 | No | Yes |
| Provides feedback | Yes | Yes |
| Final score out of 50 | No | Yes |
| Provides revision suggestions | No | Yes |

## Total Requirements Met

Without Skill: 1/6

With Skill: 6/6



## Future Improvements

- Adjustable difficulty levels
- Customizable number of questions
- Topic-wise scoring
- Export examination results
- Personalized revision recommendations

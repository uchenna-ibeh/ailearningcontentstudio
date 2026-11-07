# AI Learning Content Studio

### Exploring how generative AI can support learning content creation

I built this prototype to explore how AI and automation could help learning and development teams turn existing training materials into useful learning resources.

The idea was to make content creation more structured and efficient, while keeping human review at the centre of the process.

## The problem I wanted to explore

Creating learning materials from scratch can take time. A single training document may need to be adapted into a short lesson, a quiz and a facilitator guide.

I wanted to see whether AI could help with that process without losing sight of accuracy, clarity and the needs of the learner.

## What I built

The AI Learning Content Studio takes sample training material and uses an AI-powered workflow to generate:

- Short microlearning lessons
- Knowledge-check quizzes
- Facilitator guides

It also includes a quality review tracker and an impact metrics sheet.

## How it works

The prototype connects three modules:

1. Google Sheets: Holds the source training material and relevant information.
2. Make.com:Watches for new source material and passes it to the AI prompt.
3. Make AI Toolkit: Generates the learning content, which is then saved back into Google Sheets.

The workflow is:

`Source material → AI prompt → Generated learning content → Human review`
## Explore the workflow

[View the AI Learning Content Studio scenario on Make.com](https://eu1.make.com/public/shared-scenario/ZVzfEopDbmS/ai-learning-content-studio-content-gen)
## Tools used

- Make.com – workflow automation
- Google Sheets – source library, generated content and tracking
- Make AI Toolkit – AI-powered content generation

## Human review and responsible AI

I included a quality review section because generated content should not automatically be considered accurate or ready for use.

The review framework considers:

- Factual accuracy
- Alignment with learning objectives
- Clarity
- Accessibility
- Whether the content is supported by the original source

A human reviewer must check the material before it is used in a real training environment.

## Measuring potential impact

I also created an impact tracker to record:

- Manual content creation time
- AI-assisted creation time
- Time saved
- Quality scores
- Number of revisions
- Learner feedback

The figures in the current demonstration are illustrative examples, not measured results from a live pilot.

## What I learned

Building this prototype gave me practical experience connecting AI prompts, spreadsheets and automation workflows.

It also made me think about the wider process of introducing AI into learning and development: generating content is only one part of the work. The content must also be accurate, accessible, relevant and reviewed.

## What I would improve next

If I continue developing the prototype, I would like to:

- Test it with approved training materials.
- Improve source referencing and factual checks.
- Explore content localisation.
- Gather feedback from actual learners.
- Compare AI-assisted content creation with the existing manual process.

## Current status

This is an early proof of concept built with sample training material. It has not been deployed in an organisation or tested with real learners.

## Project Resources

- [View the Make.com automation scenario](https://eu1.make.com/public/shared-scenario/ZVzfEopDbmS/ai-learning-content-studio-content-gen)
- [View the Google Sheets project tracker](https://docs.google.com/spreadsheets/d/1p9UWVo3R98E-SS_ljw_JE4iEeZ_5ukOU-Gq7B5cL1DQ/edit?usp=sharing)

## Project Documentation

- [AI content generation prompt](documentation/ai-prompt.md)
- [Workflow explanation](documentation/workflow-explanation.md)
- [Quality review framework](documentation/quality-review-framework.md)

## Screenshots

See the [screenshots folder](screenshots/) for the automation workflow, generated content, quality review and impact metrics.

The aim is to demonstrate the workflow and explore its potential, rather than present it as a finished product.

---

**Created by:** Uchenna Jennifer Ibeh  
**Project:** AI Learning Content Studio  
**Version:** 1.0 – Initial prototype

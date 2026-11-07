# Workflow Explanation

## Overview

The AI Learning Content Studio uses Make.com to connect Google Sheets with an AI content-generation step.

The workflow takes training material from a source library, sends it to an AI prompt and stores the generated learning package in Google Sheets.

## How the workflow works

### Step 1 – Collect source material

Google Sheets uses the **Watch New Rows** module to detect new training material added to the source library.

### Step 2 – Generate learning content

Make AI Toolkit uses the **Simple Text Prompt** module to process the source material.

The prompt instructs the AI to create:
- A microlearning lesson
- A five-question knowledge-check quiz
- A facilitator guide

### Step 3 – Store the output

The final Google Sheets module, **Add a Row**, saves the generated content in the Generated Content tab.

## Workflow sequence

Google Sheets – Watch New Rows

↓

Make AI Toolkit – Simple Text Prompt

↓

Google Sheets – Add a Row

## Human review

Generated content is not automatically considered ready for use. The Quality Review tracker provides a place for a human reviewer to assess accuracy, clarity, accessibility and alignment with learning objectives.

## Current limitations

This is an initial prototype using sample training material. It has not been deployed in a live organisation or tested with learners. The workflow demonstrates the automation process, while human review remains necessary before workplace use.

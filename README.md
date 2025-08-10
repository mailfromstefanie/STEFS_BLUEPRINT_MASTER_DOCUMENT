A structured “Engineer Mode” blueprint system for AI-assisted projects — keep full context, version history, and next actions in one reusable text file for seamless continuity between sessions.

# STEFSTOOLS – Blueprint Workflow & Engineer Mode

## 📄 Blueprint Workflow – User Guide
Explains step-by-step how to use a **blueprint document** as a persistent memory bridge between AI chat sessions.

**Covers:**
- Store all core project details in one text file
- Use this file in a new AI session to continue without losing context
- Track changes, version numbers, and changelogs
- Update and maintain a project snapshot after each session

---

## 📄 Master Blueprint Template – Engineer Mode
A ready-to-use, structured template for filling in complete project information.

**Includes sections for:**
- Project name, version, and main goal  
- AI working mode instructions (Engineer Mode)  
- Current project state (Snapshot)  
- Next actions (Queue)  
- Decision and change log  

**Purpose:** Designed for technical projects with a focus on **consistency, version control, and fast onboarding** for collaborators or AI assistants.

---

## 💡 GitHub Repo Tagline
> A structured "Engineer Mode" blueprint system for AI-assisted projects — keep full context, version history, and next actions in one reusable text file for seamless continuity between sessions.

---

## 🎯 Optional Marketing-Friendly Tagline
Stay organized and in control: one simple text file to capture your project's context, progress, and next steps — making AI-assisted development faster and smarter.

STEFSTOOLS – Blueprint Workflow & Engineer Mode
===============================================

Overview
--------
This repository contains the Blueprint Workflow and Master Blueprint Template – Engineer Mode,
a system for keeping full project context between AI sessions, ensuring smooth continuation
without having to re-explain everything.

It is designed for:
- Technical projects (Unity, VRChat, scripting, tools)
- Consistent project tracking
- Seamless onboarding for AI assistants or collaborators

------------------------------------------------------------
BLUEPRINT WORKFLOW – USER GUIDE
------------------------------------------------------------

PURPOSE
-------
The blueprint ensures that ChatGPT (Nova) always knows exactly where we left off and how to respond,
without me having to explain everything again from scratch.
I keep one continuous document per project.

MASTER BLUEPRINT STRUCTURE
--------------------------
BEGIN BLUEPRINT
PROJECT NAME:         [Name]
VERSION:              [vX.X – date]
MAIN GOAL:            [Core project description]
HOW CHATGPT SHOULD RESPOND:
  - [Response style rules]
CURRENT SNAPSHOT:     [Current project state]
SCENE ANALYSIS LOG:   [File name / log info]
NEXT ACTIONS:
  1. [First task]
  2. [Second task]
LOG:
  - [Date] – [Event / decision]
END BLUEPRINT

SCENARIOS
---------

1) NEW BLUEPRINT (first time or full restart)
   Nova, fill in the master blueprint for this project based on everything we have done so far.

2) UPDATE BLUEPRINT (after new developments)
   Nova, update the existing blueprint with what we have done since the last version.
   → Nova updates the Snapshot, Queue, and Log, and increases the version number.

3) CONTINUE WITHOUT UPDATING
   Nova, use the latest blueprint as the basis and continue at [topic/step].
   → Nova picks up the context and continues immediately.

4) RESET TO EMPTY MASTER
   Nova, give the empty master blueprint.
   → Nova sends the unfilled template so I can start fresh.

ADDING FILES
------------
- Attach a Scene Analysis log (.json or .txt) to the blueprint for extra context.
- Always clearly name the file in the SCENE ANALYSIS LOG field.

VERSION CONTROL
---------------
- Always save the blueprint as: PROJECTNAME_Blueprint_vX.X.txt
- Every time you update → increase the version number by 0.1.

TIPS
----
- Keep the CURRENT SNAPSHOT short but factual.
- Only put realistic, actionable tasks in NEXT ACTIONS.
- The LOG should only contain important decisions and events.
- HOW CHATGPT SHOULD RESPOND should generally stay the same for each project.

------------------------------------------------------------
MASTER BLUEPRINT TEMPLATE – ENGINEER MODE
------------------------------------------------------------
A ready-to-use, structured template for filling in complete project information.

Includes sections for:
- Project name, version, and main goal
- AI working mode instructions (Engineer Mode)
- Current project state (Snapshot)
- Next actions (Queue)
- Decision and change log

Purpose: Designed for technical projects with a focus on consistency, version control,
and fast onboarding for collaborators or AI assistants.

------------------------------------------------------------
EXAMPLE PHRASES FOR DIFFERENT SCENARIOS
------------------------------------------------------------

Scenario 1 – Continue where you left off
Use this as basis. You are in ENGINEER MODE. Continue at "NEXT ACTIONS (Queue)".
Keep my project structure intact.

Scenario 2 – Update the blueprint after changes
Fill in the blueprint update:
- Add today’s changes to the LOG
- Update CURRENT SNAPSHOT with new details
- Refresh NEXT ACTIONS with the next tasks

Scenario 3 – Create a new blueprint for another project
Create a Master Blueprint using the template, for my new project about [short project description].

Scenario 4 – Quick minimal context when tokens are low
Quick blueprint: [short 1–2 sentence project summary].

------------------------------------------------------------
GITHUB REPO TAGLINE
------------------------------------------------------------
A structured "Engineer Mode" blueprint system for AI-assisted projects — keep full context,
version history, and next actions in one reusable text file for seamless continuity between sessions.

------------------------------------------------------------
OPTIONAL MARKETING-FRIENDLY TAGLINE
------------------------------------------------------------
Stay organized and in control: one simple text file to capture your project's context, progress,
and next steps — making AI-assisted development faster and smarter.


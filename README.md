STEFSTOOLS – Blueprint Workflow & Engineer Mode
===============================================

Description
-----------
A structured "Engineer Mode" blueprint system for AI-assisted projects — keep full context,
version history, and next actions in one reusable text file for seamless continuity between sessions.

Designed for:
- Technical projects (Unity, VRChat, scripting, tools)
- Consistent project tracking
- Seamless onboarding for AI assistants or collaborators

------------------------------------------------------------
BLUEPRINT WORKFLOW – USER GUIDE
------------------------------------------------------------

Purpose
-------
The blueprint ensures that ChatGPT (Nova) always knows exactly where we left off and how to respond,
without me having to explain everything again from scratch.
I keep one continuous document per project.

Master Blueprint Structure
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

Scenarios
---------
1) NEW BLUEPRINT (first time or restart)  
   Nova, fill in the master blueprint for this project based on everything we have done so far.

2) UPDATE BLUEPRINT (after new developments)  
   Nova, update the existing blueprint with what we have done since the last version.  
   → Updates Snapshot, Queue, Log, and increases version number.

3) CONTINUE WITHOUT UPDATING  
   Nova, use the latest blueprint as the basis and continue at [topic/step].

4) RESET TO EMPTY MASTER  
   Nova, give the empty master blueprint.

Adding Files
------------
- Attach a Scene Analysis log (.json or .txt) to the blueprint for extra context.
- Always clearly name the file in the SCENE ANALYSIS LOG field.

Version Control
---------------
- Save as: PROJECTNAME_Blueprint_vX.X.txt
- Each update → increase version number by 0.1

Tips
----
- Keep CURRENT SNAPSHOT short and factual.
- Only list realistic, actionable tasks in NEXT ACTIONS.
- LOG contains only key decisions and events.
- HOW CHATGPT SHOULD RESPOND usually stays the same per project.

------------------------------------------------------------
MASTER BLUEPRINT TEMPLATE – ENGINEER MODE
------------------------------------------------------------
Ready-to-use, structured template for complete project information.

Includes:
- Project name, version, and main goal
- AI working mode instructions (Engineer Mode)
- Current project state (Snapshot)
- Next actions (Queue)
- Decision and change log

Purpose: Consistency, version control, and fast onboarding for collaborators or AI.

------------------------------------------------------------
EXAMPLE PHRASES
------------------------------------------------------------

Continue where you left off:
Use this as basis. You are in ENGINEER MODE. Continue at "NEXT ACTIONS (Queue)". Keep my project structure intact.

Update blueprint:
Fill in the blueprint update:
- Add today’s changes to the LOG
- Update CURRENT SNAPSHOT
- Refresh NEXT ACTIONS

New blueprint for another project:
Create a Master Blueprint using the template for my new project about [short project description].

Minimal context when tokens are low:
Quick blueprint: [short 1–2 sentence project summary].

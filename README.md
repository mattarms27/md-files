# md-files

## What is this for?
The objective of this repo is to provide useful sets of agent instructions to ensure consistency across areas of development that agents seem to randomize with every new session or project. Examples of this include version control workflows, file structures within codebases, naming conventions, and design standards.

## How to use
**All of the good stuff is stored in the `/directives` folder.**

These markdown files are written to be modular. Simply append the contents to the agent instructions file in your codebase (eg. CLAUDE.md, AGENTS.md, etc.). If you do this while you have an agent actively running, you may need to tell it to re-read it's instructions file.
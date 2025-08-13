# About This Repository
This repository is for the Basic Chat Workflows website (BCW). BCW is intended to be both a publicly 
and privately hostable open-source project which allows people to make JSON-basaed workflows which are
processed by one or more LLMs. Steps in the workflow are reflected as cards.

## How Workflows Work
* Each workflow as a minimum of one step.
* First step card establishes the context and purpose of the workflow.
* A small number of pre-defined cards can be added:
  * "Generic" card with a field for a description for instructions, and output.
  * "Analyze Image" card which optionally lets user describe what information to provide from the image.
  * "Search the Web" card which uses JS and publicly available APIs to get web results.
  * "Create data" card which converts text-based information 

---
step: <% tp.file.title %>
tool: "<% tp.system.prompt("Tool or Service used in this step (e.g., Cursor Composer, Trello, Perplexity, Obsidian, Terminal)") %>"
goal: "<% tp.system.prompt("What do you aim to accomplish in this step?") %>"
goal_source: "<% tp.system.prompt("Source of the goal (e.g., me, output from a previous step)") %>"
context: "<% tp.system.prompt("What project resources, notes, etc. are needed for optimal performance of this step?") %>"
input: "<% tp.system.prompt("What input is required for this step?") %>"
output: "<% tp.system.prompt("What is the expected output of this step?") %>"
parent_step: "<% tp.system.prompt("What is the parent step? (Leave blank for root step 1)") %>"
child_steps: "<% tp.system.prompt("List child steps, comma-separated (e.g., 2,3,4)") %>"
estimated_time: "<% tp.system.prompt("Estimated time to complete this step") %>"
---

## Step <% tp.file.title %>: {{goal}}

### Tool/Service
{{tool}}

### Goal
{{goal}}

### Goal Source
{{goal_source}}

### Context
{{context}}

### Input
{{input}}

### Process
1. 
2. 
3. 

### Output
{{output}}

### Child Steps
{{child_steps}}

### Notes
- 
- 

### Time Spent
Estimated: {{estimated_time}}
Actual: 

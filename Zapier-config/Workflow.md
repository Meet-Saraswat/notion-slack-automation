\# 📄 zapier-config/workflow.md



```md

\# Zapier Workflow (Notion → Slack Automation)



\### Step 1. Trigger

\- \*\*App:\*\* Notion

\- \*\*Trigger:\*\* New Database Item (Goals DB)



\### Step 2. AI by Zapier

\- \*\*Action:\*\* Analyze and Return Data

\- \*\*Prompt:\*\* See `prompt.md`

\- \*\*Output:\*\* Tasks\[], Roles\[], Due Dates\[], Risks\[]



\### Step 3. Formatter

\- \*\*Line-Item to Text\*\* for Tasks

\- \*\*Line-Item to Text\*\* for Risks



\### Step 4. Looping by Zapier

\- \*\*Create Loop From Line Items\*\*

\- Values: Tasks, Roles, Due Dates



\### Step 5. Notion

\- \*\*Create Database Item\*\* (Tasks DB)

\- Fields:

&nbsp; - Task → Task

&nbsp; - Role → Role

&nbsp; - Due Date → Due Date

&nbsp; - Source Goal → Relation to Goal

&nbsp; - Status → Not started

&nbsp; - Assignee → From Lookup Table



\### Step 6. Formatter (Lookup Table)

\- Maps Role → Slack User ID



\### Step 7. Slack (Send Direct Message)

\- Sends each assignee their individual task.



\### Step 8. Slack (Send Channel Message)

\- Posts a summary of the weekly goal, tasks, and risks to the team channel.




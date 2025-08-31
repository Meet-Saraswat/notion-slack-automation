# 🔄 Notion → Slack Weekly Goals Automation



This project automates the process of turning **Notion weekly goals** into actionable tasks, syncing them back into Notion as individual tasks, and sending a **Slack summary + direct messages to assignees**.


## ⚡ How It Works



1. **Trigger** → New Goal created in Notion (Goals DB).

2. **AI by Zapier** → Breaks down the goal into tasks, roles, and risks (structured JSON).

3. **Formatter** → Converts arrays into clean text.

4. **Looping by Zapier** → Iterates through tasks.

5. **Notion (Tasks DB)** → Creates tasks with role, due date, source goal.

6. **Slack Channel** → Posts a weekly summary message of all tasks and risks.

7. **Slack DM** → Sends each assignee a private message with their assigned task.



## 🛠️ Tech Stack

- **Notion** (Goals + Tasks Databases)

- **Zapier** (automation + AI)

- **Slack** (summary + DM delivery)

- **OpenAI** (via AI by Zapier)\*\* for task breakdown


## 📌 Example Flow


- Goal added in Notion: 

Build weekly sales performance dashboard





- **Zapier generates tasks like:**

- Gather data from CRM (Analyst)

- Gather data from Google Analytics (Analyst)

- Create dashboard layout (Designer)

- Visualize KPIs (Designer)

- Review dashboard with stakeholders (PM)

- Finalize and distribute dashboard (PM)



- **Slack posts the summary:**



Weekly Goals → Tasks (Auto)



Goal: Build weekly sales performance dashboard

Priority: P2

Week ends: 2025-08-31



Tasks:

• Gather data from CRM (Analyst, Due: 2025-08-25)

• Gather data from Google Analytics (Analyst, Due: 2025-08-26)

• Create dashboard layout (Designer, Due: 2025-08-27)

• Visualize KPIs (Designer, Due: 2025-08-28)

• Review dashboard with stakeholders (PM, Due: 2025-08-29)

• Finalize and distribute dashboard (PM, Due: 2025-08-31)



Risks:

• Data source discrepancies

• Lack of design resources

• Potential delays in data processing

• Stakeholder availability

• Technical issues during distribution










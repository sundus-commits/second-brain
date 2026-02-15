# second-brain
## 1) Create the Database

**Notion command:** `/database` → **Database (Full page)**  
**Database name:** `Knowledge Base`

### Properties (recommended)
Create these properties in the database:

- **Type** *(Select)*  
  - Note  
  - Decision  
  - Reference  
  - Idea

- **Status** *(Select)*  
  - Open  
  - In progress  
  - Done  
  - Archived

- **Priority** *(Select)*  
  - Low  
  - Medium  
  - High

- **Area** *(Select)*  
  - Work  
  - Personal  
  - Learning

- **Linked Project** *(Relation → Projects database)*  
- **Linked Goal** *(Relation → Goals database)*  
- **Created** *(Created time)*

---

## 2) Views (GitHub-like Workflow)

Create these views at the top of the database:

### View A — “Open” (List)
- **Type:** List
- **Filter:** Status = `Open`
- **Sort:** Priority (High → Low), then Created (Newest first)

### View B — “Board” (Kanban)
- **Type:** Board
- **Group by:** Status
- **Columns:** Open → In progress → Done → Archived

### View C — “Done” (List)
- **Type:** List
- **Filter:** Status = `Done`
- **Sort:** Created (Newest first)

### View D — “Archive” (List)
- **Type:** List
- **Filter:** Status = `Archived`
- **Sort:** Created (Newest first)

---

## 3) Page Template (Issue-Style)

In the database, click **New** → **+ New template**  
**Template name:** `Issue / Note`

Paste this into the template page:

### Summary
One sentence: what is this about?

### Context
Why did this come up? What problem does it relate to?

### Details
- Key facts / notes
- Links / sources
- Constraints / assumptions

### Decision / Outcome
What did I decide or learn?

### Next Action (optional)
If this should lead to action, what is the next concrete step?

---

## 4) Suggested Naming Rules (Professional Feel)

- Keep titles short and specific:
  - “Decide pricing for template”
  - “Reference: Notion database best practices”
  - “Idea: Weekly review flow”
- Use **Status** like GitHub:
  - Open = captured
  - In progress = actively thinking/working
  - Done = concluded/clear
  - Archived = keep for later, no action needed

---

## 5) Second Brain Home (Dashboard Page)

Create a page called: `Second Brain`

Paste this layout:

## Capture
Use **Open** for quick capture. Keep it simple.

- **Open items:** (embed a linked view filtered to Status = Open)

## Work the workflow
Move items across the board as you think and decide.

- **Board:** (embed a linked Board view grouped by Status)

## Keep what’s completed
- **Done:** (embed a linked view filtered to Status = Done)
- **Archive:** (embed a linked view filtered to Status = Archived)

---

## 6) Daily Use (30 seconds)
1. Add a new item → set **Type** + **Status = Open**
2. When you work on it → set **Status = In progress**
3. When it’s clear/finished → set **Status = Done**
4. If you want to keep it without action → set **Status = Archived**

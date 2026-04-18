# 🧠 plskills

> A curated library of **high-signal, reusable AI skills**  
> designed to work *reliably* inside AI interfaces.

---

## 🚨 The Problem

In my opinion, most “prompt libraries” on GitHub are:

- ❌ Too long  
- ❌ Poorly structured  
- ❌ Inconsistent  
- ❌ One-off and not reusable  
- ❌ Break down over longer conversations  

They look good… but don’t actually *work well in practice*.

---

## ✅ The Idea

This repo turns prompts into **skills**:

> Compact, structured instruction sets that AIs can *actually follow* consistently.

Each skill is:

- ⚡ Short enough to stay in context  
- 🧱 Structured (rules, checklists, outputs)  
- 🔁 Reusable across conversations  
- 🧠 Designed to encode real expertise  
- 🧩 Composable with other skills  

---

## 🔥 Example

Instead of this:

> “Act as a UI designer and make something nice…”

You get this:

```md
ROLE: Graphic Designer for Accessible Web

RULES:
- Never rely on color alone
- Maintain strong contrast
- Ensure visible focus states

CHECKLIST:
- Contrast
- Focus
- Target size
- Form usability
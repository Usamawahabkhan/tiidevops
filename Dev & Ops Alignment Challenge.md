### Dev & Ops Alignment Challenge  
#### Full step‑by‑step tutorial for DevOps leadership practice

---

## 1. Objective (what you tell the class)

**Say this:**

> “In this exercise, Dev and Ops will start from different priorities—speed vs stability—and you’ll experience how alignment is created through conversation, not authority. Your job, especially if you see yourself as a DevOps leader, is to notice how decisions change when we make priorities explicit.”

---

## 2. Setup (5 minutes)

**Room & materials**

- **Participants:** Minimum 6–8, ideal 10–16  
- **Space:** Two separate areas (or opposite sides of the room)  
- **Materials:**  
  - Flipcharts or whiteboards  
  - Sticky notes  
  - Markers  

**Role split**

- **Group A:** Developers (Dev)  
- **Group B:** Operations / ITSM (Ops)  
- If you have many people, split into **multiple Dev/Ops pairs of groups**.

**Your role as trainer**

- You are the **DevOps Leader / Facilitator** observing how they align.  
- You do **not** solve it for them—you create the conditions.

---

## 3. Private briefs (5 minutes)

You now give **different instructions** to each group, separately.

### 3.1. Developer brief (read only to Dev group)

> “You are the development team.  
> Today you have a **critical feature** ready:
> - It fixes a customer‑visible bug in production  
> - It adds a small improvement customers have been asking for  
>
> You’ve already delayed this release once.  
> Product is pushing for it to go out **today**.  
>
> **Your priority:** Speed and customer value.  
> You believe:
> - Delaying again will hurt customer trust  
> - The change is low risk  
> - Ops is being too conservative”

Ask them to write on a flipchart:

- **Why we should deploy today**  
- **What risks we think are acceptable**  

### 3.2. Ops brief (read only to Ops group)

> “You are the operations team.  
> This week you’ve had **two production incidents**:
> - One caused an outage  
> - One caused a performance degradation  
>
> You are under pressure from management to **reduce incidents**.  
> You know:
> - Monitoring is not perfect  
> - Rollback is not always clean  
>
> **Your priority:** Stability and risk reduction.  
> You believe:
> - Another incident this week will damage credibility  
> - The system needs more testing  
> - Dev is underestimating risk”

Ask them to write on a flipchart:

- **Why we should NOT deploy today**  
- **What conditions must be true before we deploy**  

---

## 4. Alignment round (10–12 minutes)

Now you bring Dev and Ops together.

**Say this:**

> “You now have one shared decision to make:  
> **Do we deploy today or not?**  
> You must reach one joint decision and be able to explain it.”

### 4.1. Rules for the conversation

- Each side must **first explain their perspective** (no interruptions).  
- Then they can **ask clarifying questions**.  
- They must end with:
  - One **joint decision**  
  - 2–3 **agreed conditions** (e.g., “We deploy if X, Y, Z are true.”)

### 4.2. Suggested structure (you can write this on a slide/board)

1. Dev explains their view (2–3 minutes)  
2. Ops explains their view (2–3 minutes)  
3. Open discussion (5–6 minutes)  
4. Joint decision + conditions (2 minutes)

---

## 5. Example conversation (what it might sound like)

### Dev side

> “We’ve already delayed this release once. Customers are waiting for the bug fix. The change is small and well‑tested. If we don’t ship today, we risk losing trust and looking slow.”

### Ops side

> “We’ve had two incidents this week. Our monitoring is not fully reliable, and rollback is not always clean. If this release causes another issue, we’ll lose credibility with leadership. We need stronger assurance before we deploy.”

### Good DevOps Leader‑style questions you want them to ask each other

- “What would make this safe enough for you?”  
- “What’s the worst realistic outcome if we deploy today?”  
- “What can we do quickly to reduce that risk?”  
- “Is there a smaller version we can ship?”  
- “Can we add extra monitoring or a fast rollback plan?”

### Example of a good joint outcome

> “We **will deploy today**, but:
> - We add extra logging and monitoring for this feature  
> - We have a tested rollback plan ready  
> - We deploy in a low‑traffic window  
> - We do a quick post‑deployment review together”

Or:

> “We **will not deploy today**, but:
> - We schedule a deployment window tomorrow morning  
> - We run one more round of tests together  
> - We improve rollback before the next release  
> - We inform Product with a clear, honest explanation”

Both are valid—what matters is **shared reasoning**.

---

## 6. Debrief as DevOps Leader (10 minutes)

This is where the learning happens. You step into **DevOps Leader mode**.

### 6.1. Ask Dev group

- “What did you assume about Ops before the conversation?”  
- “What changed after you heard their constraints?”  
- “What would you do differently next time you plan a release?”

### 6.2. Ask Ops group

- “What did you assume about Dev before the conversation?”  
- “What changed after you heard their pressures?”  
- “What would you do differently next time you see a risky change?”

### 6.3. Ask both

- “What made alignment easier?”  
- “What made it harder?”  
- “What information was missing at the start?”  
- “What would a good **shared release policy** look like?”

Write key points on the board under three headings:

- **Assumptions**  
- **New understanding**  
- **New agreements**

---

## 7. Make the DevOps leadership lessons explicit

Now you **name the patterns** for them.

### 7.1. Lesson 1 — Both sides are right

**Say:**

> “Dev is right to care about speed and customer value.  
> Ops is right to care about stability and risk.  
> DevOps leadership is not choosing one—it’s integrating both.”

### 7.2. Lesson 2 — Misalignment is often invisible

> “Before the conversation, each side thought the other was ‘difficult’.  
> After the conversation, you saw they were protecting different risks.  
> Misalignment is usually unspoken, not intentional.”

### 7.3. Lesson 3 — Alignment is a practice, not a meeting

> “You don’t fix this with one big meeting.  
> You fix it with:
> - Shared release criteria  
> - Shared dashboards  
> - Shared incident reviews  
> - Shared language around risk and value”

---

## 8. As a DevOps Leader: what you should “see” as clear outcomes

By the end of this exercise, you should see:

### 8.1. Behavioral outcomes

- Dev and Ops **talking to each other**, not about each other  
- Less “you’re blocking us” and more “what do you need to feel safe?”  
- More **questions** than accusations  
- A visible shift from **position** (“deploy / don’t deploy”) to **conditions** (“deploy if…”)

### 8.2. Mindset outcomes

Participants should realize:

- “Ops isn’t anti‑change; they’re anti‑uncontrolled risk.”  
- “Dev isn’t reckless; they’re under pressure to deliver value.”  
- “We need shared language for risk, value, and readiness.”

### 8.3. Practical outcomes

You can now ask:

> “What one change will you take back to your real work?”

Examples they might say:

- “We’ll define shared ‘ready to deploy’ criteria.”  
- “We’ll create a joint Dev+Ops release checklist.”  
- “We’ll invite Ops earlier into planning.”  
- “We’ll add a quick risk/impact section to every change.”

That’s when you know the exercise landed as **real DevOps practice**, not just a game.

---

## 9. One‑sentence close (use this to end)

> “DevOps is not Dev winning or Ops winning—it’s the system winning.  
> Alignment is the leader’s job, and you just practiced how to create it.”

If you want, I can turn this into a **printable facilitator guide** or a **slide‑by‑slide activity deck** next.

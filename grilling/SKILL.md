---
name: grilling
description: Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases.
---

Interview the user relentlessly until you reach a shared understanding. Map this as a **design tree**: every decision branches into the decisions that hang off it.

The **frontier** is every decision whose prerequisites are already settled: the questions you can ask _now_ without guessing at answers you haven't heard yet. Ask **one frontier question at a time**, as 3–4 options with your recommended option first and why. The user often answers by voice with a single letter, so keep options short and distinct. Use the AskUserQuestion tool when it is available. Then wait for the answer before the next question.

Pick the frontier question whose answer unblocks the most of the tree. If the user says "later, move on", park that question, track it, and come back to it before you finish.

Each answer reshapes the tree: settled decisions push the frontier outward and unblock questions that depended on them. Recompute the frontier before the next question.

Finding _facts_ is your job, never the user's. When a frontier question needs a fact from the environment (filesystem, tools, etc.), look it up yourself before you ask it; don't ask the user for anything you could look up yourself. The _decisions_ are the user's: put each to them and wait.

The session is done when the frontier is empty and no parked question is left: every branch of the design tree visited, nothing left silently assumed. Do not act on it until the user confirms you have reached a shared understanding.

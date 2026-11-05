# OpenAI Academy - AI Foundations

![Course](https://img.shields.io/badge/Course-AI%20Foundations-412991?style=flat-square)
![Platform](https://img.shields.io/badge/Platform-OpenAI%20Academy-black?style=flat-square&logo=openai)
![Level](https://img.shields.io/badge/Level-Beginner-success?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)
![Format](https://img.shields.io/badge/Notes-Markdown-blue?style=flat-square)

> **A beginner-friendly study guide to understanding AI, Large Language Models, ChatGPT, prompting, context, evaluation, and responsible AI use.**

These notes are based on my learning from OpenAI Academy's **AI Foundations** course. They are organized for easy learning, future reference, and quick review.

---

## Table of Contents

1. [Course Overview](#1-course-overview)
2. [Module 1 — Introduction to AI](#2-module-1--introduction-to-ai)
3. [Module 2 — Large Language Models](#3-module-2--large-language-models)
4. [Module 3 — Prompting and Evaluation](#4-module-3--prompting-and-evaluation)
5. [Module 4 — Adding Context](#5-module-4--adding-context)
6. [Module 5 — Responsible AI Use](#6-module-5--responsible-ai-use)
7. [Practical Prompt Templates](#7-practical-prompt-templates)
8. [Final Review — What to Remember](#8-final-review--what-to-remember)
9. [Personal Learning Reflection](#9-personal-learning-reflection)

---

# 1. Course Overview

| Detail | Information |
|---|---|
| Course | AI Foundations |
| Provider | OpenAI Academy |
| Difficulty | Beginner |
| Estimated Duration | 70 minutes |
| Format | Self-paced |
| Prerequisites | No technical background required |

### What is this course about?

AI Foundations introduces the fundamentals of artificial intelligence, Large Language Models (LLMs), and ChatGPT.

The course focuses on building practical habits for working with AI:

- Giving clear instructions.
- Providing relevant context.
- Reviewing AI-generated responses.
- Using trusted sources when accuracy matters.
- Protecting private and confidential information.
- Applying human judgment before relying on AI outputs.

### Learning Objectives

By the end of the course, learners should be able to:

1. Explain what AI and Large Language Models are.
2. Understand how ChatGPT works at a high level.
3. Write clearer prompts and provide useful context.
4. Review and improve AI-generated responses.
5. Use AI responsibly and apply independent judgment.

---

# 2. Module 1 — Introduction to AI

## 2.1 What is AI Foundations?

Artificial Intelligence is becoming part of everyday work, education, and problem-solving.

This module introduces ChatGPT and demonstrates how to use it as a learning and productivity tool.

The important idea is that **you don't need to be a programmer or technical expert to use AI effectively.**

### Choose a task to practice

One of the course's recommendations is to choose a small, real-world task and use it throughout the learning process.

Examples:

| Task | Example |
|---|---|
| Drafting | Writing a project update |
| Summarizing | Condensing notes |
| Explaining | Making a difficult topic easier to understand |
| Planning | Preparing for a meeting |
| Brainstorming | Generating ideas |
| Organizing | Structuring personal or work-related information |

**Important:** Avoid sharing sensitive, private, or confidential information during practice.

## 2.2 What is a Prompt?

**Prompt** *(noun)*

A question or instruction given to an AI model to guide the response it generates.

In simple terms:

> A prompt is how you communicate what you want the AI to do.

You can ask ChatGPT to:

- Explain complicated concepts in simpler terms.
- Give examples related to your interests or studies.
- Help you practice a particular skill.
- Quiz you about something you learned.
- Suggest ways to apply AI in your work.

### Example

Instead of simply reading about programming, you can ask:

```text
Explain what a variable is in C programming.

Assume I am a complete beginner.
Use simple language and give me one short code example.
Then ask me one multiple-choice question.
```

The goal is to make AI useful as a learning partner, not just an answer generator.

## 2.3 Module 1 Key Takeaways

- AI can help with everyday tasks.
- Prompting is essentially clear communication.
- Start with a small, practical task.
- Give ChatGPT enough information to understand what you need.
- Use your own judgment when reviewing its responses.

**Remember:** Learn, practice, and use judgment.

---

# 3. Module 2 — Large Language Models

## 3.1 What is Artificial Intelligence?

**Artificial Intelligence (AI)** is the broad category of computer systems that can recognize patterns, make predictions, and help generate or organize information.

AI is the general field. Different AI systems are designed to perform different tasks.

### Three important terms

| Term | Beginner-friendly explanation |
|---|---|
| Artificial Intelligence (AI) | The broad field of computer systems that perform tasks involving capabilities associated with intelligence. |
| Large Language Model (LLM) | A type of AI model that works with human language. |
| ChatGPT | An OpenAI product that makes interacting with an LLM easier. |

**How are they related?**

ChatGPT is an AI tool built on a Large Language Model.

Think of it this way:

- AI = The broader field.
- LLM = A type of AI model.
- ChatGPT = A product that lets people interact with an LLM.

ChatGPT also provides features that support working with AI, including file uploads, search, personalization, image generation, and data analysis.

## 3.2 What is a Large Language Model (LLM)?

**Large Language Model (LLM)**

An advanced AI model trained on large amounts of data to recognize patterns in language and generate human-language responses.

LLMs learn patterns from examples of how people write, explain, and organize information.

### What can LLMs do?

Because much of our everyday work involves language, LLMs can help with:

| Capability | What it means |
|---|---|
| Drafting | Creating a first version of written content. |
| Summarizing | Condensing information into shorter explanations. |
| Explaining | Making complicated topics easier to understand. |
| Planning | Organizing tasks, activities, or ideas. |
| Brainstorming | Generating possible ideas and approaches. |
| Organizing | Structuring information into a clearer format. |

### How does an LLM generate responses?

One of the most important concepts in this course:

**An LLM generates responses by predicting what word or phrase is likely to come next.**

A simplified process:

1. You provide an input or prompt.
2. The model processes the instructions and available context.
3. The model predicts a likely next word or phrase.
4. That prediction becomes part of the context for the next prediction.
5. This process continues until a complete response is generated.

```text
USER INPUT
    |
    v
AI MODEL
    |
    v
PREDICT NEXT WORD OR PHRASE
    |
    v
ADD TO CONTEXT
    |
    v
REPEAT
    |
    v
GENERATED RESPONSE
```

This is why language models are often described as generating responses through prediction rather than simply retrieving a stored answer from a database.

### What does this mean in practice?

| What the model does | What you should do |
|---|---|
| Predicts language based on patterns | Give clear instructions. |
| Uses conversation context | Provide relevant details and examples. |
| Generates fluent responses | Check the response before relying on it. |

**Important:** A response that sounds confident and professional is not automatically correct.

## 3.3 How AI Models Are Trained

The course introduces four stages that help explain how AI models are developed and improved.

### 1. Pre-training

**What happens:** The model learns patterns from large amounts of text and other data.

**Why it matters:** It learns how language and information are commonly structured.

### 2. Post-training

**What happens:** The model is refined using feedback, examples, and evaluations.

**Why it matters:** It becomes better at following instructions and responding helpfully.

### 3. Product Experience

**What happens:** The model is made available through products such as ChatGPT, with interfaces, tools, and safeguards.

**Why it matters:** People can apply the model to everyday tasks more easily.

### 4. Ongoing Feedback

**What happens:** Researchers continue improving models over time.

**Why it matters:** Newer models can become more capable, useful, and safe.

### Quick Comparison

| Stage | Main Purpose |
|---|---|
| Pre-training | Learn patterns from data. |
| Post-training | Improve helpfulness and instruction-following. |
| Product Experience | Make the model accessible through a usable product. |
| Ongoing Feedback | Continue improving models through research. |

### Example: Post-training

Imagine asking ChatGPT:

```text
Explain change management in one sentence.
```

A less helpful response might give you several paragraphs covering communication, stakeholders, training, resistance, and governance.

A more helpful response:

> Change management is the process of helping people understand, adopt, and sustain a new way of working.

Post-training helps refine how models respond to instructions and what kinds of answers are useful.

## 3.4 Why You Need Trusted Sources

A very important lesson:

> **Use ChatGPT as the workspace, not the source of truth.**

ChatGPT can help you understand and work with information, but some tasks require reliable and up-to-date sources.

Use trusted sources, files, or web search when you need:

- Current facts.
- Policies or legal guidance.
- Prices, dates, and schedules.
- Citations and links.
- Exact source material.
- Information that may have changed over time.

### Recommended workflow

```text
TRUSTED SOURCE / FILE / WEB SEARCH
              |
              v
           CHATGPT
              |
              v
  SUMMARY / EXPLANATION / CHECKLIST
              |
              v
       HUMAN REVIEW
```

### Practical examples

| Situation | How ChatGPT can help |
|---|---|
| Meeting notes | Extract decisions and action items. |
| Company policies | Summarize approved guidance into a checklist. |
| Research | Prepare a sourced briefing with links. |

## 3.5 Why AI Needs Human Review

AI tools can be useful and still make mistakes.

Because LLMs generate responses based on patterns and context, they can sometimes produce answers that sound convincing but are incomplete, outdated, or incorrect.

This is commonly called an **AI hallucination**.

### What is an AI Hallucination?

An AI hallucination is a plausible response generated by an AI model that is not properly grounded in the correct information.

### Why do hallucinations happen?

LLMs generate responses based on learned patterns and the information available in context.

They may:

- Produce incorrect information.
- Miss recent developments.
- Lack private or organizational context.
- Make unsupported assumptions.
- Lose track of earlier details in long conversations.

### How can you reduce unsupported assumptions?

Provide more context.

**Less context:**

```text
Write an onboarding checklist for my company.
```

**More context:**

```text
Write an onboarding checklist for a new team member
joining [organization name and industry].

Include:
- Access to tools and systems
- Manager check-ins
- Role-specific training
- Team introductions
- Goals for the first week

Ask me for any missing details before finalizing.
```

The second prompt gives the model more information to work with.

### Why can AI give different answers to the same question?

Language models predict and select from multiple possible next words and phrases.

Because there may be several valid ways to respond, the same prompt can produce different wording, examples, or levels of detail.

This flexibility helps AI adapt to different tasks, but it also means you should review the response rather than assume every answer will be identical.

## 3.6 Module 2 Key Takeaways

Remember these three habits:

- **Generate:** Use ChatGPT for drafting, explaining, brainstorming, and organizing ideas.
- **Ground:** Provide relevant context, files, search results, and trusted sources when details matter.
- **Review:** Check important outputs for accuracy, completeness, relevance, and source support.

---

# 4. Module 3 — Prompting and Evaluation

This module focuses on two practical habits:

1. Writing clearer instructions using **Task, Context, and Expectation**.
2. Reviewing AI-generated responses using the **CLEAR** framework.

## 4.1 Why Clear Prompts Matter

A vague prompt forces the AI to guess what you want.

Compare these examples:

**Vague prompt:**

```text
Write a summary of this report.
```

**Clearer prompt:**

```text
Summarize this report in three bullet points for [audience].

Focus on:
- The most important findings
- Recommended action items
- Anything that requires a decision

Use concise, plain language and include only the most important details.
```

The second prompt gives the model more direction.

## 4.2 Task, Context, and Expectation (TCE)

A useful prompt can be organized into three parts.

### 1. Task — What do you want the AI to do?

This is the actual instruction or action.

Examples:

- Draft an email.
- Summarize notes.
- Create a checklist.
- Explain a concept.

### 2. Context — What background information should the AI consider?

Context helps the model understand the situation.

Examples:

- Who will read the output?
- Why do you need it?
- What does the audience already know?
- Are there specific goals or restrictions?

### 3. Expectation — How should the response look?

This defines the desired output.

Examples:

- Format.
- Length.
- Tone.
- Level of detail.

### TCE Summary

| Component | Purpose | Example |
|---|---|---|
| Task | What should be done? | Draft an email. |
| Context | What background matters? | It is for a colleague who missed a project meeting. |
| Expectation | How should the output look? | Three bullets, warm tone, clear next step. |

### Putting everything together

```text
Draft an email to a colleague who missed today's project meeting.

Context:
They need to understand the key decisions made during the meeting.

Expectation:
- Summarize the key decisions in three bullet points.
- Use a warm tone.
- End with a clear next step.
```

**Remember:** TCE is a flexible guide, not a rigid formula.

## 4.3 Reviewing AI Outputs — The CLEAR Framework

Even a well-written prompt does not guarantee a perfect answer.

Before using an AI-generated response, review whether it is accurate, complete, relevant, and appropriate for your purpose.

The course introduces the **CLEAR** framework.

| Letter | Meaning | Question to Ask |
|---|---|---|
| C | Complete | Did it answer everything I asked for? |
| L | Logical | Does it make sense from start to finish? |
| E | Evidence | Is it accurate and grounded? Do I need to check sources? |
| A | Audience | Is it appropriate for the person who will read or use it? |
| R | Relevant | Does it stay focused on the task? |

### Example: Applying CLEAR

Imagine ChatGPT generates a project update.

Review it:

- **Complete:** Did it include all requested updates?
- **Logical:** Does the information flow properly?
- **Evidence:** Are the dates, figures, and claims correct?
- **Audience:** Is the language appropriate for the intended readers?
- **Relevant:** Does it focus on the project instead of unrelated details?

If something fails the review, revise the prompt or ask ChatGPT to improve the response.

### Example revision prompt

```text
Review your previous response using the CLEAR framework.

Check:
1. Completeness
2. Logical flow
3. Evidence and accuracy
4. Audience suitability
5. Relevance

Identify any weaknesses and provide an improved version.
Do not invent missing information.
```

## 4.4 Module 3 Key Takeaways

- **Task, Context, and Expectation** help you direct the AI.
- **CLEAR** helps you evaluate its response.
- A strong prompt improves the starting point, not necessarily the final result.
- Refinement is part of the workflow.
- You are responsible for deciding whether an output is ready to use.

---

# 5. Module 4 — Adding Context

This module explains why a clear prompt is not always enough.

Sometimes ChatGPT needs additional information to produce a useful response.

## 5.1 What is Context?

**Context** is the relevant information that helps ChatGPT understand a task and produce a more appropriate response.

A prompt tells ChatGPT what you want.

Context tells ChatGPT what it needs to know to do the task well.

Useful context can include:

- Background information.
- Files and documents.
- Search results.
- Examples.
- Audience information.
- Goals and constraints.
- Saved preferences.

### Three important questions

Before giving ChatGPT a task, ask:

1. What am I trying to do?
2. What information should ChatGPT use?
3. What would a good response look like?

### Example

**Prompt:**

```text
Write a short internal announcement introducing
a new AI resource hub for employees.
```

This tells ChatGPT what to do, but it may still need:

- What resources are included?
- Who is the announcement for?
- What tone does the company use?
- How should employees access the hub?
- What action should employees take?

Without these details, the response may sound polished but generic.

> If a teammate would need certain information to do the task well, ChatGPT probably needs it too.

## 5.2 What Context Should You Provide?

Use this simple three-part check:

| Check | What to provide |
|---|---|
| Task | The action you want ChatGPT to take. |
| Information | Relevant background, files, sources, examples, audience, goals, and constraints. |
| Good Result | Desired format, tone, length, sections, or criteria. |

### Simple test

Ask yourself:

**What would someone need to know to do this task well?**

For example:

If you ask ChatGPT to create an onboarding checklist, it may need:

- The employee's role.
- Required tools and systems.
- Required training.
- Team expectations.
- First-week goals.

If you ask it to rewrite a message, it may need:

- The intended audience.
- Desired tone.
- Preferred length.
- The action you want the reader to take.

Do not add unnecessary information. Extra context should make the response more focused, not more confusing.

## 5.3 Using Files

Files are useful when ChatGPT needs to work with specific information instead of relying only on general knowledge.

Examples of files you can provide:

- Reports.
- Spreadsheets.
- Policies.
- Meeting notes.
- Templates.
- Past examples.
- Draft documents.

### What can ChatGPT do with files?

| File Type | Possible Use |
|---|---|
| Report | Summarize findings, risks, and recommended actions. |
| Spreadsheet | Identify trends, outliers, and questions to investigate. |
| Policy | Convert requirements into a checklist. |
| Meeting Notes | Extract decisions, owners, and action items. |
| Template | Follow an existing structure and tone. |
| Draft Document | Suggest edits and identify gaps. |

### How to get better results

Do not simply upload a file and say:

```text
Look at this file.
```

Give a clear instruction instead:

```text
Use this file as source material.

Summarize the three most important findings,
list the recommended actions, and flag anything
that may need follow-up.

Do not add information that is not supported by the file.
```

### File best practices

- Share only files relevant to the task.
- Explain what ChatGPT should look for.
- Tell it what output you need.
- Check whether the response accurately reflects the file.
- Ask follow-up questions when information is missing.
- Follow organizational rules when sharing internal information.

## 5.4 Using Search

Files help ChatGPT work with information you already have.

**Search is useful when you need current or external information.**

Use search when you need:

- Recent information.
- Public facts and examples.
- Trusted sources.
- Links and citations.
- Information that may have changed over time.

### What can search help with?

- Finding background information.
- Comparing options.
- Gathering recent examples.
- Checking current guidance.
- Finding public facts before drafting.

### Example search prompt

```text
Use web search to find credible and recent examples
of how organizations use AI at work.

Summarize the examples in simple language
and include links to the sources.
```

Another example:

```text
Search for the latest guidance about [topic].

Summarize what has changed, cite your sources,
and identify anything I should verify before using the information.
```

**Important:** Search does not replace human judgment. Review the sources and confirm that they are reliable.

## 5.5 Saved Preferences, Custom Instructions, and Memory

The course introduces three ways context can be used in ChatGPT.

| Feature | Meaning | Example | Best For |
|---|---|---|---|
| Input | Information provided in a conversation. | A prompt, file, or meeting transcript. | A single task. |
| Custom Instructions | Guidance about how you want ChatGPT to behave. | Keep responses professional and concise. | Recurring preferences. |
| Memory | Information ChatGPT can remember for future conversations. | Your role, projects, or preferred writing style. | Ongoing context. |

### How are they different?

**Input:** Gives ChatGPT information for the current task.

**Custom Instructions:** Describes how you prefer ChatGPT to respond.

**Memory:** Provides information that may be useful across future conversations.

These features do not replace task-specific context. Even if ChatGPT knows your preferences, you should still provide the important details for a particular task.

### Example Custom Instructions

**Work Context**

```text
I work in [role/team/industry].
Tailor examples and suggestions to my day-to-day work,
stakeholders, and business priorities.
```

**Tone and Style**

```text
Keep responses professional, clear, and concise.
Use plain English for a global business audience.
```

**Writing Support**

```text
When helping me write emails, messages, or documents,
use a warm, direct, and polished tone without sounding
overly formal.
```

**Decision Support**

```text
When I ask for advice, give a clear recommendation,
explain the trade-offs, and identify any assumptions.
```

**Accuracy and Clarity**

```text
If something is uncertain, say so clearly.
Do not guess. Explain what information is missing.
```

## 5.6 Module 4 Key Takeaways

Context helps ChatGPT make fewer assumptions.

Remember these four steps:

1. **Explain the task:** Be clear about what you want.
2. **Provide context and sources:** Give it the relevant files, information, examples, and constraints.
3. **Define what good looks like:** Specify the desired format, tone, and level of detail.
4. **Review the result:** Check whether the response accurately reflects the information you provided.

---

# 6. Module 5 — Responsible AI Use

This module focuses on using AI carefully, protecting information, and keeping humans involved in important decisions.

## 6.1 What is Responsible AI Use?

Responsible AI use means understanding when AI is appropriate, what information you should share, and how carefully you need to review its output.

It is not something you do only after completing a task.

It should be part of your workflow from the beginning.

### Three important checks

Before using ChatGPT, ask:

| Check | Question |
|---|---|
| Task | Is ChatGPT an appropriate tool for this task? |
| Information | Am I sharing only what is necessary and allowed? |
| Review | How carefully should a human check the output? |

## 6.2 Choosing the Right Task

ChatGPT is often useful for tasks involving:

- Drafting messages.
- Summarizing public or approved information.
- Brainstorming ideas.
- Organizing notes.
- Rewriting content for another audience.
- Creating checklists and outlines.
- Preparing questions for meetings.

### When should you be more careful?

Some tasks involve decisions that may affect people's:

- Safety.
- Employment.
- Finances.
- Legal rights.
- Medical care.
- Access to essential services.
- General well-being.

ChatGPT may still help organize information, clarify language, prepare questions, or review documents.

However, it should not be the only source relied on for consequential decisions.

> Use ChatGPT to support thinking and drafting. Keep humans responsible for decisions that affect people or carry higher risk.

## 6.3 Sharing Information Carefully

ChatGPT works better with useful context, but that does not mean you should share everything.

Always follow your organization's policies, especially when working with:

- Customer information.
- Employee information.
- Internal company documents.
- Security-related information.
- Confidential business data.

If you are unsure whether something is allowed, check an approved internal resource, such as your manager, security team, legal team, or AI policy guidance.

### Questions to ask before sharing information

1. Is this information actually needed?
2. Is there an approved source or process I should use instead?
3. Can I remove or anonymize sensitive details?
4. Am I allowed to share this information?
5. Is approval required?
6. Can I use a fictional example or template instead?

## 6.4 Minimize and Anonymize Information

Sometimes ChatGPT does not need exact personal or sensitive details to help with a task.

You can reduce unnecessary exposure by:

- Replacing names with labels such as `Customer A` or `Team B`.
- Removing details that are not relevant.
- Sharing only the necessary section of a document.
- Generalizing dates, locations, and identifiers.
- Using fictional examples instead of real private information.

### Example

**Less safe:**

```text
Rewrite this performance feedback message
for employee Maria Gomez.

Include her exact performance score
and all the personal details below.
```

**Safer:**

```text
Draft a generic template for giving performance
feedback to an employee.

Keep the tone clear, respectful, and constructive.
I will add the specific employee details myself.
```

The second approach allows ChatGPT to help with the writing without requiring unnecessary personal information.

## 6.5 Keep Yourself in the Loop

AI can help you work faster, but it does not replace your judgment.

Before using or sharing an AI-generated response, review it.

### Basic review checklist

- Are the facts correct?
- Are names, dates, numbers, and details accurate?
- Is the tone appropriate?
- Is anything missing?
- Does it follow the relevant policies and expectations?

For higher-risk tasks, a more thorough review may be necessary. This could include checking trusted sources, consulting a qualified person, or following an established approval process.

Think of ChatGPT as a thought partner.

It can help create a starting point, but you shape the final result.

## 6.6 Review Intensity Depends on the Task

Not every AI-generated response requires the same level of review.

| Situation | Review Needed |
|---|---|
| Brainstorming ideas for a team event | Light review. |
| Drafting a general update | Check accuracy, tone, and fit. |
| Summarizing a public article | Verify that the summary reflects the source. |
| Working with private or confidential information | Follow internal policies and minimize what you share. |
| Creating content affecting someone's rights, job, health, finances, or access to services | Strong human review or an approved process. |

### Three questions before relying on AI

**Task:** Is AI appropriate for this task?

**Information:** Am I sharing only what is necessary and allowed?

**Review:** How much human review does this output need?

## 6.7 Module 5 Key Takeaways

Responsible AI use comes down to three habits:

1. Choose an appropriate task.
2. Share only the information you are allowed and need to share.
3. Review the output before relying on it.

Human judgment remains essential.

---

# 7. Practical Prompt Templates

These templates combine the concepts from the course into reusable examples.

## 7.1 Beginner Learning Prompt

```text
Act as a patient learning assistant.

I am a beginner studying [TOPIC].

Explain the concept using:
- Simple language
- Short explanations
- Practical examples
- One small exercise

Avoid assuming that I already understand advanced concepts.

At the end, give me one multiple-choice question
to check my understanding.
```

## 7.2 Summarization Prompt

```text
Summarize the material I provide.

Requirements:
- Identify the main ideas.
- Explain important terms.
- Use simple language.
- Organize the information with headings and bullet points.
- Include examples where useful.

Do not introduce unsupported information.
If something is unclear or missing, point it out.
```

## 7.3 Research Prompt

```text
Research [TOPIC] using reliable and relevant sources.

I need:
- A beginner-friendly explanation.
- The most important findings.
- Relevant examples.
- Links to the original sources.
- Any limitations or uncertainties.

Prioritize current information.
Clearly distinguish verified information from assumptions.
```

## 7.4 Prompt Improvement

```text
Improve the following prompt using
Task, Context, and Expectation.

Original prompt:
[INSERT PROMPT]

Identify what information is missing,
then provide a clearer and more effective version.

Do not change the original goal.
```

## 7.5 CLEAR Review Prompt

```text
Review the following AI-generated response
using the CLEAR framework.

C — Complete
L — Logical
E — Evidence
A — Audience
R — Relevant

Identify weaknesses, missing information,
unsupported claims, and areas for improvement.

Then provide a revised version.
Do not invent missing facts.
```

## 7.6 Responsible AI Review Prompt

```text
Help me assess whether the following task
is appropriate for AI assistance.

Task:
[DESCRIBE TASK]

Consider:
1. Is AI appropriate for this task?
2. What information is necessary?
3. Could sensitive information be exposed?
4. Should information be anonymized?
5. What level of human review is needed?

Identify risks and recommend safer alternatives
where necessary.
```

---

# 8. Final Review — What to Remember

This section is designed for quick revision after completing the course.

## The Five Core Lessons

| Module | Main Concept | Remember This |
|---|---|---|
| 1. Introduction to AI | AI and prompting basics | Clear communication helps AI understand what you need. |
| 2. Large Language Models | How LLMs work | Models generate responses using patterns, instructions, and context. |
| 3. Prompting and Evaluation | TCE and CLEAR | Give clear instructions and review the output. |
| 4. Adding Context | Files, search, and preferences | Relevant information reduces guessing. |
| 5. Responsible AI Use | Privacy and human judgment | Use AI carefully and remain responsible for decisions. |

## Two Frameworks Worth Memorizing

### TCE — Writing Better Prompts

- **T** — Task: What do you want?
- **C** — Context: What should the AI know?
- **E** — Expectation: How should the answer look?

### CLEAR — Reviewing AI Responses

- **C** — Complete.
- **L** — Logical.
- **E** — Evidence.
- **A** — Audience.
- **R** — Relevant.

## The Complete AI Workflow

```text
1. IDENTIFY THE TASK
       |
       v
2. WRITE CLEAR INSTRUCTIONS
       |
       v
3. PROVIDE RELEVANT CONTEXT
       |
       v
4. GENERATE THE RESPONSE
       |
       v
5. REVIEW USING CLEAR
       |
       v
6. REFINE IF NECESSARY
       |
       v
7. CHECK RESPONSIBLE USE
       |
       v
8. APPLY HUMAN JUDGMENT
       |
       v
9. USE THE FINAL OUTPUT
```

## Five Things I Should Never Forget

1. AI is a tool, not a replacement for human judgment.
2. A confident response is not necessarily an accurate response.
3. Better prompts come from clear instructions and relevant context.
4. Important information should be checked against trusted sources.
5. Responsible AI use includes protecting information and reviewing outputs.

---

# 9. Personal Learning Reflection

*My personal notes after completing OpenAI Academy — AI Foundations.*

### What I learned

- The basic relationship between AI, LLMs, and ChatGPT.
- How language models generate responses.
- Why AI models can sometimes produce incorrect information.
- How to write better prompts using Task, Context, and Expectation.
- How to evaluate responses using CLEAR.
- How files, search, and preferences provide useful context.
- Why responsible AI use and human judgment matter.

### Skills I want to practice

- Writing more specific prompts.
- Using AI for research and learning.
- Verifying AI-generated information.
- Organizing information into useful documentation.
- Applying AI to practical workflows and projects.

### Final Thought

> Learning how to use AI is not just about knowing what to ask. It is about understanding what information to provide, how to evaluate the response, and when not to rely on it.

**Course completed: AI Foundations — OpenAI Academy.**

---

<sub>Notes organized and rewritten for personal study and future reference. Based on the OpenAI Academy AI Foundations learning material.</sub>

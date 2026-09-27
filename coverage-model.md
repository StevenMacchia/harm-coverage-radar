# Harm coverage model

For each kind of harm, rate five layers of defense on four levels. Coverage is the share of the maximum across the five layers. Compared with a product's risk from an abuse pre-mortem, it shows where risk outruns your defenses.

## Harm areas

| Area | Includes |
|---|---|
| **Child safety** | Child safety |
| **Sexual harm** | Sexual exploitation |
| **Harassment & hate** | Harassment and hate |
| **Violence & self-harm** | Violent and extremist content, Self-harm and wellbeing |
| **AI misuse** | AI misuse |
| **Privacy & physical safety** | Privacy and surveillance, Physical safety |
| **Platform abuse** | Platform integrity, Account security, Illegal and regulated goods |
| **Fraud & financial crime** | Fraud and scams, Financial crime |

## Layers of defense

### Policy

> **Is there a clear rule, with guidance reviewers can apply?**

| Level | What it looks like |
|---|---|
| **0 · None** | No rule covers it. |
| **1 · Partial** | A public rule exists, but reviewers lack detailed guidance. |
| **2 · Solid** | A clear rule with internal guidelines, examples and an owner. |
| **3 · Strong** | Tested against edge cases, reviewed on a schedule, and shaped by appeals data. |

### Detection

> **How do you find it, beyond waiting for user reports?**

| Level | What it looks like |
|---|---|
| **0 · None** | Found only when users report it. |
| **1 · Partial** | Keyword lists or basic filters catch obvious cases. |
| **2 · Solid** | Hash matching, classifiers or behavior signals find most of it proactively. |
| **3 · Strong** | Detection quality is measured, models learn from reviewer decisions, and red teams probe for gaps. |

### Enforcement

> **Can trained people act on it quickly and consistently?**

| Level | What it looks like |
|---|---|
| **0 · None** | No trained reviewers or defined actions. |
| **1 · Partial** | Reviewers handle it without specific training or service levels. |
| **2 · Solid** | Trained reviewers, clear actions and service levels by severity. |
| **3 · Strong** | Specialist reviewers, round-the-clock cover for the worst cases, and escalation to legal and law enforcement. |

### Appeals

> **Can users contest decisions, and do mistakes get fixed?**

| Level | What it looks like |
|---|---|
| **0 · None** | Users can't contest decisions. |
| **1 · Partial** | Appeals go to a general support inbox. |
| **2 · Solid** | A formal appeal with a second reviewer and a response target. |
| **3 · Strong** | Overturn rates are tracked and feed back into policy and training. |

### Measurement

> **Do you know how much of it users see, and how well you respond?**

| Level | What it looks like |
|---|---|
| **0 · None** | Nothing is measured. |
| **1 · Partial** | Report and removal counts only. |
| **2 · Solid** | Prevalence, speed and accuracy are tracked. |
| **3 · Strong** | Metrics have targets and owners, and leadership reviews them. |

## How gaps are found

- **Risk** is the worst pre-mortem score in each area, from 0 to 16, across one product or all of them.
- **Exposed:** critical risk (12 or more) with less than half the coverage.
- **Gap:** high risk (8 or more) with coverage below the risk level.
- **Next steps** take the weakest layers in exposed areas first, weighted toward what matters most for serious harm: detection, enforcement, policy, measurement, appeals. Each area gets its first step before any area gets a second.

---

Part of [T&S Workbench](https://github.com/stevenmacchia/ts-workbench) by [Steven Macchia](https://www.linkedin.com/in/stevenmacchia). Content licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse it freely with credit.

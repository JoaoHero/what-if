<div align="center">

# WHAT IF

### Explore the realities that could have been.

**What If** is an AI-powered platform for exploring alternative realities.

Change one event.
Create a divergence.
Discover what could happen next.

<br />

![Angular](https://img.shields.io/badge/Angular-Frontend-0F172A?style=flat-square\&logo=angular\&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-Backend-0F172A?style=flat-square\&logo=nestjs\&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-0F172A?style=flat-square\&logo=mongodb\&logoColor=white)
![OpenAI](https://img.shields.io/badge/AI-OpenAI-0F172A?style=flat-square\&logo=openai\&logoColor=white)
![Status](https://img.shields.io/badge/Status-MVP-7C3AED?style=flat-square)

<br />

<img
src="./docs/assets/what-if-banner.png"
alt="What If — Explore the realities that could have been"
width="85%"
/>

</div>

---

## ✦ What is What If?

**What If** lets you explore realities that never happened.

You change one event:

> **What if Neymar had never been injured in the 2014 World Cup?**

And the platform creates a new timeline based on that divergence.

```text
Reality ────────────────●──────────────────────
                        │
                        │  What if?
                        │
                        └─────────────── New reality
```

The goal isn't to predict what *would* happen.

It's to explore what **could** happen.

---

## ◉ How it works

```text
Ask a "What if...?"
        ↓
Find the point of divergence
        ↓
Understand the original context
        ↓
Generate possible consequences
        ↓
Explore the new timeline
```

Simple on the outside.

**AI + structured data underneath.**

---

## ✦ Timeline

Every reality is built as a sequence of connected events.

```text
2014              2015              2016              2017

 ●─────────────────●─────────────────●─────────────────●
 │                 │                 │                 │
 ▼                 ▼                 ▼                 ▼

Divergence      Consequence       New Event        Long-term
                                                    Impact
```

Each event can contain:

* Date
* Title
* Description
* Impact
* Characters
* Location
* Plausibility

---

## ◇ Plausibility

Not every alternative event is equally likely.

What If makes that uncertainty visible.

| Level         | Meaning                               |
| ------------- | ------------------------------------- |
| 🟢 **High**   | Strong consequence of previous events |
| 🟣 **Medium** | Possible, but depends on assumptions  |
| 🔵 **Low**    | More speculative outcome              |

> Plausibility is an estimate, not a scientific prediction.

---

## ✦ Example realities

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>⚽ Sports</h3>
      <strong>What if Neymar had never been injured in 2014?</strong>
    </td>
    <td width="50%" valign="top">
      <h3>🏛️ History</h3>
      <strong>What if the Roman Empire had never fallen?</strong>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎬 Fiction</h3>
      <strong>What if Mufasa had survived?</strong>
    </td>
    <td width="50%" valign="top">
      <h3>🦸 Heroes</h3>
      <strong>What if Spider-Man had never been bitten?</strong>
    </td>
  </tr>
</table>

---

## ◉ Built differently

What If isn't meant to be another AI chat.

| AI Chat             | What If             |
| ------------------- | ------------------- |
| Generates an answer | Generates a reality |
| Text conversation   | Visual timeline     |
| Isolated responses  | Connected events    |
| Free-form output    | Structured data     |
| One answer          | A world to explore  |

The AI generates the possibilities.

**What If turns them into an experience.**

---

## ⚡ Tech Stack

|   Frontend  |   Backend  |   Database  |     AI     |
| :---------: | :--------: | :---------: | :--------: |
| **Angular** | **NestJS** | **MongoDB** | **OpenAI** |

The project starts as a **modular monolith**.

No microservices.
No unnecessary infrastructure.
**Build the product first.**

---

## ✦ Architecture

```text
                 ┌─────────────┐
                 │   Angular   │
                 └──────┬──────┘
                        │
                        ▼
                 ┌─────────────┐
                 │   NestJS    │
                 └──┬───────┬──┘
                    │       │
              ┌─────▼───┐ ┌─▼──────────┐
              │ MongoDB │ │ AI Service │
              └─────────┘ └─────┬──────┘
                                │
                           AI Provider
```

AI providers are abstracted so the application isn't locked to a single model.

```text
AIService
   │
   └── AIProvider
          ├── OpenAI
          ├── Gemini
          └── ...
```

---

## 🚀 MVP

The first version has one mission:

<div align="center">

### One question.

### One divergence.

### One alternative reality.

</div>

<br />

* [ ] Create a scenario
* [ ] Detect the divergence point
* [ ] Generate structured events
* [ ] Calculate plausibility
* [ ] Render the timeline
* [ ] Save generated realities
* [ ] Generate a cover image

That's it.

The goal is to make the core experience **good before making it big**.

---

## ◇ What's next?

```text
MVP
 │
 ├── Accounts & history
 ├── Saved realities
 ├── Sharing
 ├── Timeline branches
 ├── Community
 └── What If Engine
```

### Timeline Branches

Eventually, any event can become another **What if?**

```text
                         Reality B
                        /
────────────●──────────●
            │           \
            │            Reality C
            │
       Divergence
```

One timeline becomes many.

---

## 🧠 What If Engine

The long-term idea is to stop treating realities as just generated text.

```text
Event
  ↓
Decision
  ↓
Consequence
  ↓
New Event
  ↓
New Reality
```

Events, characters and consequences become connected data.

Change one event and the system can understand **what else should change with it**.

That's the direction of the **What If Engine**.

---

## 🛠️ Running locally

### Clone

```bash
git clone <repository-url>
cd what-if
```

### Backend

```bash
cd backend
npm install
npm run start:dev
```

### Frontend

```bash
cd frontend
npm install
ng serve
```

Open:

```text
http://localhost:4200
```

---

## ✦ The idea

<div align="center">

Reality happened one way.

**But it didn't have to.**

<br />

# WHAT IF?

*Explore the realities that could have been.*

</div>

---

<div align="center">

## ☕ Like the project?

If you enjoy **What If** and want to support its development:

<br />

<a href="YOUR_BUY_ME_A_COFFEE_URL">
  <img
    src="https://img.shields.io/badge/Buy%20me%20a%20coffee-Support%20What%20If-7C3AED?style=for-the-badge&logo=buymeacoffee&logoColor=white"
    alt="Buy me a coffee"
  />
</a>

<br />
<br />

**Every coffee helps create another reality. ☕**

<br />

Made with curiosity, code and way too many *"what ifs?"*

</div>

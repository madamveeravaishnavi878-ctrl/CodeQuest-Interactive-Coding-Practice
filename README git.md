# CodeQuest --- Interactive Coding Practice Platform

> **Tagline:** Practice. Learn. Improve.

CodeQuest is a web-based learning platform concept designed to help
beginner programmers practise Python, review quiz explanations, and
monitor their learning progress in one place.

-   **Live website:** https://hopeful-code-quest-flow.base44.app
-   **Project type:** B.Tech mini project
-   **Domain:** Web Development / Programming Education / AI & ML
    concepts
-   **Built with:** Base44 (website-building platform)
-   **Project status:** Base44 prototype --- features should be verified
    against the live application before being described as completed.

## Table of Contents

-   [Overview](#overview)
-   [Problem Statement](#problem-statement)
-   [Objectives](#objectives)
-   [Proposed Features](#proposed-features)
-   [How It Works](#how-it-works)
-   [Proposed System Design](#proposed-system-design)
-   [AI/ML Connection](#aiml-connection)
-   [Technology Stack](#technology-stack)
-   [Getting Started](#getting-started)
-   [Testing Checklist](#testing-checklist)
-   [Limitations](#limitations)
-   [Future Enhancements](#future-enhancements)
-   [Learning Outcomes](#learning-outcomes)
-   [Author](#author)

## Overview

Learning to program requires regular practice, feedback, and a way to
identify topics that need more attention. CodeQuest is intended to make
beginner-level Python practice more structured and engaging through
topic-based quizzes, coding exercises, explanations, and progress
tracking.

The project is developed using Base44 to prototype a web application.
The live website can be opened from the link above.

## Problem Statement

Beginner programmers can find it difficult to practise consistently,
understand incorrect answers, and identify weak programming concepts.
Learning resources may be spread across different platforms, while
learners may lack a clear view of their progress.

**CodeQuest aims to provide a centralised, beginner-friendly platform
for Python practice, quiz feedback, learning progress, and
recommendations for further practice.**

## Objectives

-   Provide structured practice for fundamental Python concepts.
-   Organise questions by topic and difficulty.
-   Give learners feedback and explanations where supported.
-   Help learners review quiz results and recognise topics for
    improvement.
-   Explore personalised question recommendations based on quiz
    performance.
-   Build a practical web project that can be demonstrated in a student
    portfolio.

## Proposed Features

The following are the intended feature areas. Check the live application
before marking any item as implemented.

-   **Python topics:** Variables, data types, operators, conditions,
    loops, strings, collections, and functions.
-   **Topic-based quizzes:** Questions grouped by programming concept.
-   **Difficulty levels:** Beginner, intermediate, and advanced, if
    enabled.
-   **Scoring and feedback:** Calculate results and show explanations
    for answers, if supported.
-   **Coding challenges:** Beginner-friendly problems with sample
    input/output.
-   **Progress dashboard:** Summaries of quiz attempts and topic
    performance, if data is saved.
-   **Practice recommendations:** Suggest topics for revision based on
    observed quiz results.

## How It Works

1.  Open the CodeQuest website.
2.  Select an available Python topic or practice activity.
3.  Read each question and choose or submit an answer.
4.  Review the result and any available explanation.
5.  Use the feedback to decide what to practise next.
6.  If progress tracking is available, review saved attempts and topic
    performance.

The exact steps depend on the features enabled in the current Base44
deployment.

## Proposed System Design

A high-level design for the intended application is:

``` text
Learner
   |
   v
CodeQuest Web Interface
   |
   v
Topic Selection and Quiz
   |
   v
Answer Evaluation and Feedback
   |
   v
Quiz Results / Progress Records
   |
   v
Topic Analysis
   |
   v
Recommended Practice
```

This diagram represents the proposed workflow, not a verified
description of Base44's internal implementation. Confirm the actual
database, authentication, and evaluation behaviour before including
implementation-specific claims in a report.

## AI/ML Connection

A useful starting point is a **rule-based recommendation system**:

-   If a learner scores below 50% on a topic, recommend more beginner
    questions for that topic.
-   If the score is between 50% and 79%, recommend additional practice
    at a similar level.
-   If the score is 80% or above, suggest a harder question or the next
    topic.

These thresholds are example rules and can be adjusted. Recommendations
should be based on real quiz results, not fabricated statistics.

A rule-based system is not the same as a trained machine-learning model.
A future version could investigate an ML model after collecting
suitable, consented learning data and defining an evaluation method.

## Technology Stack

  Component                           Technology / approach
  ----------------------------------- -----------------------------------------
  Website creation                    Base44
  User interface                      Base44-supported web interface
  Data storage                        Base44-supported storage, if configured
  Recommendation logic                Proposed rule-based logic
  Version control and documentation   GitHub
  Programming content                 Python learning questions and exercises

Update this table if you confirm additional technologies in the actual
implementation. Do not list a framework, database, or ML model as used
unless you have verified it.

## Getting Started

### Use the live website

1.  Visit https://hopeful-code-quest-flow.base44.app.
2.  Explore the pages and available learning activities.
3.  Try a quiz or practice activity, if available.
4.  Check whether results and progress persist after refreshing or
    returning to the site.

### Repository contents

This repository can contain the project's documentation and supporting
materials, such as:

``` text
CodeQuest/
├── README.md
├── docs/
│   └── project-documentation.md
└── screenshots/
    └── (add genuine screenshots of the application)
```

If you export or sync the source code from Base44, add the exported
files to the repository and update this structure accordingly. A link to
the live website alone does not mean the application's source code is
included in GitHub.

## Testing Checklist

Before presenting the project, test the following in the live
application:

-   [ ] The website opens and navigation works.
-   [ ] Topic selection opens the correct activity.
-   [ ] Answers can be selected or submitted.
-   [ ] Scores are calculated correctly.
-   [ ] Explanations match the correct answers.
-   [ ] Difficulty filters work, if available.
-   [ ] Quiz results are saved, if persistence is implemented.
-   [ ] Progress information matches actual attempts, if available.
-   [ ] Recommendations reflect actual performance, if implemented.
-   [ ] The layout works on mobile and desktop.
-   [ ] Any code-running feature is tested safely and described
    accurately.

Only report test results after you have performed the tests.

## Limitations

-   The available functionality depends on the current Base44
    deployment.
-   A coding challenge interface does not necessarily execute arbitrary
    Python code; verify how answers are evaluated.
-   Rule-based recommendations should not be described as a trained ML
    model.
-   Persistent progress depends on the configured data storage and
    user/session setup.
-   The project should not claim measured learning improvements without
    an appropriate evaluation.

## Future Enhancements

-   Add more Python questions and carefully reviewed explanations.
-   Introduce C and Java practice sections.
-   Add a reliable, sandboxed code execution service if needed and
    feasible.
-   Improve topic-wise analytics and learning history.
-   Add more personalised recommendations.
-   Introduce achievements and learning milestones.
-   Conduct usability testing with students and document the results.
-   Evaluate an ML-based recommendation approach if enough suitable data
    becomes available.

## Learning Outcomes

This project can provide experience in:

-   Planning and prototyping a web application.
-   Organising programming questions by topic and difficulty.
-   Designing quiz and feedback workflows.
-   Thinking about progress tracking and recommendation logic.
-   Documenting a software project using GitHub.
-   Testing functionality and identifying limitations honestly.

## Author

**M.V. Vaishnavi**\
B.Tech --- Computer Science and Engineering (AI & ML)\
Gouthami Institute of Technology and Management for Women

## Project Link

**Live Demo:** https://hopeful-code-quest-flow.base44.app

------------------------------------------------------------------------

*This README describes the project's goals and proposed design. Review
it against the current live application and update the feature and
technology descriptions to match what is actually implemented.*

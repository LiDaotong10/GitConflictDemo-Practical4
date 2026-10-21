# GitConflictDemo-Group1

**COMPX310 — Practical 4: Collaborating with GitLab and Resolving Merge Conflicts**

A small Android application with two buttons, used by a group of two students to
practise collaborative Git work: branching, merge requests, producing a merge
conflict on purpose, resolving it by hand, and merging the resolved feature back
into `main`.

## Group members

| Role | Student | Student ID | Feature branch |
|------|---------|-----------|----------------|
| Student 1 | Li Daotong | 20243006983 | `feature-red-button` |
| Student 2 | _<Liu Linrui>_ | _<20243006995>_ | `feature-green-button` |

Both students work on **this same repository and this same Android Studio
project** — no separate projects.

## The exercise

1. `Student 1` changes the button colour to **red** on `feature-red-button`.
2. `Student 2` changes the button colour to **green** on `feature-green-button`,
   starting from the *same* original commit.
3. `feature-red-button` is merged into `main` first (Merge Request #1).
4. `feature-green-button` is then merged (Merge Request #2) — Git cannot decide
   between red and green on the same lines of
   `app/src/main/res/layout/activity_main.xml`, so a **merge conflict** occurs.
5. The group resolves the conflict by hand, tests the app, commits the
   resolution and completes the merge.

## Running the app

Open the folder in Android Studio, let Gradle sync, then Run on an emulator.

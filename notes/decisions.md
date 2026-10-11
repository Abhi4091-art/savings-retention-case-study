# Decisions log

Each entry: what was decided, why, and what the alternative was.

## 1. Problem framing
**Decision:** Find what drives retain vs close at maturity, and outline a model
that gives each customer a probability of retaining.
**Why:** That's what the brief asks. Setting the "right rate" is the business use
of the model, not something the data alone can answer: it needs cost of funding,
and offered rates weren't set randomly.

## 2. Tools
**Decision:** Python for analysis, Excel for summary tables and cross-checks.
**Why:** Python is repeatable (if a decision changes, re-run everything). Excel
is easy for others to check and matches how the team works.
**Alternative:** Excel only. Rejected as slower, more error-prone, and weak
for the multivariate check.

## 3. Repo
**Decision:** Private GitHub repo, data included.
**Why:** Keeps everything in one place. Private because the data is
interview material.
# Bad Prompt
```markdown
We have a hackathon problem where we need to optimize deliveries between stores. Can you come up with the best algorithm and write the code? The problem statement is attached.
```

# Good Prompt
```markdown
# Task

Design and implement optimisation algorithms for a hackathon project.

Your goal is to maximise the competition score, not just produce a correct solution.

---

# Problem

We have a fleet of delivery vehicles that distribute stock from a central warehouse to multiple stores.

Each store has:
- Product demand
- Delivery deadline
- Geographic location

Each vehicle has:
- Maximum carrying capacity
- Maximum driving distance per day
- Starts and ends at the warehouse

## Objective

Optimise deliveries to:

1. Maximise the number of stores whose demand is completely fulfilled.
2. Minimise the total distance travelled.

If these objectives conflict, prioritise them in this order unless the problem statement specifies otherwise.

---

# Constraints

The solution should scale to approximately:

- 500 stores
- 50 vehicles

It should complete within a few minutes on a standard laptop.

A high-quality heuristic is preferred over an exact algorithm if it achieves similar scores much faster.

---

# Resources

Read `docs/problem_statement.pdf` before proposing a solution.

If the document is large, process it incrementally, summarise important findings, and work in logical checkpoints to avoid context window issues.

---

# Competition Context

- Unlimited submissions are available.
- Optimise for leaderboard performance.
- Recommend experiments worth testing between submissions.

---

# Deliverables

Implement at least **three distinct approaches**.

For each approach provide the following in markdown files:

- Why it was chosen
- High-level implementation plan
- Core pseudocode
- Computational complexity
- Strengths, weaknesses, and possible improvements

Also include a comparison of the approaches and recommend which to implement first.

---

# Working Style

Before implementing:

- Explain major design decisions and trade-offs.
- Compare alternatives before choosing one.
- Highlight risks and validation strategies.
- Prefer modular, maintainable solutions.

---

# Assumptions and Missing Information

Before proposing a solution:

- Identify missing information.
- List all assumptions.
- Explain how each assumption could affect the solution.
- If missing information could materially change the design, ask clarifying questions instead of guessing.
```
# PL/SQL Practical Solutions — Kaushik (Roll No. 38)

Individual `.sql` files, one per exercise, ready to commit to GitHub as-is.

## Structure

```
unit1/          P1_1.sql  .. P1_23.sql   (Block structure & datatypes — 23 exercises)
unit2/          P2_1.sql  .. P2_8.sql    (Control structures — 8 problems)
cursors/
  schema_setup.sql                       (run first — creates the Library schema used below)
  section2/     Q1.sql .. Q12.sql        (Simple/explicit cursors)
  section3/     Q1.sql .. Q12.sql        (Parameterised cursors)
  section4/     Q1.sql .. Q6.sql         (Trace / debug / short answer)
```

## Notes

- All roll-number-seeded values use **roll_no = 38**.
- A few problems needed personal details not provided (home city, birth month,
  exact last-semester marks) — reasonable placeholder values were used and are
  flagged with a comment in the file (e.g. `P1_6.sql`, `P1_7.sql`, `P1_19.sql`).
  Swap in your real values before submitting if your instructor checks those.
- Unit 1 & 2 assume the standard Oracle `HR` sample schema (`employees`,
  `departments`) is available.
- Cursor exercises assume `cursors/schema_setup.sql` has been run first.

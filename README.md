# Robust Pronoun Fidelity for Vietnamese

Standalone repository for generating Vietnamese pronoun annotation instances.

## Contents

- `generate_vietnamese_instances.py` — samples balanced instance rows.
- `pronouns.py` — pronoun terms used by the generator.
- `tasks_vi.xlsx` and `context_vi.xlsx` — source task and context data.
- `sampled_for_humans_vietnamese.tsv` — current 600-row human annotation sample.
- `vietnamese_instances_600.tsv` — companion 600-row TSV from the source project.

## Run

From this directory, run:

```bash
python3 generate_vietnamese_instances.py
```

The script writes `sampled_for_humans_vietnamese.tsv` in this directory. It uses only the Python standard library.

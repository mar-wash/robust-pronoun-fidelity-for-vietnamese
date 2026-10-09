# Robust Pronoun Fidelity for Vietnamese

Standalone repository for generating Vietnamese pronoun annotation instances.

## Contents

- `Instance-generator/generate_vietnamese_instances.py` — samples balanced instance rows.
- `Instance-generator/pronouns.py` — pronoun terms used by the generator.
- `Instance-generator/tasks_vi.xlsx` and `Instance-generator/context_vi.xlsx` — source task and context data.
- `Instance-generator/sampled_for_humans_vietnamese.tsv` — current 600-row human annotation sample.
- `Instance-generator/vietnamese_instances_600.tsv` — companion 600-row TSV from the source project.

## Run

From the repository root, run:

```bash
python3 Instance-generator/generate_vietnamese_instances.py
```

The script writes `Instance-generator/sampled_for_humans_vietnamese.tsv`. It uses only the Python standard library.

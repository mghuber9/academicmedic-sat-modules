# Academic Medic — SAT Modules

This repository hosts SAT-style math practice modules using an image-based
question bank and a reusable SAT test template.

## Repository Structure

/
├── index.html # SAT online template (entry point)
├── modules/
│ └── module_demo_22.json # Example 22-question SAT module
├── banks/
│ └── algebra_linear_eq_1var_easy_p01/
│ ├── bank.json
│ └── images/
│ ├── 0adbe034_q.png
│ ├── fa80893a_q.png
│ └── ...
└── docs/
└── README.md


## Notes
- Banks contain reusable questions extracted from PDFs.
- Modules are lightweight JSON files that select questions from banks.
- index.html loads a module file and renders a full SAT-style experience.

Future plans:
- Multi-bank semi-random module generation
- Topic/difficulty balancing
- Dynamic parameterized questions

# dataset_trustytutors

Anonymized conversational logs from student–AI interactions and tutor impersonation experiments, stored as CSV files with sender and message fields, for research on dialogue systems, educational AI, and tutoring strategies.

## Dataset Overview

This repository hosts anonymized conversational logs collected from two experimental settings:
1. **Student experiments** — real-world student interactions with AI agents.
2. **Tutor impersonation experiments** — simulated interactions including a student’s baseline knowledge through dialogue and following tutor interactions.

Each CSV file uses a simple two-column schema:
- **Remetente** — the sender of the message (Aluno, Utilizador, Tutor, or Avaliador)
- **Mensagem** — the text content of the message, including protocol tags such as `[STUDENT]`, `[TUTOR]`, or `[USER]`. These tags can be ignored by researchers, but were used during the experiments to indicate which Python routine should run next.


## Usage

Researchers can use this dataset to:
- Analyze real student–AI conversational patterns
- Evaluate tutoring and feedback strategies
- Train and benchmark dialogue systems in educational contexts

## Citation
If you use this dataset in your research, please cite:


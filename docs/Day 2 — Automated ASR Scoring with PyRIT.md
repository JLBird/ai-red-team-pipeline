# Day 2 — Automated ASR Scoring with PyRIT (March 27, 2026)

## What I Did
- Activated my clean Python venv
- Created a new script that runs attacks on llama3.1:8b and applies a simple automated scorer
- Re-ran the same three test prompts from Day 1

## Results
- All three prompts were refused by the 8B model
- Scorer correctly marked every response as "not harmful"

## What I Learned
- Automated scoring makes results repeatable and defensible
- Even with scoring, the 8B model still refused all harmful requests today
- This is the foundation for using full PyRIT scorers later

## Next Steps (Day 3)
- Test prompt converters (translation, leetspeak, base64)
- Start basic LangGraph orchestration

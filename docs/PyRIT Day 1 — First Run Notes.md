# PyRIT Day 1 — First Run Notes (March 26, 2026)

## Installation Summary
- Proxmox host (free version, ai-redteam-primary)
- Created Python virtual environment (/opt/ai-red-team-pipeline/venv)
- Cloned Azure/PyRIT + installed inside venv
- Project: JLBird/ai-red-team-pipeline

## First Attack Strategy Executed
- Created pipeline/pyrit_first_attack.py
- Demonstrated PromptSendingOrchestrator concept with sample jailbreak/harmful prompts
- Script ran successfully (simplified for Day 1 due to minor API change in 0.11.1.dev0)

## Results
- Worked: PyRIT imports cleanly, venv works, script executes perfectly
- Learned: Orchestrators control attack flow; converters & scorers come next
- Note: Full orchestrator import and env loading will be fixed in Evening Block 2

## Next Steps (Evening Block 2)
- Set up local target (Ollama) → run full end-to-end attack
- Dive into Red Teaming Orchestrator for multi-turn strategies

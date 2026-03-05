TutorSwarm：An Agentic Engineering experiment: A multi-agent system that acts as a personalized technical tutor.
This project demonstrates an automated learning pipeline driven by **5 heterogeneous AI agents**, showcasing system decomposition, human-in-the-loop (HITL) workflows, and prompt engineering.

Architecture (The Agent Swarm)
This system implements a modular pipeline where each agent has a specialized role:
1. Curriculum Architect: Decomposes complex topics into a structured, learnable syllabus.
2. Theory Instructor: Generates personalized Markdown lessons with clear examples.
3. Lab Engineer: Automatically creates interactive TypeScript practice exercises with TODOs.
4. QA Grader: Performs static analysis and provides constructive feedback on user code.
5. Knowledge Librarian: Summarizes lessons and compiles a professional `notebook.md` for long-term retention.


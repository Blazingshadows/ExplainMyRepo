## Session 1 — done
- Orchestrator now fetches real repos
- Tested against psf/requests — working

## Session 2 — start here
- Update the LLM timeout in Settings — cloning takes time, 20s is too short for large repos
- Add EXPLAIN_MY_REPO_GEMINI_MODEL=gemini-2.0-flash-lite to .env.example
- Write Dockerfile
- Deploy to DigitalOcean
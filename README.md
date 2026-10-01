# ElevenLabs Interview Agent (CallKaro AI)

A Hinglish voice agent built on ElevenLabs that runs first-round screening
calls for the Forward Deployed Engineer (FDE) Intern role at CallKaro AI.

## What it does
- Runs a 12 to 15 minute interview in Hindi/English (Hinglish)
- Stages: consent, warm-up, project deep-dive, prompt-engineering scenario,
  debugging scenario, client communication, logistics, candidate Q&A
- Honest about being an AI if sincerely asked
- Never reveals scoring or promises selection

## Design choices
- One question per turn, with stage gates so it cannot skip ahead
- Interview questions map directly to the FDE job description
- Devanagari for spoken lines and English for technical terms, so TTS
  pronounces them cleanly
- Guardrails: no sensitive data collection, no discriminatory questions,
  no hiring promises

## Files
- `prompt/system_prompt_hinglish.md`: the full agent system prompt
- `prompt/first_message.txt`: the agent's opening line

## Try it
Demo link available on request.

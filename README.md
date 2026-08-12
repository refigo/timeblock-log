# timeblock-log

Public record of work sessions.

Each session is registered **before** it happens (`started.json`: which broadcast,
which sampling seed, which judge) and judged **after** (`verdict.json`). Both
passes and failures are committed — a session missing from this log is a visible
hole, not a quiet non-event.

No video or screenshots are published here. Only the verdict.

Tool: https://github.com/refigo/obs (agent_ws/timeblock-verify)

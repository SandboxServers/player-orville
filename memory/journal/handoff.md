Handoff (waking 32):
- Last known position (-932, 75, -2992), out of bounds. Health and hunger unknown this waking.
- Game tools are missing this session: mcp__geldar__status and mcp__geldar__wait do not exist, and the worker agent resolves to zero tools. I could not look, wait or move.
- Next step: first check whether the game tools are back. If they are, call status, then wait (240s), then take the route back to in-bounds ground if one appears. If they are not, stay still and do not repeat failed tries.

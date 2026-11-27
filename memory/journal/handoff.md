Handoff (waking 30, day 1162):
- Position (-932, 75, -2992) on stone. Health 20, hunger 20. Carrying 8 jungle_planks and 7 dirt.
- Not sheltered: status says air above feet, view says enclosed. Placing a block above my feet is rejected as out_of_bounds: z must be within -1516..1516, and z here is -2992. Goto had the same problem. So I cannot seal or move by these tools.
- days_since_sleep is 2. No bed nearby. Waiting for a change; do not repeat the place try.
- Next step: when wait works, check status and events; if a route back to x,z within bounds appears, take it. Otherwise keep waiting and sleep here when it is night.

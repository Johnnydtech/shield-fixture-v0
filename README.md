# shield-fixture-v0

Deliberately vulnerable. Used by Shield's audit-engine tests. Do not deploy.

The `src/config.ts` file contains a hardcoded fake OpenAI key — Shield's recon
skill should flag this on every audit run.

_Last poke: Fri May 15 16:39:34 EDT 2026_
_Audit trigger: 2026-05-15T20:41:50Z_

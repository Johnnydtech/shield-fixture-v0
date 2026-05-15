# shield-fixture-v0

Deliberately vulnerable. Used by Shield's audit-engine tests. Do not deploy.

The `src/config.ts` file contains a hardcoded fake OpenAI key — Shield's recon
skill should flag this on every audit run.

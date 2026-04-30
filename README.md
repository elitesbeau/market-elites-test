# Market Elites Desktop — Test Sandbox

Sandbox for testing new features before porting to the live site.

**Live:** https://elitesbeau.github.io/market-elites-desktop/
**Test:** https://elitesbeau.github.io/market-elites-test/

Different origin = isolated localStorage. Same Firebase project, but writes to namespaced paths (`/bugReports_test/`, etc.) so test data doesn't pollute production.

Features in flight:
- Bug reporter (Stage 1: in-app modal, auto-context capture, Firebase write, Discord webhook ping)

Once a feature is stable here, it gets ported to `elitesbeau/market-elites-desktop`.

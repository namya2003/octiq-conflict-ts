# octiq-conflict-ts

Fixture for testing the imported-repo sync CONFLICT path (OSW-1128).

`src/greeting.ts` is the conflict target: Octiq edits one line locally, a GitHub
commit rewrites the same line, and the sync has to park a conflict instead of
choosing a side.

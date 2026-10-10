# Strategic Voting & Arrow's Impossibility Theorem Simulator

Voting paradox simulator that runs five different voting methods on the same electorate and highlights when they produce conflicting winners — directly demonstrating Arrow's Impossibility Theorem.

## Key Features

- **Five voting methods**: Plurality, Borda Count, Condorcet pairwise, Instant Runoff (IRV), and Approval voting run simultaneously
- **Configurable electorate**: 3–5 candidates and 3–5 voter groups with adjustable group sizes and full preference rankings
- **Arrow's Theorem detection**: automatically flags when different methods produce different winners with an explanatory note
- **Condorcet cycle visualiser**: detects and displays intransitive majority preference cycles (A > B > C > A)
- **localStorage persistence**: last scenario is saved and restored on page reload

# Data files cited by the site

Each file below is named as a source on a goaliq.app page. Nothing else from the model repository's data/ is published.

- `data/gw_calls.json`: goaliq.app/fpl, 'Gameweek calls, logged and scored'. One row per call the model made before the deadline, with the points it scored.
- `data/model_squad_frozen/`: goaliq.app/fpl, the squad each captain call came from. One file per gameweek, written before that gameweek's deadline.
- `data/fpl_xp_gw_accuracy.json`: goaliq.app/fpl accuracy table and goaliq.app/fpl/points. Error of the frozen projection against what each player scored.
- `data/fpl_xp_frozen/`: goaliq.app/fpl, the frozen expected-points projection. One file per gameweek; the commit that added it is dated before the deadline.
- `data/fpl_elite_managers.json`: goaliq.app/fpl, what the top-ranked managers own and moved.
- `data/fpl_elite_ownership.json`: goaliq.app/fpl, effective ownership by rank tier.
- `data/spl_deadline_snapshots/`: pro.goaliq.app/spl, the Swiss Pro League projection pinned at the first kickoff of each round. Gameweeks 1 to 4 were added to git in one backfill on 3 September 2026; the provenance block inside each file names the build commit and the time it was generated.
- `data/prediction_log.json`: goaliq.app and goaliq.app/predictions, the match prediction track record. One row per match: the model's probabilities, when the row was logged (logged_at), and the result once the match was played.

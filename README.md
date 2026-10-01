# Sports Intelligence & Tournament Analytics

Probabilistic sports analytics project combining multidimensional team-strength inputs, Poisson goal modelling and Monte Carlo tournament simulation.

## What it does
- Represents 48 teams using FIFA/Elo-style strength, possession, attack/defence, recent form, squad depth, injury risk and venue context.
- Converts team/context inputs into expected-goal parameters and simulates match scores using Poisson draws.
- Implements full group-stage and knockout progression logic.
- Runs 10,000 complete tournament simulations and aggregates R16, quarter-final, semi-final, finalist and championship probabilities.
- Produces probability tables and visualisations for scenario-based sports decision analysis.

## Resume alignment
This repository supports the **Sports Intelligence & Tournament Analytics** project on my JioStar Data Analytics resume. The tournament simulator was co-developed with . The separate Moneyball SQL team exercise referenced in the resume is documented in `moneyball_sql_case_notes.md`.

## Run
Open the notebook in Jupyter/Colab and run all cells.

```bash
pip install -r requirements.txt
```

## Notes
The model is a scenario/simulation engine, not a claim of certain tournament outcomes. Hard-coded or derived strength/context inputs should be treated as modelling assumptions unless independently sourced.



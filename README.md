# SnakeOil [WIP]

Agent-based modeling approaching to trying to discover a sensible approach to crypto-currency trading and other highly speculative high risk ventures

# Design

Turn based approach between assets, agents, and strategies

## Agents

- Has a stable monthly income
- Has living expenses
- Wants to net present value
- Has a collection of strategies
- opportuness and robustness which change based upon amount of capital
- Robustness should depending upon minimum thresholds as described by Piketty's analysis on fortune sizes and expected returns on capital

## Assets

- A linear combination of payoffs given between an erlang, gaussian, and power-law distribution
- Values are generated in the market
- Asset values are unknown until measured in the market via transaction
- 

where `t` is my duration of investment (aka vesting schedule). Uncertainty enters through all my `Weight` functions. I currently don't have a model for how my `Weight` functions

## Strategy

- Duration
- Buy-in criteria
- Exit criteria

# References

- Julia roots library for file structure https://github.com/JuliaMath/Roots.jl
- Model analysis and decision support http://madsjulia.github.io/Mads.jl/
- Julia by example https://juliabyexample.helpmanual.io/
- Learn x in y minutes for julia https://learnxinyminutes.com/docs/julia/
- julia express http://bogumilkaminski.pl/files/julia_express.pdf
- information gap theory https://en.wikipedia.org/wiki/Info-gap_decision_theory
# The Greeks

The Greeks are named sensitivities that describe how an option's theoretical value changes when one input changes. They are estimates from a pricing model, not guarantees, and they shift as conditions change.

**Delta** The estimated change in option value for a one-unit change in the underlying price. Often also read as a rough sense of how the option behaves relative to the underlying.

**Gamma** The estimated change in delta for a one-unit change in the underlying price. It describes how quickly delta itself moves.

**Theta** The estimated change in option value as one unit of time passes, holding other inputs constant. It is usually negative for option holders, reflecting time decay of extrinsic value.

**Vega** The estimated change in option value for a change in the implied volatility of the underlying.

**Rho** The estimated change in option value for a change in interest rates.

**Implied volatility** The level of expected future movement that the current option price implies, given a pricing model. It is derived from the price, not measured directly, and it changes constantly.

**A caution on the Greeks** Every Greek is a model output based on assumptions. They are useful for understanding sensitivity in the abstract. They are not promises about what a position will do, and relying on them as if they were certainties is a known way to be surprised.

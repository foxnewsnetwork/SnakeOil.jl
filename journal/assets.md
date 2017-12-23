# Assets

Here I attempt to describe some basic principles of assets and value

# Assumptions

My base assumption:

- willingness is scalar
- ability to trade is scalar
- desire is scalar

My operator assumptions (as in I assume these exist):

- d is an incremental (aka marginal) difference
- i is inverse (i.e. inversely porportional)
- p is perceived (i.e. my guess at someone else's values via empathy and theory of mind)
- f is future (i.e. the value of something in the future; obviously uncertainties abound)
- m is market value (i.e. when willingness is forced into an actual transaction)
- xavg is some form of market average and has to do with how various exchange display price - a matter of UI - this is effectively a  weighted sum
- t is forced trade binary operator; may not always succeed

## Willingness

d Willingness to trade = i d Ability to trade + Desire for subject - Desire for object

### Caveats

- I don't quite know what the units of "willingness to trade" is yet
- Ability to trade is measurement of the "cost of trading"
- I don't quite know what the units of "desire" is

## Desire

d Desire for X = d p f Market Value of X

## Market Value

Market Value of X = xavg( willingness t willingness )

This suggests to me there is some sort of willingness vector - notably, willingness is some sort of state vector and that `t` is some sort of matrix operator

## Ability

d Ability = d Fees

# Operators

## Future
`f` the operator, for all intents and purpose is a linear projection into the future:

`f x = x + dx/dt * dt`

## Perception
The `p` operator represent a perception of belief

- I'm more likely to believe something if other people also believe it
- 
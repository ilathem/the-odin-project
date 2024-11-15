# Transitions

1. Are all CSS properties animatable?

Yes, unless otherwise specified.

2. What are the long and short hand notations for transitions?

Long: `transition-behavior` (how it inherits from parents),
`transition-delay` (how long until the transition starts),
`transition-duration` (how long the transition lasts),
`transition-property` (which property is getting the transition),
`transition-timing-function` (how the transition frames are distributed).
Shortand is `transition: name duration easingFunction delay`.

3. What is the stacking context?

The 3D dimensional conceptualization of the elements on a z-axis facing the user.

4. Why do you need to keep an eye on repaints?

To make the webpage more performant, especially on low-power devices.

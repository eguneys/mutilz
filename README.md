# mutilz
Utility math functions for graphics programming like random choices, smoothstep round etc.

_PI_ constant PI
_TAU_ constant PI * 2.0

_rad(degree)_ convert degree to radian


_rand(min, max)_ random float between min, max

_randInt(min, max)_ random integer between min, max

_arand(values)_ pick a random item from an array

_weightedChoice(weights)_ pick a random value out of given items based on given weights. 
Input is in the form `[[item, weight], [item2, weight2]]`, where weight is between 0 and 1,
 and all weights should add up to 1.

_clamp(v, min, max)_ clamp v to min and max

_usin(v)_ sin value in range 0 and 1

_smoothstep(min, max, value)_ smoothstep value

_round(v, d = 100)_ round value to `d` digits

_map(n, start1, stop1, start2, stop2)_ map value `n` from range `start1/stop1` to `start2/stop2`


# mutilz
Utility math functions for graphics programming like random choices, smoothstep round etc.

## Usage

`yarn add mutilz`

    import * as u from 'mutilz';

    console.log(u.PI);

`PI` constant PI
`TAU` constant PI * 2.0

`rad(degree)` convert degree to radian


`rand(min, max)` random float between min, max

`randInt(min, max)` random integer between min, max

`arand(values)` pick a random item from an array

`weightedChoice(weights)` pick a random value out of given items based on given weights. 
Input is in the form `[[item, weight], [item2, weight2]]`, where weight is between 0 and 1,
 and all weights should add up to 1.

`clamp(v, min, max)` clamp v to min and max

`usin(v)` sin value in range 0 and 1

`smoothstep(min, max, value)` smoothstep value

`round(v, d = 100)` round value to `d` digits

`map(n, start1, stop1, start2, stop2)` map value `n` from range `start1/stop1` to `start2/stop2`


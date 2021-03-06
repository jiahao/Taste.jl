# Taste.jl

[![Build Status](https://travis-ci.org/jiahao/Taste.jl.svg?branch=master)](https://travis-ci.org/jiahao/Taste.jl)

A simple package for computerized human-computer olfaction and gustation
interactivity.

## Support for Integrated Demand-driven Instant Olfaction Technology Screens

As part of computer manufacturers' ongoing efforts to provide ever-immersive
user experiences, some computers now provide experimental support for
human-computer interactivity through olfactory and gustatory mechanisms.

Lucky users of modern computers are now able to harness their tastebuds to
interact with their favorite programming language, Julia. This package provides
access to undocumented gustation functionality available through the latest LCD
display technology, and provides rudimentary query functions for Big Data
acquisition and analysis.

```jl
julia> x = measureumami() #Place tastebuds on Modern Umami Sensor, located just above the top center of the screen on most modern notebooks.

Taste.うま味{Float64}(16.5419921875)

julia> issavory(x)

true

julia> svd(x) #In this case, the user tasted a grain of MSG

Bitterness: 2.464948920533061e-7
Saltiness: 0.004293918548302065
Savoriness: 0.9996140820830358
Sourness: 0.0
Sweetness: 0.0
```

# PID Controller

## Parameter

### P
Proportional term, works directly proportional to CTE.

### I
Integral term is proportional to CTE and to it's duration.

### D
Derivative term represents the error slope over time.


## Parameter selection

P is choosen smal since it is bad idea hectic pull on the steering wheel.
I is very smal in this case since it becomes bigger if cte decrease slowly, this means we would probabbly be allready off the road.
D is choosen high since it is very helpfull to adjust steering in a curve.
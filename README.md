# numerical-analysis

Some notes about numerical algorithm.

## Numerical stable


### Round-off error

An example show how to calculate pi by LiuHui method.
The basic idea is, from a hexagon, with radius 1, all 6 edge length 1, split an edge by a ray from centre O through midpoint of the edge, caculate length of two new chords.
Repeat until the new chords are small enough, therefore, the regular polygon will converge to a circle with same radius.  

LiuHui method [[References](https://github.com/thtang/Introduction-to-Numerical-Analysis/blob/master/The%20Art%20of%20Numerical%20Analysis/lecture-201.pdf)]
![LiuHui method][LiuHui method]

[LiuHui method]: https://github.com/ntp28459hteam/numerical-analysis/blob/master/images/LiuHui.png "LiuHui method"

We have S<sub>n</sub>=1 - S<sub>n-1</sub>
### Cholesky decomposition (hmmlearn)

# TODO:

- [ ] [Github markdown and math symbol](https://stackoverflow.com/questions/11256433/how-to-show-math-equations-in-general-githubs-markdownnot-githubs-blog)

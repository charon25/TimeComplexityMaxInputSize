# Maximum size of input according to the time complexity and maximum number of operations

This table gives the maximum input size $n$ you can use with an algorithm of a given complexity according to the maximum number of operations/units of time allowed.

This of course does not take into account any leading coefficients or more complicated expressions of the time complexity, but it gives a rough estimate.

For instance, if an $\mathcal{O}(n\log n)$ algorithm is used with a maximum number of operations of 1,000,000, the input should not be grater than 88,000.

For every computation, the chosen base of the logarithm is $e$.

|Complexity|Example| $10^6$ | $10^9$ | $10^{12}$ |
|---|---|:---:|:---:|:---:|
| $\mathcal{O}(\log\log n)$ |Interpolation search| $10^{1.3\cdot 10^{4.3\cdot 10^5}}$ | $10^{3.5\cdot 10^{4.3\cdot 10^{8}}}$ | $10^{9.4\cdot 10^{4.3\cdot 10^{11}}}$ |
| $\mathcal{O}(\log n)$ |Binary search| $10^{4.3\cdot 10^5}$ | $10^{4.3\cdot 10^{8}}$ | $10^{4.3\cdot 10^{11}}$ |
| $\mathcal{O}(n^{1/3})$ |   | $10^{18}$ | $10^{24}$ | $10^{36}$ |
| $\mathcal{O}(\sqrt n)$ |Divisors of $n$ | $10^{12}$ | $10^{18}$ | $10^{24}$ |
| $\mathcal{O}(n)$ |Array scan| $10^6$ | $10^9$ | $10^{12}$ |
| $\mathcal{O}(n\log\log n)$ |Sieve of Erastothenes| $3.9\cdot 10^5$ | $3.4\cdot 10^8$ | $3.1\cdot 10^{11}$ |
| $\mathcal{O}(n\log n)$ |Quick sort| $8.8\cdot 10^4$ | $5.6\cdot 10^7$ | $4.1\cdot 10^{10}$ |
| $\mathcal{O}(n(\log n)^2)$ |Shell sort| $1.1\cdot 10^4$ | $4.3\cdot 10^6$ | $2.2\cdot 10^9$ |
| $\mathcal{O}(n\sqrt n)$ |Divisors $\forall k\leq n$ | $10^4$ | $10^6$ | $10^9$ |
| $\mathcal{O}(n^2)$ | $n$ x $n$ grid scan| $10^3$ | $3.2\cdot 10^4$ | $10^6$ |
| $\mathcal{O}(n^2\log n)$ |   | $407$ | $10^4$ | $2.8\cdot 10^5$ |
| $\mathcal{O}(n^2\sqrt n)$ |   | $251$ | $398$0| $6.3\cdot 10^4$ |
| $\mathcal{O}(n^{\log_2 7})$ |Strassen's algorithm <br> for matrix multiplication|$137$|$1600$| $1.9\cdot 10^4$ |
| $\mathcal{O}(n^3)$ |Naive matrix multiplication|$100$|$1000$| $10^4$ |
| $\mathcal{O}(2^n)$ |Power set|$20$|$30$|$40$|
| $\mathcal{O}(n\cdot 2^n)$ |   |$16$|$25$|$35$|
| $\mathcal{O}(n^2\cdot 2^n)$ |TSP via <br> dynamic programming|$13$|$21$|$30$|
| $\mathcal{O}(e^n)$ |   |$14$|$21$|$28$|
| $\mathcal{O}(10^n)$ |   |$6$|$9$|$12$|
| $\mathcal{O}(n!)$ |Naive TSP|$9$|$12$|$14$|
| $\mathcal{O}(n^n)$ |   |$7$|$9$|$11$|


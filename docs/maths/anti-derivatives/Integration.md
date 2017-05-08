# Integration

### *Type - 1*

We know,

> ### $\frac{d[x^n]}{dx} = n.x^{n-1}.1$

or,

> ### $\frac{d[f(x)^n]}{dx} = n.f(x)^{n-1}.f'(x)$

Here the differentiation of the function in the left gives us the expression on the right hand side.

As integration is the inverse of differentiation, therefore integration of the expression on the right  hand side gives us the function on the left hand side.

or,

> ### $\int n.f(x)^{n-1}.f'(x) = f(x)^n + c$

or,

> ### $\int f(x)^{n-1}.f'(x) = \frac{f(x)^n}{n} + c$

here as **$c$** and **$n$** both are constants **$\frac{c}{n}$** is also constant.

For convenience the above formula can be written as,

> ### $\int f(x)^{n}.f'(x) = \frac{f(x)^{n+1}}{n+1} + c$



***Meaning of the constant $c$***

We know the derivative of a function gives us the slope of the function at any point, hence integration of the slope will give us the function. But there are many function which when differentiated gives us the same slope therefore the expression **$f(x) + c$** is written to represent all of those functions. 

***Application of the formula***

When integrating an expression which consists of product of the function **$f(x)$** raised to some power **$n$** and the derivative of the base (the function) **$f'(x)$**, then the anti-derivative can be written as the division of the function raised to the power of **$f(x)^{n+1}$** by **$n+1$**. 

*Examples*

1. #### $\int sin^3x.cosxdx = \frac{sin^4x}{4} + c$

   ​

2. #### $\int (2ax + b)\sqrt{ax^2+bx +c}\ dx$

   #### $= \int (ax^2+bx +c)^{1/2}(2ax + b)dx$

   #### $= \frac{(ax^2 + bx +c)^{}3/2}{3/2} + c$

   ​

3. #### $\int \frac{sin^6x}{cos^8x}dx$

   #### $ = \int tan^6x.sec^2x\ dx $

   #### $ = \frac {tan^7x}{7} + c$

   ​

4. #### $\int \frac{cos^4x}{sin^6x}dx$

   #### $ = -\int cot^4x.(-cosec^2x)\ dx $

   #### $ = -\frac {cot^5x}{5} + c$

   ​



5. #### $\int (tan^{12}x + tan^{14}x)$

   #### $= \int tan^{12}x(1  +  tan^2x)\ dx$

   #### $= \int tan^{12}x.sec^2x\ dx$

   #### $ = \frac {tan^{13}x}{13} + c$

   ​



6. #### $\int \frac{tanx}{\sqrt{cosx}}dx$

   #### $= \int \frac{sinx}{cos^{3/2}x}dx$

   #### $= -\int cos^{-3/2}x.(-sinx)$

   #### $= -\frac{cos^{-1/2}x}{-1/2} + c$

   #### $= 2cos^{-1/2}   + c$

   ​



7. #### $\int \frac{\sqrt{tanx}}{sinx.cosx}dx$

   #### $= \int\frac{tan^{1/2}x}{tanx.cos^2x}dx$

   #### $= \int tan^{-1/2}x.sec^2x$

   #### $= \frac {tan^{1/2}x}{1/2} + c$

   ​



8. #### $\int \frac{x.sin^{-1}x}{\sqrt{1-x^4}}dx$

   #### $= \frac{1}{2}\int sin^{-1}x^2.\frac{2x}{\sqrt{1-x^4}}dx$

   #### $= \frac{1}{2}.\frac{(sin^{-1}x^2)^2}{2} + c$



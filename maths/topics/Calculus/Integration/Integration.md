# Integration

### *Type - 1*

###### *Derivation*

We know,

> \\(\displaystyle \frac{d[x^n]}{dx} = n.x^{n-1}.1\\)

or,

> \\(\displaystyle \frac{d[f(x)^n]}{dx} = n.f(x)^{n-1}.f'(x)\\)

Here the differentiation of the function in the left gives us the expression on the right hand side.

As integration is the inverse of differentiation, therefore integration of the expression on the right  hand side gives us the function on the left hand side.

or,

> \\(\displaystyle \int n.f(x)^{n-1}.f'(x) = f(x)^n + c\\)

or,

> \\(\displaystyle \int f(x)^{n-1}.f'(x) = \frac{f(x)^n}{n} + c\\)

here as **\\(\displaystyle c\\)** and **\\( \displaystyle n\\)** both are constants **\\(\displaystyle \frac{c}{n}\\)** is also constant.

For convenience the above formula can be written as,

> \\(\displaystyle \int f(x)^{n}.f'(x) = \frac{f(x)^{n+1}}{n+1} + c\\)



###### ***Meaning of the constant \\(c\\)***

We know the derivative of a function gives us the slope of the function at any point, hence integration of the slope will give us the function. But there are many function which when differentiated gives us the same slope therefore the expression **\\(\displaystyle f(x) + c\\)** is written to represent all of those functions. 

###### ***Application of the formula***

When integrating an expression which consists of product of the function **\\(\displaystyle f(x)\\)** raised to some power **\\(\displaystyle n\\)** and the derivative of the base (the function) **\\(\displaystyle f'(x)\\)**, then the anti-derivative can be written as the division of the function raised to the power of **\\(\displaystyle f(x)^{n+1}\\)** by **\\(\displaystyle n+1\\)**. 

###### *Examples*

1. \\(\displaystyle \int sin^3x.cosxdx = \frac{sin^4x}{4} + c\\)

2. \\(\displaystyle {\int (2ax + b)\sqrt{ax^2+bx +c}\ dx\\= \int (ax^2+bx +c)^{1/2}(2ax + b)dx\\= \frac{(ax^2 + bx +c)^{}3/2}{3/2} + c}\\)

3. \\(\displaystyle {\int \frac{sin^6x}{cos^8x}dx\\= \int tan^6x.sec^2x\ dx \\= \frac {tan^7x}{7} + c}\\)

4. \\(\displaystyle {\int \frac{cos^4x}{sin^6x}dx\\= -\int cot^4x.(-cosec^2x)\ dx \\= -\frac {cot^5x}{5} + c}\\)

5. \\(\displaystyle {\int (tan^{12}x + tan^{14}x)\\= \int tan^{12}x(1  +  tan^2x)\ dx\\= \int tan^{12}x.sec^2x\ dx\\= \frac {tan^{13}x}{13} + c}\\)

6. \\(\displaystyle {\int \frac{tanx}{\sqrt{cosx}}dx\\= \int \frac{sinx}{cos^{3/2}x}dx\\= -\int cos^{-3/2}x.(-sinx)\\= -\frac{cos^{-1/2}x}{-1/2} + c\\= 2cos^{-1/2}   + c}\\)

7. \\(\displaystyle {\int \frac{\sqrt{tanx}}{sinx.cosx}dx\\= \int\frac{tan^{1/2}x}{tanx.cos^2x}dx\\= \int tan^{-1/2}x.sec^2x\\= \frac {tan^{1/2}x}{1/2} + c}\\)

8. \\(\displaystyle {\int \frac{x.sin^{-1}x}{\sqrt{1-x^4}}dx\\= \frac{1}{2}\int sin^{-1}x^2.\frac{2x}{\sqrt{1-x^4}}dx\\= \frac{1}{2}.\frac{(sin^{-1}x^2)^2}{2} + c}\\)




### *Type - 2*

###### *Derivation*

We know,

> \\(\displaystyle {\frac{d[e^x]}{dx} = e^x\cdot1}\\)

or,

> \\(\displaystyle {\frac{d[e^{f(x)}]}{dx} = e^{f(x)}\cdot f'(x)}\\)

Now, integrating both sides we get,

> \\(\displaystyle {\int e^{f(x)}\cdot f'(x)dx = e^{f(x)} + c}\\)

Also,

> \\(\displaystyle {\frac{d[a^{f(x)}]}{dx} = a^{f(x)}\cdot lna\cdot f'(x)}\\)

And, integrating both sides,

> \\(\displaystyle {\int a^{f(x)}\cdot lna\cdot f'(x)dx = a^{f(x)} + c}\\)

or,

> \\(\displaystyle {\int a^{f(x)}\cdot f'(x)dx = \frac{a^{f(x)}}{lna} + c}\\)



###### *Application of the formula*

When integrating an expression which consists of an exponential function \\(\displaystyle e^{f(x)}\\) alongside the derivative of the power \\(\displaystyle f'(x)\\), then the anti-derivative can be written as \\(\displaystyle e^{f(x)} + c\\). 

When the expression consists of exponential function such as \\( \displaystyle a^{f(x)}\\) with the derivative of the power \\( \displaystyle f'(x)\\), then the anti-derivative can be written as \\(\displaystyle {\frac{a^{f(x)}}{lna} + c}\\). 

###### *Examples*

<<<<<<< HEAD
1. $\displaystyle {\int {\frac{3^{\frac{1}{x}}}{x^2}dx} = -\frac{3^{\frac{1}{x}}}{ln3}+c}$

2. $\displaystyle {\int {\frac{2^{tan^{-1}x}}{1+x^2}dx} = \frac{2^{tan^{-1}x}}{ln2}+c}$

3. $\displaystyle {\int {e^{(x+\frac{1}{x})}(1-\frac{1}{x^2})}dx = e^{(x+\frac{1}{x})} +c}$

4. $\displaystyle {\int {e^{sinx\cdot cosx}\cdot cos2x}\ dx\\ =\int{e^{sinx\cdot cosx}\cdot (cos^2x-sin^2x)}dx\\ = e^{sinx\cdot cosx} + c}$

5. $\displaystyle {\int {\frac{a^{tanx}\cdot secx}{\sqrt{1-sin^2x}}dx}\\= \int{a^{tanx}}\cdot sec^2x\ dx\\=\frac{a^{tanx}}{lna}+c}$

6. $\displaystyle {\int {x\cdot e^{x^2}} dx\\= \frac{1}{2}\int e^{x^2}\cdot 2x\ dx\\=e^{x^2}+c}$
=======
1. \\(\displaystyle {\int {\frac{3^{\frac{1}{x}}}{x^2}dx} = -\frac{3^{\frac{1}{x}}}{ln3}+c}\\)
2. \\(\displaystyle {\int {\frac{2^{tan^{-1}x}}{1+x^2}dx} = \frac{2^{tan^{-1}x}}{ln2}+c}\\)
3. \\(\displaystyle {\int {e^{(x+\frac{1}{x})}(1-\frac{1}{x^2})}dx = e^{(x+\frac{1}{x})} +c}\\)
4. \\(\displaystyle {\int {e^{sinx\cdot cosx}\cdot cos2x}\ dx\\ =\int{e^{sinx\cdot cosx}\cdot (cos^2x-sin^2x)}dx\\ = e^{sinx\cdot cosx} + c}\\)
5. \\(\displaystyle {\int {\frac{a^{tanx}\cdot secx}{\sqrt{1-sin^2x}}dx}\\= \int{a^{tanx}}\cdot sec^2x\ dx\\=\frac{a^{tanx}}{lna}+c}\\)
6. \\(\displaystyle {\int {x\cdot e^{x^2}} dx\\= \frac{1}{2}\int e^{x^2}\cdot 2x\ dx\\=e^{x^2}+c}\\)
>>>>>>> 83c58ea929334ea482f2a841353ab0521b8dd368

   ​


### *Type - 3*

###### *Derivation*

We know,

> $\displaystyle {\frac{d[e^{ax}\cdot f(x)]}{dx} = a\cdot e^{ax}\cdot f(x) + e^{ax}\cdot f'(x)}$

or,

> $\displaystyle {\frac{d[e^{ax}\cdot f(x)]}{dx} = e^{ax}[f(x) + \frac{f'(x)}{a}]}$

Now, integrating both sides,

> $\displaystyle {\int e^{ax}[f(x) + \frac{f'(x)}{a}]dx = \frac{e^{ax}\cdot f(x)}{a} + c}$



###### *Application of the formula*

As in the other types here also if we come across where we need to integrate the expression of the format on the left hand side we can right the expression in the right hand side as the answer.

 ###### *Examples*

1. $\displaystyle {\int e^{3x}(\frac{3x^2 + 2x}{3})= \frac{e^{3x}\cdot x^2}{3}+c}$
2. $\displaystyle {\int (x\cdot e^x + e^x)\ dx\\=\int e^x(x + 1)\ dx\\=e^x\cdot x +c}$
3. $\displaystyle {\int}$
4. $\displaystyle {\int }$
5. $\displaystyle {\int }$
6. $\displaystyle {\int }$
7. $\displaystyle {\int }$
8. $\displaystyle {\int }$
9. $\displaystyle {\int }$
10. $\displaystyle {\int }$
# Reciprocal Average Rate Forward

A reciprocal average rate forward is a forward contract whose matured payoff is the difference between the reciprocal of the arithmetic average of foreign exchange rates and the reciprocal of a strike. The average is calculated by those rates quoted with the market convention over a given set of observation dates. The forward strike is also quoted in the same convention. Clearly, a reciprocal average rate forward is a nonlinear forward contract, which means the contract matured payoff is a non-linear function of averaged rates.

The pricing model for the reciprocal average rate forward, in the view of a first order approximation, applies the same approach as in ordinary average rate forward. Pricing average rate related non-linear derivatives, a well-acceptable and effective with reasonable accuracy pricing model for the reciprocal average rate forward is not available yet.

We did some research of seeking a semi-close form solution for pricing non-linear average rate derivatives. This research has revealed satisfactory results for pricing linear reciprocal average rate derivatives (see https://finpricing.com/lib/EqAsian.html).

Let A be the arithmetic average of a number of correlated log-normal variables and G be the corresponding geometric average. Let G = eB, then B » N(mB; vB) or the density function of G, denoted by fG(¢), can be given as

 

Now, let a > 0 and b be two fixed real numbers. We try to calculate the following

 

where a and b are such that the random variable [aA + b]¡1 has finite mean and variance. Since the
distribution of A is generally unknown, this expectation may not be obtained easily. First, we have

 

We assume that ln(A¡y) » N(mA(y); vA(y)) where mA(y) and vA(y) > 0 are smooth functions with respect
to y 2 (0;1). Let fAjy(¢) be the conditional density function of A ¡ y, then we have

 

There is a trivial case where A = G surely. For example, it is the case when A is the arithmetic average of
a single log-normal variable. In this case, (3) can be written as

 

Let us consider the non-trivial case where A > G almost surely. Thus,

 

Let us introduce

 

and

 

After substituting (7) and (8) into (6), we have

 

where

 

We may need that the function H is a well-behaved function with respect to (ux; uy) on R2 such as the
double-integral exists and the inner integral in (11) is uniformly integrable with respect to uy on R. Then
by using Gauss-Hermite quadrature, the integral (11) can be approximated with a high precision by





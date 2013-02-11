Complex-Number-Library
======================

A Lua/LuaJIT library that allows you to work with complex numbers.

Functions and constants available in cmath:
Constants
-e=2.718281828459
-i=sqrt(-1)
-pi=math.pi

Complex creation and extraction functions
-complex(re,im) creates a complex number from real and imaginary components.
-re(z) real part of z
-im(z) imaginary part of z
-arg(z) argument of z

-abs(z) absolute value of z
-sqrt(z) = z^0.5
-pow(x,y) = x^y
-exp(z) = e^z
-ln(z) = e^? = z
-log(b,z) = ln(z)/ln(b)

Trig functions
-sin(z)
-cos(z)
-tan(z)

-sinh(z)
-cosh(z)
-tanh(z)

-asin(z)
-acos(z)
-atan(z)
-atan2(y,x)

-asinh
-acosh
-atanh

Miscellaneous functions
-polar(z) returns r,phi = cmath.abs(z),cmath.arg(z)
-rect(r,phi) returns a complex number from polar = r*e^(i*phi)
-diff(z) = re(z)^2-im(z)^2
-zeta(z[,accuracy=1e4]) riemann zeta function
-lintegrate(f,H,[L=0,n=sensible for H])
-cx(string) creates a complex number from a string (e.g. "1.1-i" -> 1.1+-1i)
-cx(re,im) = complex(re,im)

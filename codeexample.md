Here is code that calculates the position of an object:

<p> # Object Position Calculator

x0 = float(input("Initial Position(x0): "))
<br />
v0 = float(input("Initial Position(v0): "))
<br />
a = float(input("Acceleration(a): "))
<br />
t = float(input("Time(t): "))
<br />
xf = x0 + v0*t + 0.5*a*t*t
<br />
print("\nFinal position(xf): ",xf)

<p/>

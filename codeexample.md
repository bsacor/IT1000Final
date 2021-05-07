Here is code that calculates the position of an object:

# Object Position Calculator

x0 = float(input("Initial Position(x0): "))
v0 = float(input("Initial Position(v0): "))
a = float(input("Acceleration(a): "))
t = float(input("Time(t): "))

xf = x0 + v0*t + 0.5*a*t*t

print("\nFinal position(xf): ",xf)

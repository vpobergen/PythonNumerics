# PythonNumerics
#Examples of Python code to learn numerical methods
import numpy as np
T = 1
Nt = 50
t = np.linspace(0, T, Nt+1) # mesh points in time
# make a simple forward Euler scheme
dt = t[1] - t[0] # time step
u = np.zeros(Nt+1) # solution vector
u[0] = 1.0 # initial condition
for n in range(0, Nt):
  u[n+1] = u[n] + dt*u[n]
# end of loop
print(u)
import matplotlib.pyplot as plt
plt.plot(u)
plt.show()

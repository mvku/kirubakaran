 # Quantum Physics Visualization with Python Code

 On this blog, I would like to explain the concepts of Quantum Phyics for college level students to understand very hard core Qunatum mechnanics in a very simple way of approach
```
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(1,100,100)
y = np. sin(x)

plt.plot (x,y,'-r)
plt.title(' sine wave generation')
plt.xlabel('Time(s)')
plt.ylabel('Amplitude(Volt)')
```

# Schrodinger Equation
In 1926, Erwin Schrodinger advanced the famous wave equation that relates the energy of a system to its wave properties. Because its application to the hydrogen atom is rather complicated, we shall first use wave equation to solve the particle-in-a-box. The Schrodinger Wave equation expressing in 1D is

$\sum_{n=1}^{10} n^2$

\begin{equation*}
$$\frac {\partial^2 \varphi}{\partial x^2} +  \frac{ 8\pi^2 m}{ h^2} (E-V) \varphi = 0$$
\end{equation*}


   
where, 
* $\varphi$ - wave function or eigenfunction
* x - coordinate in space *
* m - mass 
* h - plank's constant
* V - potential energy

## Rössler attractor
:disappointed_relieved: What is Rössler attractor and where is it coming from ? - a system of three non-linear ordinary differential equations originally studied by _Otto Rössler_ in the 1970s. Find more about [him](https://en.wikipedia.org/wiki/Otto_R%C3%B6ssler).

And fyi _Chaos theory_ is a field of mathematics that studies chaotic systems, which are dynamical systems driven by underlying patterns and deterministic rules that are very sensitive to initial circumstances. For example I collected a really awesome gif of the behaviour of double rod pendulum.
By Catslash - Own work, [Public Domain](https://commons.wikimedia.org/w/index.php?curid=10404903)

<p align="center">
<img src="https://user-images.githubusercontent.com/39788520/124354415-8353a900-dc29-11eb-83fd-f18f3bf8e2e6.gif">
</p>

That German biochemist we talked about earlier ? He studied this field of mathematics 👓 Isn't it cool?

Well, to learn about Rössler attractor, let us first know what is an attractor.
Here are some of the details notion of an attractor:
- in dynamic system (time dependence of a point in a geometric space) an attractor is defined as a set of numeric values toward which a system tends to evolve for a variety of initial conditions of the system. E.g. the evolving variable we mentioned in finite-dimensional systems, can be represented algebraically as an n-dimensional vector. If the evolving variable is in 2D or 3D, the attractor may be represented geometrically in 2D or 3D space respectively.
- an attractor can be a point, curve, manifold, fractal structure, etc.
- a dynamic system can be described by one or more differential equations. The attractor, also known as the attractive section or attractee, is a subset of the dynamical system's phase space that corresponds to normal behaviour.
Let us now return to our main topic of discussion on Rössler. The German Biochemist Otto Rössler researched its attractor for the Rössler System, which is a system of three non-linear Ordinary Differential Equations. Rössler is recognised for his work on "chaos theory," which is a dynamic system of random states and diseases. A continuous-time dynamic system is defined by this set of equations.

<p align="center">
<img src="https://user-images.githubusercontent.com/39788520/118755564-b662f880-b886-11eb-9d9a-58889b82c9ff.gif">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/39788520/118755641-e01c1f80-b886-11eb-94a0-ce47887b3224.gif">
</p>

<p align="center">
<img src="https://user-images.githubusercontent.com/39788520/118755732-08a41980-b887-11eb-8e83-1d81373ab577.gif">
</p>

Here is a 3D image of the Rössler attractor with bifurcation values **a = 0.2, b=0.2, c=5.7**.

<p align="center">
<img src="https://user-images.githubusercontent.com/39788520/118700060-dca97980-b82f-11eb-9ce1-e26930c387bd.png" width="800" height="500" title="Rossler Attractor">)
</p>

Rössler studied this so called "chaotic attractor" and investivated using various bifurcation parametric values **a,b** and **c**. Before concluding this section, let us first know what is bifurcation ?

It is said that, _when a parameter value is varied, bifurcations may occur_. In other words, bifurcations are qualitative change in its dynamic produced by change in parameter. In this case, you must have noticed that the set of equations we have consist of some parameters namely "a, b and c", which are generated from variation. And due to this variation or change there occurs a sudden behavioural change or topological change of the system.

These are sources for this file: [S1](https://en.wikipedia.org/wiki/R%C3%B6ssler_attractor) [S2](http://www.scholarpedia.org/article/Rossler_attractor) [S3](https://en.wikipedia.org/wiki/Bifurcation_theory)
# To Run The Code
- You can try downloading the `ROSSLER.mlx` file and then execute it or else you may copy paste the code from `rossler.m` and try running it online [Here](https://in.mathworks.com/products/matlab-online.html)

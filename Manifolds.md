# Manifolds

A series of videos by [The Bright Side of Mathematics](https://www.youtube.com/@brightsideofmaths) introducing Topology and walking through the pre-requisites for Calculus on surfaces.

[Link to the Playlist](https://www.youtube.com/playlist?list=PLBh2i93oe2qvRGAtgkTszX7szZDVd6jh1)

## Part 0: A LaTeX Refresher

Check out [this cheat sheet](http://tug.ctan.org/info/undergradmath/undergradmath.pdf)!

Here are some useful symbols to highlight:

| Symbol              | How to make it      |
| :---------:         | :----------         |
| $\varepsilon$       | \varepsilon         |
| $\mathcal{T}$       | \mathcal{T}         |
| $A \implies B$      | A **\implies** B    |
| $x \in X$           | x **\in** X         |
| $Y \cup X$          | Y **\cup** X        |
| $Y \cap X$          | Y **\cap** X        |
| $\mathbb{R}$        | \mathbb{R}          |


## Part 1: Introduction and Topology

The series will progress as follows: it starts with Topology, then defines differentiable manifolds, then defines differential forms. The end goal is to prove the Generalized Stokes's Theorem.

A Metric space is a tuple of $(X,d)$
  - $X$ is a set
  - $d$ is a distance function
  - $d(x,y)$ is the distance between x and y in X.
  - The open epsilon ball $B_\varepsilon(x)$ is the set of all points with $d(x,y) < \varepsilon$

Topology is the abstraction away from metric spaces. Instead of starting by defining what makes an open set and then proving properties about those open sets, topology starts by simply listing all of the open sets (without any distance function to generate them). This is a generalization because all Metric spaces have a topology thanks to the distance function, but there can exist topological spaces without metrics (or rather we can manipulate these spaces without metrics).

Let $X$ be a set, $\mathcal{P}(X)$ be the power set, and $\mathcal{T} \subseteq \mathcal{P}(X)$ be a collection of subsets. If $\mathcal{T}$ satisfies:
  1. $\emptyset, X \in \mathcal{T}$
  2. $A, B \in \mathcal{T} \implies A \cup B \in \mathcal{T}$
  3. $(A_i) _ {i \in I} \text{ with } A_i \in \mathcal{T} \implies \bigcup _ {i \in I} A_i \in \mathcal{T}$

Then $\mathcal{T}$ is called a topology on $X$. The elements of $\mathcalT$ are called open sets. The property "open" is given by definition, and it only makes sense with respect to a given topology.

TODO: look into why $\{ \}$ is not working
Examples:

  - (a) $\mathcal{T} = \{ \emptyset, X \}$ is a topology on $X$.

## Part 2: Interior, Exterior, Boundary, Closure

## Part 3: Hausdorff Spaces

## Part 4: Quotient Spaces

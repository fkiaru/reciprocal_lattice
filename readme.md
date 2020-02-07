## Reciprocal Lattice Animation

The *reciprocal lattice* of a given lattice is the Fourier transform this given lattice<br>
This project is a live visualization tool developed in **Python** that helps the user understanding how the:
<ul>
  <li> Direct Lattice (also real space) </li>
  <li> Reciprocal Lattice (also Fourir space) </li>
</ul>
are related together.
<br>
The interactivity is based on **event-driven** programming using *matplotlib*.

### Reciprocal Lattice
Definition:
Given a set <br>
<img src="https://render.githubusercontent.com/render/math?math=\{\bf{r}_j\} \, j=1..N">
<br>
of basis vectors,
the *Bravais Lattice* is the set of all integer linear combinaisons of the form
<br>
<img src="https://render.githubusercontent.com/render/math?math=\{\bf{R}_j=n_1 \bf{r}_1 + n_2 \bf{r}_2 + \ldots \quad  \forall n_1,n_2 \in \mathbb{Z} \}">
<br>
The *reciprocal lattice* of this lattice is the set of all vectors <img src="https://render.githubusercontent.com/render/math?math=\bf{K}"> that verifies <br>
<img src="https://render.githubusercontent.com/render/math?math=e^{i\bf{K}\cdot\bf{R}}=1 \quad \forall \bf{R} \in \textrm{Real Space}">
<br>
The *reciprocal basis* <br>
<img src="https://render.githubusercontent.com/render/math?math=\{\bf{g}_i\} \quad i=1..N">
<br>
is given by the NxN conditions <br>
<img src="https://render.githubusercontent.com/render/math?math=\bf{g}_i\cdot \bf{r}_j =\delta_{ij}">

### Example

By a simple **click and drag** action, the user can vary either the two basis vectors of the Direct or Reciprocal lattice.
![example](animeLattice.gif )




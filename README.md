The Linear Shell Obstacle Course
================================

The linear shell obstacle course provided here is intended to be used as a validation tool for linearized Kirchhoff-Love shell codes. Classically, shell codes have been validated using pointwise metrics with no theoretical backing. The challenge associated with validation of linearized Kirchhoff-Love shell codes is the lack of available solutions. This is due to the inherent complexity associated with computing high-ordered differential operators defined over manifolds that arise in the strong formulation of the linearized Kirchhoff-Love shell.

The linear shell obstacle course is comprised of eight problems that together encompass all possible geometric configurations and boundary conditions amenable to the linearized Kirchhoff-Love shell. Each of the eight problems has a prescribed displacement field with corresponding manufactured forcing function defined over the underlying geometric parameterization. In addition to the forcing functions, we also provide the associated strain and stress tensors corresponding to the membrane and bending modes of the shell, providing the ability to compute both displacement and strain energy errors in Sobolev-type norms.

The forcing functions are rather unwieldy and therefore require a high degree of precision to be evaluated to a reasonable accuracy. For this reason everything is provided as a Mathematica notebook. For further details regarding the content, refer to the documentation in the docs directory. For licensing details, please see the file LICENSE.txt.

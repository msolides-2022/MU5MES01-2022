# Calcul numérique des solides et structures non-linéaires

This repository collects the material to the class MU5MES01 of the Solid Mechanics Master of [Sorbonne Université](http://master.spi.sorbonne-universite.fr/fr/mecanique-des-solides-et-des-structures.html) and [ENPC](ww.enpc.fr)

* Teachers:

    * Denis Duhamel (denis.duhamel@enpc.fr)

    * Claire Lestringant (claire.lestringant@sorbonne-universite.fr)

    * Corrado Maurini (corrado.maurini@sorbonne-universite.fr, tour 55-65, 414)

    * Sébastien Neukirch (sebastien.neukirch@sorbonne-universite.fr)

* You can find help on how to install and use FEniCS in [INSTALL.md](INSTALL.md)

* You can find some links to online resources in the file [LINKS.md](LINKS.md)

* The preliminary program  is available here [syllabus.md](syllabus.md)

# Numerical tools

In this class we will use the following open-source numerical tools:

- `gmsh`: Advanced meshing tool (https://gmsh.info)

- `dolfinx`: the finite element library, see https://docs.fenicsproject.org/dolfinx/v0.5.1/python/api.html.

     FEniCSx is a popular open-source computing platform for solving partial differential equations (PDEs). FEniCSx enables users to quickly translate scientific models into efficient finite element code. With the high-level Python and C++ interfaces to FEniCSx, it is easy to get started, but FEniCSx offers also powerful capabilities for more experienced programmers. FEniCSx runs on a multitude of platforms ranging from laptops to high-performance clusters.

- `ufl` (Unified Form Language): https://fenics.readthedocs.io/projects/ufl/en/latest/manual/introduction.html

    The Unified Form Language is an embedded domain specific language
    for definition of variational forms intended for finite element
    discretization. More precisely, it defines a fixed interface for choosing¨
    finite element spaces and defining expressions for weak forms in a
    notation close to the mathematical one.

- `pyvista`:
    pyvista - PyVista package for 3D plotting and mesh analysis (https://docs.pyvista.org).

- `paraview`: ParaView is an open-source, multi-platform data analysis and visualization application (https://www.paraview.org).

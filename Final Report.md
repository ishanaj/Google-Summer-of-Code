# About Me
My name is Ishan Joshi and I have completed my third year of Bachelors in Manufacturing Processes and Automation Engineering from University of Delhi at Netaji Subhas Institute of Technology.

# About the Project
My GSoC work was focused on extending the `continuum_mechanics` module of SymPy. It involved adding some new features to the existing Beam class, and further implementation of newer classes (or modules) for handling column buckling calculations and Truss analysis. The proposal to the same can be found [here](https://docs.google.com/document/d/1LOtMTr9cCrzQ8_OnKrgkZs8wFS9N9PxlR10h3aKG0jg/edit?usp=sharing)

# Pull Requests
## Major additions
- [#17001](https://github.com/sympy/sympy/pull/17001)- Added a new method cut_section() which would return a tuple of new polygons which lie above and below the given line that intersects it.
- [#17055](https://github.com/sympy/sympy/pull/17055)- Made Beam class accept cross-section geometries.
- [#17153](https://github.com/sympy/sympy/pull/17153)- Added functionality to determine polar second moment of area, first moment of area and section modulus of a polygon.

## Open Pull requests
 The below PR's are in their final stages of getting merged:
- [#17122](https://github.com/sympy/sympy/pull/17122)- Introduced a class Column which provides functionality for column buckling calculations.
- [#17345](https://github.com/sympy/sympy/pull/17345)- A method to plot beam diagram using sympy's own plot().
- [#15775](https://github.com/sympy/sympy/pull/15775) - Added functionality to calculate bending stress and shear stress. This PR was created before the start of the project, but with the new functionalities being introduced in the Beam module, it can now reach its goal.
## Closed Pull Requests
- [#16964](https://github.com/sympy/sympy/pull/16964)- A new class CrossSection has been introduced in the continuum_mechanics module.
- [#17240](https://github.com/sympy/sympy/pull/17240)- Added functionality in the beam module to draw beam diagrams via a draw() function.

## Discussions and issues
- [#17072](https://github.com/sympy/sympy/pull/17072)- [Discussion]: Column buckling calculations in continuum mechanics module
- [#17162](https://github.com/sympy/sympy/pull/17162)- Problem with solve in handling some trigonometric equations.
- [#17302](https://github.com/sympy/sympy/pull/17302)- [Discussion]: Class for Truss analysis in continuum_mechanics

# Future Work
Here is a list that comprises of all the ideas (which were a part of my GSoC Proposal and/or thought over during the Summer) which can extend my GSoC project.
- Calculating the first moment of area for ellipses class.
- Determining the critical load for the pinned-fixed end condition of Column.
- Making a class for symbolic Truss analysis.
- Making composite shapes using Boolean operations on basic shapes in the geometry module.

# Conclusion
This summer has been a great learning experience and has helped me get good knowledge on the subject. I plan to actively review the work that went into this project and continue contributing to SymPy. I am grateful to my mentors, Jashanpreet and Yathartha for reviewing my work, giving me valuable suggestions, and being readily available for discussions.

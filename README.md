# Mara

Originally written by "m.j.louhivuori@rug.nl"

This package is distributed as-is under the GNU General Public License found in the file LICENSE.

A quick glance of the modules included gives:

Atom        -- Molecular primitives, starting from atoms and building up to 
               polypeptides etc. Can be used to build or store molecules.

aux         -- Auxiliary functions. List intersections, quicksort etc.

Biology     -- At the moment only parse_sequence().

Interface   -- Front-end to external programs such as Pales.

IO          -- Input/output interface for different data formats, e.g. PDB.

Library     -- Dictionaries and translation codeces used to convert from
               one naming convention to another.

Linguistics -- Actual translators to do the job.

Logic       -- Simple wrapper functions for chaining together complex 
               logical expressions.

Math        -- Mathematical algorithms.

mpi         -- Multi-processor interface. (untested)

NMR         -- NMR specific data structures. Dipolar coupligns etc.

Physics     -- Algorithms to calculate various physical quantities from the 
               center of mass to electrostatic potentials.

svd         -- Implementation of Singular Value Decomposition.

Happy hacking!


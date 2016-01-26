# ibctest
test apps for ibc library

## authors
 - Florian Jeltsch (idea, basic model concept, and supervision),
 - Felix May (basic model, ZOI, cutting option, and seed rain option),
 - Ines Steinhauer (clonal option),
 - Lina Weiss (sensitivity analysis, adoption to real communities, and validation),
 - Katrin Koerner (revision and rebuilt Felix' grazing experiments, and
  belowground grazing option)

## Verbal description of what the code does:
The model describes the development of a community of
perennial plant functional types (PFTs).
It is based on the grassland model developed by May et al. (2009),
augmented by the incorporation of clonal plant types.

See also: \ref ODDbase "ODD description" (by L.Weiss), also in publications of
Weiss et al. (2014), Koerner et al. (2014) and May(2009)

## Type (function, class, unit, form, ...):
console application based on ibc(coast) library

## Flow chart 
see ibc project

## Expected input (type and range of values, units):
- an input file for successive simulations (SRunPara::NameSimFile,e.g. 'SimFile.txt', given as program argument) with structure defined in ibc project
- an input file for pft definitions
- in case of ibccoast: an env file defining yearly abiotic conditions 

## Output (type and range of values, units):
- some ASCII-coded *.txt-files with weekly or yearly numbers
  of individuals or other summarizing variables on PFT or Grid level
- the Output is coded in ibc project

## Requirements and environment (libraries, headers, IDE):
- IDE: Eclipse 
- Compiler:  MinGW and standard libraries on Win-based system
- header: ibc and ibccoast libraries

## Sensitivity analysis (or reference to publication):
see ibc project

## Validation (or reference to publication):
ongoing ...

## Sources or reasons for parameter values, methods, equations:
See publications of May(2008) and Steinhauer(2008) and \ref ODDbase (\ref straits and \ref spftdef).

## bugs and todos
See additional pages for solved and unsolved bugs (\ref bug) and todos (\ref todo)

## Code History
- 2015-12 make ibc a library and exclude apps from library content (KK)

#copyright
All rights belong to the Plant Ecology and Conservation
Biology group at the University of Potsdam

# Publications or applications referring to the code:
- Weiss L, H Pfestorf, F May, K Koerner, S Boch, M Fischer, J Mueller,
  D Prati, S Socher , F Jeltsch (2014)
  Grazing response patterns indicate isolation of semi-natural
  European grasslands. Oikos 123 (5) 599-612.
- Koerner, K., Pfestorf, H., May, F., Jeltsch, F., 2014.
  Modelling the effect of belowground herbivory on grassland diversity.
  Ecological Modelling 273, 79-85.
- May, Felix, Grimm, Volker and Jeltsch, Florian (2009): Reversed effects of
  grazing on plant diversity: the role of belowground competition
  and size symmetry. Oikos 118: 1830-1843.
- Steinhauer, Ines (2008): KOEXISTENZ IN GRASLANDGESELLSCHAFTEN -
  Modellgestuetzte Untersuchungen unter Beruecksichtigung klonaler Arten.
  Diplomarbeit Universitaet Potsdam
- May, Felix (2008): Modelling coexistence of plant functional types
  in grassland communities - the role of above- and below-ground competition.
  Diploma thesis Potsdam University.

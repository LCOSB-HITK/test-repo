# COMPONENTS folder
always remember to create new components in the same dir struct as the dummy folder [submodule-component-name](https://github.com/LCOSB-HITK/SW-design-template/tree/main/COMPONENTS/submodule-component-name)

## what a component really is ?
The LCOSB has only 4 prime modules (sbunit, mod-senseact, mod-comp, mod-net). Each modules may have sub-modules inside them (eg. LAME, SLAM in mod-senseact).**A component is an even smaller part of a sub-module.**

## A few points
- keep the design requirement more towards the logic of the problem at hand, rather than the possible implementation constraints (hw or sw)
- use the include folder minimaly
- PLEASE make TESTS for your own code !!!

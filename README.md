This is the entirety of the Honeywell High Power Inverter MQP of 2025.
In this repo are teh LTspice circuit simulations for the creation of 
DC-DC converter that then supplies a DC-AC inverter. 

Multiple LTspice files contain both test cases, and
Various stages of the design process of the project.


There are multiple files in this Altium Designer Project folder. 
Below is an explanation of what each file contains and how they work together.

.SchLib
      This file contains the library that houses all the component symbols.
      The symbols are used in the Schematic, as that is where all the electrical 
      connections are established
      
.PcbLib
      This file contains the library that houses all the footprints for each 
      component in this schematic. The footprints are the physical representation
      of each component when they are laid out on the PCB.

.SchDoc
      Contains the entire circuit schematic for the inverter, which was validated
      with zero errors using the Electrical Rule Check (ERC).

.PCBDoc
      Contains the PCB 2D and 3D layout, including the layer stack-up. This file
      compiled with zero Design Rule Check (DRC) errors.

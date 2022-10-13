# SOHO - Sharework Ontology for Human-Robot Collaboration

This repository contains the core ontological model of SOHO  and the knowledge defined for the pilot use cases of the EU H2020 Sharework project. 

The OWL files have been defined using Protégé (they contain also SWRL inference rules) and support the realization of ROS-integrated 
knowledge representation and reasoning services. Such services have been developed using the open-source Apache Jena library and ROSJava. 

The repository thus contains the following folders: 

- the folder "core" contains the ontological model of SOHO;
- the folder "intances" contains knowledge instances defined to evaluate the representation of the defined ontology;
- the folder "rules" contains the inference rules supporting knowledge reasoning within the ROS module developed using Apache Jena.

## Publications

- Umbrico A, Orlandini A., Cesta A., "An Ontology for Human-Robot Collaboration", Procedia CIRP, Vol. 93, pp. 1097-1102, 2020.


## Other Resources

Please check the following repository for further details about the use of SOHO within ROS.

- Sharework Knowledge Module:     https://github.com/pstlab/sharework_knowledge.git
- Sharework Task Planner Module:  https://github.com/pstlab/sharework_taskplanner.git 


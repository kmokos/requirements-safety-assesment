# Model-based Safety Analysis of Requirement Specifications

This work introduces a semi-automated approach for the generation of a formal model from a requirements specification.

In essence, we diminish the cost of model-based design by generating a model skeleton directly from the system requirements, which enables to eventually assess their correctness through the safety analysis of gradually improved system models. Our work aims to the efficient analysis of system safety, for a set of functional requirements coupled with specifications of failure, detection, isolation and recovery (FDIR).

The concrete research contributions of this work are:
(i) an extension of our ontology-based boilerplate language*, for the specification of FDIR requirements
(ii) the model-based representation of system requirements, for the analysis of system safety, including (a) a visualization of the specification and (b) the automated generation of a model skeleton
(iii) a technical approach for (a) the safety analysis of a system design given by a model skeleton and (b) the traceability of safety violations to the requirements through their visual representation from (ii)
(iv) an application of our model-based safety analysis to a set of requirements for an industrial-scale star tracker system

The application is available inside the Tool folder. To run the JAR file, you must install the Java JDK or JRE on your computer.

To run the JAR file, use the folowing syntax:

java -jar ReqDoSA-1.0.jar

Inside the Model folders are the requirements together the supporting DSO. While in the Model folder, you can find the final version of the SLIM model used in Compass toolset.

More on the approach can be found in https://depend.csd.auth.gr/software/requirements-safety-assesment

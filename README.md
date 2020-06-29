# What is CyPhEF?
CyPhEF is a Model-Driven Engineering framework supporting the development and validation of self-adaptive cyber-physical systems. CyPhEF is implemented as an Eclipse plugin, and is based on the Eclipse Modeling Framework and the Graphical Modeling Project.

# Why CyPhEF?
Self-adaptation is nowadays recognized as an effective
approach to manage the complexity and dynamics inherent
to cyber-physical systems, which are composed of deeply intertwined
physical and software components interacting with each
other. A self-adaptive system typically consists of a managed
subsystem and a managing subsystem that implements the
adaptation logic by means of the well established MAPE-K model,
with Monitor, Analyze, Plan and Execute components, plus a
Knowledge that maintains relevant information for the other
components. Since in large distributed settings a single loop is
hardly adequate to manage the whole system, self-adaptation
is achieved by multiple loops that coordinate with one another.
Developing such systems is challenging, as several dimensions
concerning both the cyber-physical system and the decentralized
control loops should be considered. To this end, we promote
MAPE-K components as first-class modeling abstractions and
provide a framework supporting the design, development, and
validation of decentralized self-adaptive cyber-physical systems.

# Installation Instructions
We are working hard to realease the first version of CyPhEF Eclipse Plugin. At the moment, if you want to use CyPhEF, you must import the tool and use it as a developer. The installation procedure is not straight as the installation of an Eclipse Plugin, but it is not hard. Follow these steps:

1. Before downloading the tool install the following software inside Eclipse (Help -> Install new Software)
   * Eclipse Modeling Framework (EMF)
   * Graphical Modeling Project (GMP)
2. Download the sources of the tool from the top of this page (tar.gz or .zip)
3. Extract the files in a desired location
4. Import the following projects as existing projects into the workspace
   * se.lnu.decentralizedPattern
   * se.lnu.decentralizedPattern.diagram
   * se.lnu.decentralizedPattern.edit
5. Launch the runtime workspace: se.lnu.decentralizedPattern.diagram -> Run As -> Eclipse Application
6. In the runtime workspace created after launching the environment import the following project
   * CyPhEF
7. Inside the imported project you can already find the cyberModel and the physicalModel of the video example
8. You can test your installation by running the Simulate class

# Model-based Engineering of Decentralized Control in Self-Adaptive Systems
This repository contains the simulation code to replicate the results of the experimantation of the paper "Model-based Engineering of Decentralized Control in Self-Adaptive Systems" currently under revision on JSS - Special Issue on Software-Intensive Autonomous Systems: methods and applications.

# What is DECAS?
DECAS (DECAS: **DE**centralized **C**ontrol for **A**daptive **S**ystems) is a Model-Driven Engineering framework supporting the development and evaluation of decentralized self-adaptive systems. DECAS is implemented as an Eclipse plugin, and is based on the Eclipse Modeling Framework and the Graphical Modeling Project.

# Why DECAS?
Designing decentralized control architectures in self-adaptive systems constitutes yet a design challenge. In fact, in large and distributed systems software engineers are faced with the problem of how to effectively design self-adaptive control schemes that timely performs (i.e., timeliness) the correct adaptations (i.e., correctness), while guaranteeing the managed systems behaviors (i.e., assurances). Since complex, dynamic and adaptive systems are characterized by multiple design dimensions, finding the right solution for the problem might be extremely challenging, as with increase system complexity the solution space might explode.

In this context, the main research question that we this framework aims at tackling is:  How to design, evaluate and compare different control architectures and select the best candidate for a given system?

# Installation Instructions
We are working hard to realease the first version of DECAS Eclipse Plugin. At the moment, if you want to use DECAS, you must import the tool and use it as a developer. The installation procedure is not straightfoward as the installation of an Eclipse Plugin, but it is not hard. Follow these steps:

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
   * DECAS
7. Inside the imported project you can already find the cyberModel and the physicalModel of the video example
8. You can test your installation by running the Simulate class

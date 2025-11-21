# CCPBioSim PCA Workshop

[![build](https://github.com/ccpbiosim/pca-workshop/actions/workflows/build.yaml/badge.svg?branch=main)](https://github.com/ccpbiosim/pca-workshop/actions/workflows/build.yaml)

The aim of the workshop is to illustrate methods we can use to assess convergence and sampling in MD trajectories. You will compare and contrast the most basic and widely-used method to do this - RMSD analysis - with the use of more sophisticated approaches based on Principal Component Analysis (PCA). 

You will apply the approaches to two common scenarios: firstly the comparison of the dynamics of a protein the presence and absence of a bound ligand, and secondly the evaluation of sampling and convergence in an ensemble of independent, replicate, MD trajectories of a protein.

## Docker

This container is derived from the CCPBioSim JupyterHub image. This container
adds the necessary software packages and notebook content to form a deployable
course container. The source content for this course can be found at
https://github.com/CCPBioSim/pca-workshop

## How to Use

In our containers we are using the JupyterHub default port 8888, so you should
forward this port when deploying locally::

    docker run -p 8888:8888 ghcr.io/ccpbiosim/pca-workshop:latest

## Contact

Please direct all comments and enquiries to [Charlie Laughton](mailto:charles.laughton@nottingham.ac.uk)

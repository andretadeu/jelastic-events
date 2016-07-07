# jelastic-events
Jelastic JPS file to log the occurrence of Jelastic events on a Glassfish DAS node.

## Introduction

This JSON file contains all the events I know in order to document them.

## How to test

To test the events, you have to import the JSON file in this repository in Jelastic. After that, you should perform some modifications in the cluster topology.

One of the suggestions to test the events:

1. Add andretadeu/glassfish node to Application Server (cp) and add link to 'das'
2. Scale Out cp
3. Scale In cp
4. Add volume to 'das'
5. Remove volume from 'das'
6. Add new environment variable to 'das'
7. Remove the environment variable from 'das'
8. Remove all nodes from 'das' and remove the Application Servers from topology.

# About
--------------------------------------------------------------------------------
This respository collects software for the *Control over the Cloud* project of the *Department of Automatic Control* and the *Department of Electrical and Information Technology* at *Lund University*. The project does not include the system configuration (i.e. compute node and router setup, network and radio link configuration etc).

The submodules are:

* calvin-base: A fork of Calvin which adds Syslog support and LTTng trace points
* PyQPgen: Python wrapper around QPgen which generates an MPC optimisation routine
* calvincontrol: A library of Calvin Actors and Calvin Scripts


# Requirements
--------------------------------------------------------------------------------
Uses Python, is tested only on Linux. Matlab is required for PyQPgen to build the MPC binary module.

# Installation
--------------------------------------------------------------------------------
Clone the git and download the submodules to get the code.
```
  :~$ git clone https://github.com/pskarin/CotC
  :~$ cd CotC
  :~$ git submodule init
  :~$ git submodule update
```
See the individual submodule projects for more information.

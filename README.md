# qufit
MATLAB software for fitting a transmon-cavity model to experimental qubit data

The goal of this project is to do the following: Given an input bare resonator and qubit frequency, and a DC line voltage (proportional to flux bias), produce a curve to fit qubit frequency vs. flux bias
this will require a mathematical model for transmon-cavity coupling

Input Data: 
	- qubit frequency array, cavity frequency array VS. applied flux 
	- applied (flux) array = x-axis
  
  Unknowns:
	- coupling (?); or parameterize at 40 MHz
	- 
  
Return (unknown):
	- qubit frequency, cavity frequency vs. applied flux, tunable to FIT to input data

# TwinCAT-ADS-RW-TEST

Test code to communicate with a local Beckhoff XAE runtime, reading and writing to variables on the PLC
Add a global variable list named 'GVL_Vars'. you will need to add 2 variables as described below


Required variables: 

1. testABC (type=bool,init val=FALSE)
2. test123 (type=UINT,init val=0)


You MUST run this command before running the program: dotnet add package Beckhoff.TwinCAT.Ads --version 6.1.154
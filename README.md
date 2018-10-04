# virl-lab

This lab runs VIRL on an ESXi host in a lab environment. The lab was built using VMMaestro but virlutils is used to quickly enable and disable the lab. 

The topology consists of 2 spine switches (NX-OSV) and 3 leaf switches (CSR1000v). 

|-----------------------|
|      NX      NX       |
|     /   \  /   \      |
|   CSR   CSR    CSR    |
|-----------------------|

# Wind Flow Around a Cubical Building
<p>The OpenFOAM case file 'buildingUniform' can simulate uniform wind flow around a cubical building model for Reynolds Number (Re) = 100. For this problem, non-dimensional form of Navier-Stokes (NS) equations is considered and thus the inlet velocity is considered as unity, i.e. U = 1, V = 0 and W = 0. Further details about the installation of OpenFOAM and ParaView as well as steps for visualizing data files created by OpenFOAM are provided in the file 'ASEE-introduction.pdf'.</p>

<b>Steps for executing the case file:</b>

To run the simulation, the following commands should be executed in the Linux terminal or in Ubuntu under Windows Subsystem Linux (WSL). It should be noted that the execution of commands should be done under the directory 'buildingUniform':

• Generate hexahedral multi-block mesh

$ <i><b>blockMesh</b></i>

• Run the simulation

$ <i><b>icoFoam</b></i>

These are part of the ASEE-2021 paper,'Incorporating Two Weeks Open Source Software Lab Module in CFD and Fluids Courses' by <b>S. Verma</b>, Z. Mansouri and R.P. Selvam from the Univeristy of Arkansas.
This work is supported by the award from National Science Foundation (NSF) under Grant No. CMMI-1762999. 
<a href = "https://www.nsf.gov/awardsearch/showAward?AWD_ID=1762999&HistoricalAwards=false"> <<Visit NSF page here !>></a>

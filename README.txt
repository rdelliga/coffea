READING DATA WITH COFFEA NANOEVENTS.

NanoEvents is a Coffea utility to wrap flat nTuple structures (such as the CMS NanoAOD format) into a single awkward array with appropriate object methods (such as Lorentz vector methods ), cross references, and nested objects, all lazily accessed  from the source ROOT TTree via uproot.

SETUP
The file setup-lybraries.ipynb allow to set up the virtual environment in order to use coffea on the jupyter notebook and create your own kernel, I followed the instuctions on the websites (the first one explains how to install coffea and create a virtual environment, the second one how to set a kernel):

https://coffeateam.github.io/coffea/installation.html
https://www.vanderbilt.edu/accre/jupyter/

STARTING A NEW ANALYSIS
From the JupyterHub home directory, click on “New” then “terminal” in the top right to launch a new terminal, or "New" then "coffea_kernel" to start a new notebook with the new kernel created with the setup.

SAMPLES
Samples are here
eos/cms/store/group/phys_higgs/cmshmm/amarini/
to acced from lxplus do
ls /eos/cms/store/group/phys_higgs/cmshmm/amarini/
it is better to copy it directly in the jupyter folder with the shell command 

scp rdelliga@lxplus.cern.ch:/eos/cms/store/group/phys_higgs/cmshmm/amarini/WPLEPWMHADjj_4f_EWK_LO_TuneCP5_13TeV-madgraph-pythia8/UL2018-NANOAODSIMv9/220315_075136/0000/step7_456.root .

GITHUB
The folder coffea is saved in 
https://github.com/rdelliga/coffea
the password required to push a change is a token. My accounts's default identity are rdelliga@cern.ch and rdelliga.




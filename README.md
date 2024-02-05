LengthScale Download Instructions
by Connor Witt (cwitt@umass.edu) and Brandon Clarke (bstuntebeck@umass.edu)
______________________________________________________________
For background information regarding this app, please see:

"Bottlebrush Networks: A Primer for Advanced Architectures"
by Brandon R. Clarke*, Connor L. Witt*, Mark Ilton**, Alfred J. Crosby*, James J. Watkins*, and Gregory N. Tew*.

*Department of Polymer Science and Engineering
University of Massachusetts Amherst
Amherst, MAssachusetts 01003, United States

**Department of Physics
Harvey Mudd College
Claremont, CA 91711, United States
______________________________________________________________
Note:

Users must understand that this application is desgined for graft-copolymers comprised of backbones that are stiffer than their side chains (b_b > b_s)! Using this application for systems with stiffer side chains than backbones invalidates a number of critical assumptiosn made during the development of these equations, and will result in non-physical calculations and regime boundaries.

______________________________________________________________ 

Thank you for downloading length scale! The following document outlines details on how to install and use the application.

-----------------Abbreviations used in the app--------------------
PMMA = Poly(methyl methacrylic acid)
PNB = Poly(norbornene)
PCO = Poly(cycloctene)
PCL = Poly(caprolactone)
PDMS = Poly(dimethyl siloxane)
PnBA = Poly(n-butyl acrylate)
PEG = Poly(ethylene glycol)
PS = Polystyrene
PLA = Poly(lactic acid)
PAAM = Poly(acrylamide)
PNIPAAM = Poly(N-isopropylacrylamide)
PHEMA = Poly(hydroxy ethyl methaxrylate)

SBB = "Streched backbone"
SCC = "Streched sidechain"
RSC = "Rod-like sidechain"

-----------------FILES INCLUDED IN LengthScale_V25OCT2024_Installer --------------------
LengthScale_V25OCT2023.mlapp - Matlab application
MyAppInstaller_web.exe - Application installer, including a web-based installation of Matlab Runtime
README - This document
splash.jpg - Splash image upon opening app
readme_MATLABinstaller - Matlab instructions for installation

-----------------IF YOU ALREADY HAVE MATLAB INSTALLED--------------------
You may access the app simply by opening the file "LengthScale_25OCT023.mlapp" which is located on the github and is compatible with both Windows and Mac Computers, assuming you have MATLAB version 2023a or newer. If issues arise with the app, first ensure you have updated your version of MATLAB. If the issues do not cease, please email Connor Witt (cwitt@umass.edu). 

To view the code used to create the app, simply click the highlighted and bolded "LengthScale_25OCT2023" that is output in your command window. Once the help window pops up, simply click the hyperlink saying "View Code for LengthScale_25OCT2023" located in the upper right corner of window. This will open the MATLAB App Designer, which was used to create the app. For questions or comments on the code, please email Connor Witt (cwitt@umass.edu). 

-----------------IF YOU DO NOT HAVE MATLAB INSTALLED--------------------

You will need to first run the installer, which is entitled "MyAppInstaller_web.exe".
The installation wizard will then prompt you to install the application. Ensure you are running this .exe file as an administrator, as otherwise MATLAB will not be able to install the app to your desired location.

Once selecting your preference for the install location, the installation wizard will prompt you to install the MATLAB Runtime platform, which allows you to access the app. IN ORDER TO DOWNLOAD MATLAB RUNTIME, YOU MUST HAVE AN INTERNET CONNECTION. Once installed, you can access the app just as you would any other. For questions, please email Connor Witt (cwitt@umass.edu).


-----------------HOW TO USE LENGTHSCALE--------------------

Upon opening the app, you will be prompted to choose backbone and side chain monomers. Upon selecting one, you will see density, monomer length, and kuhn length values change to reported values. Select your desired monomers and input your desired degree of polymerization and degree of polymerization between side chains. You may also modify your monomers density, but standard densities are given. 

NOTE: Monomer length, and kuhn length values CANNOT be changed for the given monomers. To input custom values, you must select "Other." Upon selection from the dropdown menu, these values will be come editable. 

Once your polymer has been specified, press the "Calculate Regime" button. Upon pressing, you will see the see the graph populate, which is analogous to Figure 5 in "Bottlebrush Networks: A Primer for Advanced Architectures," with the blue regime corresponding to comb-like polymers, dark red corresponding to SBB polymer, and light red corresponding to SSC polymers.

Desired output values, including the predicted regime, mean squared radius of gyration of the side chain and backbone, and the effective kuhn length of the backbone. 

If you wish to calculate the a different regime for a given polymer, simply change your desired inputs and press the "calculate regime" button again. 

Pressing the "Clear Graph" button will remove the graph of its values. 







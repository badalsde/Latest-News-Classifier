Installation of Anaconda distribution

The next step is to install the Anaconda distribution for Linux/window/mac operating systems, which will have a lot of the libraries needed installed for us. 

The installation instructions can be found here.

Installation of additional python packages

Although a lot of packages will be installed with the Anaconda distribution, we will need to manually install other ones. They can be installed by typing the following commands in the anaconda prompt:

 # altair
 pip install altair vega_datasets notebook vega

 # dash
 pip install dash==0.35.1
 
 # dash HTML components
 pip install dash-html-components==0.13.4

 # dash core components
 pip install dash-core-components==0.42.1

 # dash table
 pip install dash-table==3.1.11

# Atmospheric radiative transfer modeling for aquatic synthetic dataset development. 

<br>This codebase is intended to read output txt files from the HydroLight aquatic radiative transfer program and model above water reflectance to top-of-atmosphere for various atmosphere conditions and multiple satellite sensor configurations, as well as hyperspectral. This code does not include MODTRAN itself, and is built using a MODTRAN 5 [Matlab wrapper](https://www.mathworks.com/matlabcentral/fileexchange/31961-derekjgriffith-matlab-modtran-5) which needs to be installed separately and point to the MODTRAN 5 executable (see associated instructions in the wrapper). 

<br>- Parent script is RunBatch_v5.m
<br>- Test output HydroLight data is located in folder 'test'
<br>- Will need to adjust paths pointing to hydrolight data in line 6 of FindHyCases_v5.m and line 37 in ExecuteCase_ver5.m
<br>- Outputs will be printed in .csv files with prefix defined in RunBatch_v5.m file. 

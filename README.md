# epilepsy_eeg_matlab

## Steps for Windows Runtime <br>
   1. Install Matlab Runtime Installer (to run the executable without MATLAB license) <br>
   2. Go to : https://in.mathworks.com/products/compiler/matlab-runtime.html <br>
   3. Select : Make sure runtime version is equal to MATLAB version during compiling and packaging (In our case R2018b (9.5) Windows 64-bit) <br>
   4. Download and install the file "MCR_x_win64_installer.exe"(In our case "MCR_R2018b_win64_installer.exe") <br>
   5. Runtime application "MATLAB Runtime x" (in our case "MATLAB Runtime 9.5 is installed")
   6. In the "executable_folder" find the executable file named ".exe"
   7. Installation Popup will appear and choose the appropriate folder
   8. Choose MATLAB Runtime Installation folder which was previously installed
   9. Accept all the steps

   N.B : Application is resource intensive, run on a 



## Prerequisites for building from Source Code
Valid MATLAB License <br>
Tested MATLAB version : R2018b and R2019a <br>
Additional MATLAB APPS : MATLAB Compiler 7.0.0(R2019a) + (or whatever is default for your MATLAB verion) <br>

## Steps to Compile Application from Compiler Project (Windows)
   1. Packaging File with dependencies provided in "run_sourceloc.prj" <br>
   2. Select "Runtime downloaded from web"/"Runtime Included in the package" <br>
   3. Make sure additional files are present under "Additional installer options -> Files required for your application to run" <br> [Fix This step]
   4. Add any other meta information for the file bulid <br>
   5. Click Package on the upper right corner. <br>
   6. Select the destination folder where the executable will be stored

## Steps to Create a new Compiler Project (Windows)
   1. Open MATLAB Editor go to APPS -> "Application Compiler" <br>
   2. Add main file "run_sourceloc.m" <br>
   3. Follow steps in the previous point <br>
   4.  

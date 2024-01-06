**Storage directory of code used in simulation is "MatDEM3.20(2021a runtime)".**

## About software: **MatDEM**

MatDEM is a comprehensive discrete element software developed by Nanjing University, featuring fully independent intellectual property rights. It employs original matrix-based computation methods to achieve rapid simulations of millions of particles and enables large-scale three-dimensional numerical simulations of discrete elements in a matter of hours. Building upon the original theory, the software has achieved significant advancements by implementing automatic modeling of discrete element materials and incorporating energy conservation calculations for discrete element systems, among other notable features. The software integrates pre-processing, computing, and post-processing functionalities along with robust support for secondary development. This comprehensive approach delivers a fully functional interface and an efficient computing engine capable of executing complex multi-field coupling simulations.

MatDEM is  written by Matlab language, allowing it to run on various operating systems such as Windows, Linux, Unix, and Mac OS. Currently, the Windows version of MatDEM is the primary version available, as it is the most commonly used by the majority of users. However, additional versions for other operating systems may be developed and maintained in the future.


For the secondary development of MatDEM, the installation of the Matlab runtime environment is required. Specifically, MatDEM_v3.20 and above versions require the R2021A version of the MATLAB runtime environment. The MATLAB runtime environment is freely available for download from the official Matlab website and can be installed separately. To access the latest version of MatDEM, please visit the website: http://matdem.com.

## **Running of MatDEM software**

1. Download the folder named "MatDEM3.20(2021a runtime)" and locate the application named "MatDEM.exe."
1. Double-click the "MatDEM.exe" application to launch the MatDEM software.
1. Once the MatDEM software is running, navigate to the "main program" and double-click to open the "code" located in the working folder on the right side of the interface.
1. Double-click each code file (named step 1~3) and click the "Run commands" button located below the code bar.
1. The three codes should be executed in order.
1. The "step 1" code performs accumulation modeling, creating a geological accumulation body through gravity deposition and compaction.
1. The "step 2" code handles model cutting and material settings.
1. The "step 3" code manages the loading and calculation processes.
1. After the calculations are completed, the post-processing module can be used to generate and output the desired results.
Note: Once the iteration has started, the program should not be terminated. If it becomes necessary to force termination, the MatDEM task can be ended using the task manager.


**Notes:The program cannot be terminated after starting the iteration. If you need to force the termination, you can end the task with Matdem in the task manager.**

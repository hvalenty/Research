Four Directories:
1. ChainPT_CFR
2. ChainPT_TFR
3. DepolPT_CFR
4. DepolPT_TFR

In ChainPT's Program Chain Run Order:
--> [need to run with original data file in the directory before, or change code to fit filepath]
1. ProtonTreePTRebin.C
--> [running in machine or jlab for .C; root filename.C]
2. AsymmetryPTRebin.java
--> [if running in jlab commands for java; javac filename.java (followed by) java filename]
3. FitMethodFall2PTRebin.C
4. AsymmetryCalcPTRebin.C
--> [if changing target variable (from pT to other) find pT variables and insert desired term]
--> [will need to change number and range of variable cuts throughout programs 1-3
5. (Example ALU Plot)

In DepolPT's:
1. mean_vs_xF.txt
2. protonAsymmetryPT.txt
3. FLUTotalComp.C
--> [change input .txt files based on data gained from target variable]
--> [can comment out ALU comparison plot for just FLU/FUU]
4. (Example Table and Plots for Reference, including files 1 & 2)

In FactorPT:
1. DepolarizationfactorTFR.C
2. DepolarizationfactorCFR.C
3. TwoDPlotMakerPT.C
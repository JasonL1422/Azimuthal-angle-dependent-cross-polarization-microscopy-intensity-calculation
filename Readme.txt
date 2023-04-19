
The cross-polarization (CP) optical microscopy intensity calculation used WOLFRAM MATHEMATICA (ver. 12.3.0). The attached code was tested with version 12.3.0 and worked well on both Windows and macOS. It does not require non-standard hardware. You can download and install WOLFRAM MATHEMATICA here: www.wolfram.com/mathematica. It does not require any non-standard hardware. However, it may need decent PC performance to use. Since Mathematica is commercial software, the details of installation instructions and PC specifications are not described here but are available on the website. The installation should be finished within 1-20 minutes. The time may vary depending on the version and your PC performance. The code does not need datasets to demo the code. Equations to calculate and produce results are written within the code. However, cellulose birefringence information is needed, which is available in a previous publication (https://doi.org/10.1002/admi.201902169 or reference 53 in the Main text), and saved in the nenodn.xlsx file. 

* Instructions to use *
In .zip file, there are three files:
1. Readme.txt
2. Cross-polarization calculation (Supplementary Figure 6, 8).nb
3. nenodn.xlsx

Before running the code, make sure the nenodn.xlsx file is in the same folder where .nb file is located. Otherwise, you need to insert the file path of the excel file to the "Import[]" in section A. 

How to run the code:
1. On the top menu bar, click "Evaluate" - "Evaluate Notebook".
2. It takes a few minutes to run the code, and the result is saved as .xlsx file in the same folder where the Cross-polarization calculation (Supplementary Figure 6, 8).nb file is located.

Reproduction instruction:
The resulting file (.xlsx) is saved with the time mark in the file name. Thus, you can just repeat "How to run the code" section. Newly produced data does not overwrite existing files.

Supplementary Figure 6b is the average of ten datasets after repeating ten notebook evaluations. The datasets for Supplementary Figure 6c can be obtained by running the code after adjusting "n" in section D. For example, n=200 or n=300.

In the code file (.nb), Equation 1-5 in Methods (Main text) are highlighted in yellow, Supplementary Figure 8a,d are inserted in the code for easier understanding, and the parts that generate Supplementary Figures 8b,c,e,f are also highlighted in yellow.

* Please note that the code may not work when the file is located where the file path name is too long or when the file name includes special characters.
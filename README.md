#VSB Power Line Fault Detection

Julian Sweet, DSI-LA6

### Problem Statement

Partial discharge (PD) in high voltage electrical transmission lines is known to be a precursor to complete failure of an electrical system in the form of coronal discharge (flashover). Flashover failure leads to costly damage of the system and will also likely lead to fire or an explosion, which can put people and property at risk.

Can the analysis of 3 phase (3-wire) time-varying electrical signals from transmission lines be used to determine if either a single wire, or family of 3 wires is experiencing partial discharge. 

> https://www.kaggle.com/c/vsb-power-line-fault-detection

This project is composed of the following notebooks:

01_Data_Manip             : Introduction to the dataset and storage formats. The data is manipulated to create a   
                            balanced class from the unbalanced anomaly type dataset. Time series visualizations.

02_Time_Visuals           : The time domain data is visualized and discussed.

03_Fourier_visuals        : The manipulated dataset is converted to frequency-space data with FFT and STFT visualizations.

04_Log_Reg_Bal            : The Balanced class data is modelled using Logistic Regression.

05_Log_Reg_UnBal          : The unalanced class data is modelled using Logistic Regression.

06_Dec_Tree_Bal           : The unbalanced class data is modelled using decision trees.

07_Dec_Tree_Unbal         : The balanced class data is modelled using decision trees.

08_Neural_Bal             : The unbalanced class type is modelled using a neural network.

09_Neural_Unbal           : The balanced class type is modelled using a neural network.

10_Conclusion             : Production model suggested. What work should continue, how the project should scale. 
 








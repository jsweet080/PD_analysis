#VSB Power Line Fault Detection

Julian Sweet, DSI-LA6

### Problem Statement

Partial discharge (PD) in high voltage electrical transmission lines is known to be a precursor to complete failure of an electrical system in the form of coronal discharge (flashover). Flashover failure leads to costly damage of the system and will also likely lead to fire or an explosion, which can put people and property at risk.

Can the analysis of 3 phase (3-wire) time-varying electrical signals from transmission lines be used to determine if either a single wire, or family of 3 wires is experiencing partial discharge. 

> https://www.kaggle.com/c/vsb-power-line-fault-detection

This project is composed of the following notebooks:

01_Data_Manipulation      : Introduction to the dataset and storage formats. The data is manipulated to create a   
                            balanced class from the unbalanced anomaly type dataset. Time series visulaizations.

02_Fourier_convert        : The manipulated dataset is converted to frequency-space data with FFT and STFT visualizations.

03_Decision_Tree          : Both balanced and unbalanced classes data is modelled using decision trees.

04_Neural                 : Both class types are modelled using a neural networks.

05_Analysis_and_Future    : Accuracy and other metrics are discussed with respect preceding models. What work should continue,           
                            how the project should scale.
 








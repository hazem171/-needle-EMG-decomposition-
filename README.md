# -needle-EMG-decomposition-


Implementing the needle EMG decomposition algorithm. The function takes as inputs the EMG signal to process and the moving average window size T. The function returns a vector that contains the timestamps of the peaks of the detected MUAPs for each detected MU and a vector for the template of each MU. Applying the function to the EMG signal provided in the file “Data.txt” with T =20 samples and DiffTh is set to 12.655. 

Attached files: 

• A figure showing from sample 30000 to sample 35000 of the EMG signal with an “*” marking the detected MUAPs colored with different colors depending on the MU each MUAP belongs to (Similar to slide 19). The figure is named “DetectedMUAP.jpg”
• A figure showing the waveform of each template of the detected MUs. The figure is named “Templates.jpg”

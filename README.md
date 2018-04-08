# Chaotic-circuit-encryption-decryption
We implemented a simple encryption-decryption circuit using the property of synchronisation of chaotic circuits and simulated them in ngSPICE. 

The file oss.cir plots the output of the chaotic circuit(transmitter circuit), change the value of R6 in ngSPICE code to obtain different plots.

The file coupling.cir adds the input to the chaotic circuit(encrypts) and plots the encrypted signal. 

The file receiver.cir plots the output of the receiver circuit and the transmitter circuit on the same graph to show synchronisation

The file final.cir gives the final recovered output which has an additional low pass filter connected so get better results. 

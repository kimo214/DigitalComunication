## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67.
#### Settings:
* Noise level is set to 10 Db for the scatter plots.
* Sample time is 1 with 100 samples per frame.
* The set size is 2.
* Initial Speed is 37.

## **Quadrature Phase-Shift Keying Modulation (QPSK)**
### - Definition 
QPSK is a modulation scheme that allows one symbol to transfer two bits of data. There are four possible two-bit numbers (00, 01, 10, 11), and consequently we need four phase offsets. Again, we want maximum separation between the phase options, which in this case is 90°. The channel used is an Additive White Gaussian Noise (AWGN).


### - Before AWGN Channel
* Without Raised Cosine Filter:

    ![Regular](/QPSK/Before.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QPSK/RaisedCosineBefore.png) 
### - After AWGN Channel
* Without Raised Cosine Filter: 

    ![Regular](/QPSK/After.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QPSK/RaisedCosineAfter.png) 


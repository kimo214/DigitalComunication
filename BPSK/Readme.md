## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67.
#### Settings:
* Noise level is set to 10 Db for the scatter plots.
* Sample time is 1 with 100 samples per frame.
* The set size is 2.
* Initial Speed is 37.

## **Binary Phase-Shift Keying Modulation (BPSK)**
### - Definition 
BPSK is the simplest form of phase shift keying (PSK), where “binary” refers to the use of two phase offsets (one for logic high, one for logic low). It uses two phases which are separated by 180° and so can also be termed 2-PSK. The channel used is an Additive White Gaussian Noise (AWGN).


### - Before AWGN Channel
* Without Raised Cosine Filter:

    ![Regular](/BPSK/Before.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/BPSK/RaisedCosineBefore.png) 
### - After AWGN Channel
* Without Raised Cosine Filter: 

    ![Regular](/BPSK/After.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/BPSK/RaisedCosineAfter.png) 


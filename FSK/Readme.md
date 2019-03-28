## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67.
#### Settings:
* Noise level is set to 10 Db for the scatter plots.
* Sample time is 1 with 100 samples per frame.
* The set size is 2.
* Initial Speed is 37.

## **Frequency Shift Keying Modulation (FSK)**
### - Definition 
Frequency-shift keying (FSK) is a frequency modulation scheme in which digital information is transmitted through discrete frequency changes of a carrier signal. The channel used is an Additive White Gaussian Noise (AWGN).


### - Before AWGN Channel
* Without Raised Cosine Filter:

    ![Regular](/FSK/Before.PNG) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/FSK/RaisedCosineBefore.PNG) 
### - After AWGN Channel
* Without Raised Cosine Filter: 

    ![Regular](/FSK/After.PNG) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/FSK/RaisedCosineAfter.PNG) 


## Simulation Environment Settings
The simulation is done on different initial random seeds, mostly either 15 or 67.
#### Settings:
* Noise level is set to 10 Db for the scatter plots.
* Sample time is 1 with 100 samples per frame.
* The set size is 2.
* Initial Speed is 37.

## **Quadrature Amplitude Modulation (QAM64)**
### - Definition 
QAM conveys two analog message signals, or two digital bit streams, by changing (modulating) the amplitudes of two carrier waves, using the amplitude-shift keying (ASK) digital modulation scheme or amplitude modulation (AM) analog modulation scheme. The channel used is an Additive White Gaussian Noise (AWGN).


### - Before AWGN Channel
* Without Raised Cosine Filter:

    ![Regular](/QAM64/Before.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QAM64/RaisedCosineBefore.png) 
### - After AWGN Channel
* Without Raised Cosine Filter: 

    ![Regular](/QAM64/After.png) 
* With Raised Cosine Filter:

    ![Raised Cosine Filter](/QAM64/RaisedCosineAfter.png) 


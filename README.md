## Repository of the official datasets used for testing and validating the consistency of the matlab, R, and Python implementations of the mannkendall code.


The tests (in matlab syntax) are as follows. Running them in all codes is used to ensure that they
return consistent results.


**nanautocorr:**
1. `[nanautocorr_test1_out,~] = nanautocorr(nanautocorr_test1_in,2,1) ;`

**nanprewhite_arok:**
1. `[nanprewhite_arok_test1_out1, nanprewhite_arok_test1_out2, nanprewhite_arok_test1_out3] = nanprewhite_ARok(nanprewhite_arok_test1_in);`
2. `[nanprewhite_arok_test2_out1, nanprewhite_arok_test2_out2, nanprewhite_arok_test2_out3] = nanprewhite_ARok(nanprewhite_arok_test2_in,’alpha_ak’,90);`

**prewhite:**
1. `prewhite_test1_out = prewhite(prewhite_test1_in,7,2);`

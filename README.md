## Repository of the official datasets used for testing and validating the consistency of the matlab, R, and Python implementations of the mannkendall code.


The tests (in matlab syntax) are as follows. Running them in all codes is used to ensure that they
return consistent results.


**nanautocorr:**
1. `[Test_nanautocorr_out,~] = nanautocorr(test_nanautocorr_in,2,1) ;`

**nanprewhite_arok:**
1. `[test1_nanprewhite_ARok_out1, test1_nanprewhite_ARok_out2, test1_nanprewhite_ARok_out3] = nanprewhite_ARok(test1_nanprewhite_ARok_in);`
2. `[test2_nanprewhite_ARok_out1, test2_nanprewhite_ARok_out2, test2_nanprewhite_ARok_out3] = nanprewhite_ARok(test2_nanprewhite_ARok_in,’alpha_ak’,90);`

**prewhite:**
1. `test1_prewhite_D_out = prewhite_D(test1_prewhite_D_in,7,2);`

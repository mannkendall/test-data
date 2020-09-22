# test-data:
## Repository of the official datasets used for testing and validating the matlab, R, and Python
versions of the mannkendall code.


The tests (in matlab syntax) are as follows.


**nanautocorr:**
1. [Test_nanautocorr_out,~]=nanautocorr(test_nanautocorr_in,2,1) ;

**nanprewhite_arok:**
1. [test1_nanprewhite_ARok_out1, test1_nanprewhite_ARok_out2, test1_nanprewhite_ARok_out3]=nanprewhite_ARok(test1_nanprewhite_ARok_in);
2. [test2_nanprewhite_ARok_out1, test2_nanprewhite_ARok_out2, test2_nanprewhite_ARok_out3]=nanprewhite_ARok(test2_nanprewhite_ARok_in,’alpha_ak’,90);

**prewhite:**
1. test1_prewhite_D_out=prewhite_D(test1_prewhite_D_in,7,2);

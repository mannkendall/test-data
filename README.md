## Repository of the official datasets used for testing and validating the consistency of the matlab, R, and Python implementations of the mannkendall code.


The tests (in matlab syntax) are as follows. Running them in all codes is used to ensure that they
return consistent results.

**compute_MK_stat:**
1. `[compute_MK_stat_test1_out1,compute_MK_stat_test1_out2,compute_MK_stat_test1_out3,compute_MK_stat_test1_out4]=compute_MK_stat(compute_MK_stat_test1_in1,compute_MK_stat_test1_in3,compute_MK_stat_test1_in3);`
2. `[compute_MK_stat_test2_out1,compute_MK_stat_test2_out2,compute_MK_stat_test2_out3,compute_MK_stat_test2_out4]=compute_MK_stat(compute_MK_stat_test2_in1,compute_MK_stat_test2_in3,compute_MK_stat_test2_in3,'alpha_MK',90,'alpha_CL',95);`

**Kendall_var:**
1. `Kendall_var_test1_out = Kendall_var(Kendall_var_test1_in1,Kendall_var_test1_in2,Kendall_var_test1_in3);

**MK_tempAggr:**
1. `MK_tempAggr_test1_out_default=MK_tempAggr(MK_tempAggr_test1_in,'3PW', 0.01);`
2. `MK_tempAggr_test1_out_CL=MK_tempAggr(MK_tempAggr_test1_in,'3PW', 0.01,'alpha_MK',90,'alpha_ak',90,'alpha_CL',95,'alpha_Xhomo',95);`
3. `MK_tempAggr_test2_out_default=MK_tempAggr(MK_tempAggr_test2_in,'3PW', 0.01);`
4. `MK_tempAggr_test2_out_CL=MK_tempAggr(MK_tempAggr_test2_in,'3PW', 0.01,'alpha_MK',90,'alpha_ak',90,'alpha_CL',95,'alpha_Xhomo',95);`
5. `MK_tempAggr_test3_out_default=MK_tempAggr(MK_tempAggr_test3_in,'3PW', 0.01);`
6. `MK_tempAggr_test3_out_CL=MK_tempAggr(MK_tempAggr_test3_in,'3PW', 0.01,'alpha_MK',90,'alpha_ak',90,'alpha_CL',95,'alpha_Xhomo',95);`

**nanautocorr:**
1. `[nanautocorr_test1_out,~] = nanautocorr(nanautocorr_test1_in,2,1) ;`

**nanprewhite_arok:**
1. `[nanprewhite_AR_test1_out1, nanprewhite_AR_test1_out2, nanprewhite_AR_test1_out3] = nanprewhite_AR(nanprewhite_ar_test1_in);`
2. `[nanprewhite_AR_test2_out1, nanprewhite_AR_test2_out2, nanprewhite_AR_test2_out3] = nanprewhite_AR(nanprewhite_ar_test2_in,'alpha_ak',90);`

**Nb_tie:**
1. `Nb_tie_test1_out=Nb_tie(Nb_tie_test1_in,2);`
2. `Nb_tie_test2_out=Nb_tie(Nb_tie_test2_in,0.01);`

**prewhite:**
1. `prewhite_test1_out = prewhite(prewhite_test1_in,7,2);`
2. `prewhite_test2_out = prewhite(prewhite_test2_in,'scat',0.01);`

**Prob_3PW:**
1. `[Prob_3PW_test1_out1,Prob_3PW_test1_out2] = Prob_3PW(Prob_3PW_test1_in1,Prob_3PW_test1_in2,Prob_3PW_test1_in3);`
2. `[Prob_3PW_test2_out1,Prob_3PW_test2_out2] = Prob_3PW(Prob_3PW_test2_in1,Prob_3PW_test2_in2,Prob_3PW_test2_in3);`

**Sen_slope:**
1. `[Sen_slope_test1_out1,Sen_slope_test1_out2,Sen_slope_test1_out3] = Sen_slope(Sen_slope_test1_in1,Sen_slope_test1_in2,Sen_slope_test1_in3);`

**STD_normale_var:**
1. `STD_normale_var_test1_out = STD_normale_var(STD_normale_var_test1_in1,STD_normale_var_test1_in2,STD_normale_var_test1_in3);`

**S_test:**
1. `[S_test_test1_out1, S_test_test1_out2] = S_test(S_test_test1_in1,S_test_test1_in2);`

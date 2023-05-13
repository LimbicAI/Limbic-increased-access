# Limbic-increased-access
In this repository you will find the data and analysis script for the research article "Closing the accessibility gap to mental health treatment with a conversational AI-enabled self-referral tool"


You can find the data in the three folders:
1. **_Annual_data_** has the data reported annually by NHS Digital and is used for total referral analysis
2. **_Monthly data_** has the data reported monthly by NHS Digital and is used for total self-referral analysis
3. **_Quaterly_data_** has the data reported quaterly by NHS Digital and is used for demographic analysis


The code is divided into the following files:

1. **_Analyse_total_referrals_and_figure_2_**
is used to calculate the total referrals for the pre- and post-implementation periods for services using the AI-enabled tool, match the services to most similar other services not using the tool, plot Figure 2 and perform the statistical tests for total referral analysis

2. **_Analyse_demographics_and_figure_3_**
is used to analyse the demogrpahic data for pre- and post-implementation for services using the AI-enabled self-referral tool and perform the statistical tests.

3. **_Thematic-analysis-train-classifier-and-use-for-all-feedback_**
is used to train the supervised NLP classification model for the thematic analysis described in the paper, and then to analyse the 42,332 feedback entries. The data for used in this code is not made available due to because the information could compromise participants' privacy/consent.

4. **_Analyse_total_self_referrals_and_supplemental_figure_1_**
is used to calculate the total self-referrals for the pre- and post-implementation periods for services using the AI-enabled tool, define the matched services not using the tool (using the same services as for total referrals) and plot Supplemental Figure 1 and perform the statistical tests


 
 

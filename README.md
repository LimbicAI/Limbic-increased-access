# Limbic-increased-access
In this repository, you will find the data and analysis script for the research article "Closing the accessibility gap to mental health treatment with a conversational AI-enabled self-referral tool"


You can find the main data in the three folders:
1. **_Annual_data_** has the data reported annually by NHS Digital and is used for total referral analysis
2. **_Monthly data_** has the data reported monthly by NHS Digital and is used for total self-referral analysis
3. **_Quaterly_data_** has the data reported quarterly by NHS Digital and is used for demographic analysis

   In addition, the data from the additional study where we compare the AI-enabled self-referral tool to a user-friendly but non-AI chatbot and webform can be found at 'UEQ_individual_results" (see more details about the study in the Supplementary Material)


The code is divided into the following files:

1. **_Analyse_total_referrals_and_figure_1_and_2_updated_**
is used to calculate the total referrals for the pre- and post-implementation periods for services using the AI-enabled tool, match the services to most similar other services not using the tool, plot Figure 2 and perform the statistical tests for total referral analysis. In addition, it analyses the demographic data for pre- and post-implementation for services using the AI-enabled self-referral tool and the matched control services and plots Figure 3 and performs the statistical tests. There is also an option to match services on confounding variables and run statistical tests on whether services differ on the confounding variables in the pre-implementation period.

2. **_Thematic-analysis-train-classifier-and-use-for-all-feedback_**
is used to train the supervised NLP classification model for the thematic analysis described in the paper, and then to analyse the 42,332 feedback entries. The data used in this code is not made available because the participants did not provide explicit consent for sharing this data.

3. **_Analyse_feedback_labels_per_demographic-groups_and_figure_4_and_supplemental_figure_2_**
is used to analyse the feedback labels according to the demographic groups to determine whether the proportions of individuals mentioning specific themes differed between minority and majority groups, and plot Figure 3 and Supplemental Figure 4.The data used in this code is not made available because the participants did not provide explicit consent for sharing this data.

4. **_Analyse_total_self_referrals_and_supplemental_figure_1_**
is used to calculate the total self-referrals for the pre- and post-implementation periods for services using the AI-enabled tool, define the matched services not using the tool (using the same services as for total referrals) and plot Supplemental Figure 1 and perform the statistical tests

5. **_UEQ_analysis_**
is used to calculate the user experience questionnaire scores for the comparison of the AI-enabled self-referral tool to a user-friendly but non-AI chatbot and webform, as well as plot Supplementary Figure 5 and run the statistical tests.


 
 

#  Stiffness Analysis for Stroke Rehabilitation using Game Data

Introduction:
This code focuses on analyzing the stiffness of stroke patients during gameplay sessions. Stiffness is categorized into three types: resistance, assistance, and perturbation. The code utilizes data from a database that captures the patient's handling of the game handle while playing. The game is designed to uncover images by moving the handle towards specific targets. The goal is to evaluate the patient's stiffness levels throughout the rehabilitation process and assess their progress.

Code Overview:
This code performs various analyses to understand and visualize the stiffness patterns of stroke patients during gameplay. The following steps are carried out:

Plotting Stiffness Values per Gameplay:
The code retrieves the stiffness values for each gameplay session.
A plot is generated to visualize the stiffness values over time, allowing for a detailed analysis of the patient's stiffness during gameplay.

Stiffness Trend Analysis for Individual Patients:
The code calculates the mean stiffness value from the last few recorded values for each gameplay.
The mean values are plotted to visualize the overall trend and improvement in stiffness over multiple gameplays.
This analysis helps assess if the patient's stiffness is decreasing or if assistance is still required towards the end of the therapy.

Stiffness Median and Median Absolute Deviation (MAD) Analysis:
The code computes the median stiffness value within each gameplay session.

Median Absolute Deviation (MAD) is calculated to assess the dispersion of stiffness values.
Plots are generated to visualize the median stiffness and MAD within gameplays, providing insights into the overall stiffness distribution.

Mean and Standard Deviation Analysis:
The code calculates the mean and standard deviation of the stiffness values for each gameplay.
These metrics are plotted to examine the average stiffness and its variation across different gameplays.
This analysis helps identify games or gameplays that contribute to higher or lower stiffness levels.

Mean Stiffness Analysis Across Patients:
The code computes the mean stiffness value across all patients involved in the study.
A final plot is generated to visualize the mean stiffness of all patients, providing an overview of the stiffness levels observed throughout the rehabilitation process.

Conclusion:
This code offers a comprehensive analysis of stiffness during stroke rehabilitation using game data. By evaluating stiffness levels across different gameplays, it provides valuable insights into patient progress and therapy effectiveness. The visualizations and statistical measures aid in understanding stiffness trends, dispersion, and improvements. Researchers and rehabilitation specialists can utilize these findings to optimize therapy programs and personalize interventions based on individual patient needs.

Note: The provided script is a high-level overview. It is recommended to include additional details, such as the specific data processing steps, visualization techniques used, and any relevant statistical analysis, to provide a comprehensive understanding of the research work.

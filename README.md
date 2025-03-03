# Neural_reach_matlab
# README


This MATLAB script is designed to load, analyze, and visualize neural and behavioral data from a movement-based experiment. The dataset consists of trials where subjects perform reaching movements, and neural activity is recorded from multiple cells. The script extracts behavioral data by loading `neuralData.mat`, identifying unique target locations, and processing hand position data for each trial. 

Hand position data is plotted to visualize movements across different targets, assigning distinct colors to each target location and displaying mean hand positions. Additionally, the script computes movement velocity by calculating hand movement speed, identifying peak velocity and reaction times, and generating velocity plots for each trial. Statistical analysis is performed, including the computation of mean and standard deviation of reaction times and conducting ANOVA to compare reaction times across targets.

For neural data analysis, spike times are extracted from neural recordings, and raster plots are generated to visualize neural activity. The script computes peristimulus time histograms (PSTH) for aligned spike data and converts target locations into degrees for further analysis. Neural tuning curves are then plotted for different cells to analyze their activity patterns.

This script requires `neuralData.mat` to be present in the same directory. MATLAB functions such as `plot`, `xline`, `scatter`, `bar`, and `fminsearch` are used for visualization and analysis. Users should follow an ordered execution of the script, starting with extracting and visualizing hand movement data, followed by neural activity analysis and tuning curve generation. Parameters such as velocity thresholds and plotting settings can be modified as needed. 

The script outputs hand position plots for multiple targets, reaction time statistics, velocity plots for each trial, raster plots for neural activity, PSTH visualizations, and tuning curves for neurons. If any variables are missing, users should verify that field names in `R` are correctly referenced. The visualization process may take time depending on the number of trials.



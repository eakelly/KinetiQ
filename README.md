# KinetiQ

## Tutorial
1. Open the latest kinetiq_v4.ipynb notebook.
2. To run the experiments, we need to run all the cells in Setup and Experiment Functions. 
3. The runner code for the experiments exists in the run_api_calls() function. The compare_query_parameters() also runs the experiments, but does not make any external API calls and instead reads the results from the files created during a run_api_calls() run. It is used if we want to perform only the comparison and evaluation step.
4. Once the above cells have been run, you can then run each of the experiments in the Experiments section.
5. Once the experiments are run, then results can be generated in the Results section.

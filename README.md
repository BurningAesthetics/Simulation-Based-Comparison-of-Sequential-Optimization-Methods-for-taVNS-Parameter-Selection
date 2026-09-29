**STEPS TO RUN THE BAYESIAN-OPTIMIZER TAVNS SIMULATION:**

1) Run the first import cell first: Google Colab may prompt you to restart the session to download an import. In this case, simply agree and rerun the first import cell again.

2) Run each cell until you get to the cells that run the optimizer families:

   If you desire to run each of the families, run the desired optimizer family cell.

   Alternatively, you can import your existing csv family cells into the either of the 2 cells before the final sensitivity analysis. One cell will take in a results and a convergence csv file to give you statistics for that specific family. Another cell will take all optimizer results and convergence results csv files, and will download all the data into variables.

3) a)If you downloaded all the optimizer family csv files, which should number 18 in total for 2 files per optimizer family, through running the cell, OR
   b) You have ran each optimizer family cell experiment inside of the google colab environment itself,
   You can run the final cell, which outputs the final sensitivity analysis of all the optimizer data.

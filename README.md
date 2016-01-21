# Extraction of Priors from Neuronal Skeletons
By the No-Brainers Team: Katie, Sandra, Elizabeth

Our project's goal is the extraction of biological priors from neuronal skeletons for eventual classification of cell type. The script we produced takes .swc files (we used NeuroMorpho.org to download neuronal skeletons of interest, specifically granule and pyramidal cells of the rat hippocampus from the Turner Lab) and outputs information on branching angle, branch length, path length, branch order, number of tips, and number of branches. Specifically, the script outputs:
- the above mentioned priors' means and standard deviations of both sets of neurons
- overlaying plots using the kernal smoothing function estimate
- the statistical difference using the Hellinger distance

To run the MATLAB script, you will need to download the TREES toolbox, which can be found here: http://www.treestoolbox.org/
Your two groups of trees should be organized into two different folders. While within the folder with TREES, enter "start_trees", then enter the first of your trees' folders. Run the the first section in one folder of trees, then the second section within your second folder of trees.

Poster: https://www.lucidchart.com/invitations/accept/5dbe965d-1576-454d-a6e6-02c1114ea5d8

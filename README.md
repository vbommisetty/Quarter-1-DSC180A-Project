# Quarter-1-DSC180A-Project

## Running the Project

### Cloning the Project

1. Open Git Bash and navigate to the directory you would like to clone to.

2. type `git clone https://github.com/vbommisetty/Quarter-1-DSC180A-Project.git`

You now have access to the repo and downloaded the files, and can now create your conda environment.

### Creating Conda Environment to Run Code with environment.yml

First, make sure to have Anaconda installed. (https://www.anaconda.com/download)

After installing, open Anaconda Prompt, and navigate to your desired directory.

* Use the `cd` command to navigate. For example, `cd Desktop` or `cd MyFolder` 

Create a new conda environment using the `environment.yml` file in the repo:
- `conda env create -f environment.yml`

Make sure to activate the conda environment you just created when trying to run our code.

Note: To edit the environment name after creation, access the `environment.yml` file and edit the "Name" field.

## References

International Brain Laboratory et al. “Standardized and reproducible measurement of decision-making in mice.” eLife vol. 10 e63711. 20 May. 2021, doi:10.7554/eLife.63711

Wikipedia contributors. “International Brain Laboratory.” Wikipedia, 11 Dec. 2023, en.wikipedia.org/w/index.php?title=International\%20Brain\%20Laboratory&oldid=1189350630.

Turney, S. (2023, June 21). Poisson Distributions | Definition, Formula & Examples. Scribbr. Retrieved December 3, 2024, from https://www.scribbr.com/statistics/poisson-distribution/

Bishop, Christopher M. Pattern Recognition and Machine Learning. New York :Springer, 2006.

Shadlen, M N, and W T Newsome. “Neural basis of a perceptual decision in the parietal cortex (area LIP) of the rhesus monkey.” Journal of neurophysiology vol. 86,4 (2001): 1916-36. doi:10.1152/jn.2001.86.4.1916

Cunningham, John P., and Byron M. Yu. ‘Dimensionality Reduction for Large-Scale Neural Recordings’. Nature Neuroscience, vol. 17, no. 11, Nov. 2014, pp. 1500–1509, https://doi.org/10.1038/nn.3776.

Yu, Byron M., et al. ‘Gaussian-Process Factor Analysis for Low-Dimensional Single-Trial Analysis of Neural Population Activity’. Journal of Neurophysiology, vol. 102, no. 1, American Physiological Society, July 2009, pp. 614–635, https://doi.org/10.1152/jn.90941.2008.
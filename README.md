# HyperspectralExplorer
Can be used for visual exploration of hyperspectral images (raman .wdf files only, for now)

# Prerequisits
You should have [Anaconda](https://www.anaconda.com/download/) or [Miniconda](https://docs.conda.io/en/main/miniconda.html) installed

# Instructions:
### "Installation" (you just have to do it once)
After downloading (and unzipping) the files, open a terminal in that directory (anaconda prompt, git-bash, cmd, or whatever)
and type  
`conda env create -f environment.yml` to create the new environment and install the necessary python modules in it.

### Running the script:
Open a terminal in the directory containing the downloaded files, and type:  
`conda activate raman_svi` to activate the environment.  
Then just run the script by typing (in the terminal):  
`python HyperspectralExplorer.py`

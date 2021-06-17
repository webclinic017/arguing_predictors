<style>
	div {
		text-align: justify;
	    }
</style>

# Installation

First download the program repository.

The proof of concept program uses a Jupyter notebook as UI. The program can also be used without a Jupyter notebook by executing the main.py file. In case of executing the main.py file, a small GUI will appear after the model set-up in the file has been successfully trained. The GUI is a window containing buttons to display different statistics about the systems overall performance. However, it is recommended to use the system with a Jupyter notebook and the main.py file to demo the system.

I recommend to use Anaconda to use Jupyter notebook and manage the necessary python libraries for this program. Anaconda can be downloaded [here](https://www.anaconda.com/products/individual#Downloads).

After Anaconda has been downloaded and successfully installed, open the anaconda terminal/command line and create a virtual enviornment with the following command:

```shell
conda create -n yourenvname python=3.8. 
```

After the enviornment is installed, activate it by typing: 

```shell
conda activate yourenvname
```

Please proceed by installing Jupyter notebook by executing:

```shell
conda install jupyter notebook
```

Now, all dependiencies for the program need to be installed. First, pip install torch v.1.6 from [here](https://pytorch.org/get-started/previous-versions/). I recommend to use the CPU only version.

Finally, cd into the program directory and execute:

```shell
pip install -r requierements.txt
```

This will install all other necessary dependencies. For full reference, the full_env_requirements.txt contains all dependencies installed in the anaconda enviornment that was used to build this prototype system.

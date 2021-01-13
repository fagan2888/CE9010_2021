

## CE9010: Introduction to Data Analysis <br> Semester 2 2020/21 <br> Xavier Bresson
   

<br>
<br>

## Running Python notebooks without local Python installation
<br>

&nbsp;&nbsp;&nbsp; Run the notebooks from the cloud using Binder: Simply [click here].

[Click here]: https://mybinder.org/v2/gh/xbresson/CE9010_2021/master





<br>
<br>

## Local Python installation
<br>

Follow the following instructions to install Miniconda and create a Python environment for the course:

1. Download the Python 3.6 installer for Windows, macOS, or Linux from <https://conda.io/miniconda.html> and install with default settings. Note for Windows: If you don't know if your operating system is 32-bit or 64-bit, then open Settings-System-About-System type to find out your xx-bit system.
   * Windows: Double-click on the `Miniconda3-latest-Windows-x86_64.exe` file. 
   * macOS: Run `bash Miniconda3-latest-MacOSX-x86_64.sh` in your terminal.
   * Linux: Run `bash Miniconda3-latest-Linux-x86_64.sh` in your terminal.
1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Install git: `conda install git`.
1. Download the GitHub repository of the course: `git clone https://github.com/xbresson/CE9010_2021`.
1. Go to folder CE9010_2021 with `cd CE9010_2021`, and create a Python virtual environment with the packages required for the course: `conda env create -f environment.yml`. Note that the environment installation may take some time.  



   Notes: <br>
      Direct link to conda is `https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh` for Linux, `https://repo.continuum.io/miniconda/Miniconda3-latest-MacOSX-x86_64.sh` for MacOS and `https://repo.continuum.io/miniconda/Miniconda3-latest-Windows-x86_64.exe` for Windows. <br>
      The installed conda packages can be listed with `conda list`.<br>
      Some useful Conda commands are `pwd`, `cd`, `ls -al`, `rm -r -f folder/`<br>
      Add a python library to the Python environment: `conda install -n CE9010_2021 numpy` (for example)<br>
      Read [Conda command lines for packages and environments]<br>
      Read [managing Conda environments]

[managing Conda environments]: conda/conda_environments.pdf

[Conda command lines for packages and environments]: conda/conda_cheatsheet.pdf





<br> 
<br> 

## Running local Python notebooks 
<br>


1. Windows: Open the Anaconda Prompt terminal from the Start menu. MacOS, Linux: Open a terminal.
1. Activate the environment. Type: `source activate CE9010_2021` or `conda activate CE9010_2021`.
1. Go to folder `CE9010_2021/` and start Jupyter with `jupyter notebook`. The command opens a new tab in your web browser.
1. Open, edit and run the notebook `tutorial01.ipynb` in your browser.



	Notes: <br> 
      Windows: Folder CE9010_2021 is located at `C:\Users\user_name\CE9010_2021`. MacOS, Linux: `/Users/user_name/CE9010_2021`.<br>
      List of [git commands]<br>

[git commands]: git/git_commands.pdf









[git]: https://git-scm.com
[python]: https://www.python.org
[scipy]: https://www.scipy.org
[anaconda]: https://anaconda.org
[miniconda]: https://conda.io/miniconda.html
[conda]: https://conda.io
[conda-forge]: https://conda-forge.org


<br>
<br>
<br>
<br>
<br>
<br>




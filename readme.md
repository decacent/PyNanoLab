## PyNanoLab is an all-in-one GUI software for data analysis and visualization, expecially for nanopore analysis.
![PyNanoLab UI](https://pynanolab.com/images/1.png)


## Installition
In the version 3.X, binary installer (*.exe) is not provided anymore owing to the complex workflow and lost feature and performance.

We recommend you use the pip install to obtain all the advanced features.

### System Required

Firstly, you should have already installed the python or conda virtual environment in your system.

[Miniconda](https://docs.conda.io/en/latest/miniconda.html) is recommended. And you should add the conda to your system environment variable.

In windows, you also need to install a terminal. [git-windows](https://git-scm.com/download/win) or [windows-terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701) is recommended.

### 1. Create a new python virtual environment

PyNanoLab depend on th PySide6 to create its GUI. And it's not compatible with the other PyQt package. So we highly recommend to install pynanolab to a new python virtual environment.

use following command in a terminal:
```sh
conda create -n pnl python=3.11.3  
source activate
conda activate pnl # activate the pnl environment.
conda install numpy # optional, install the numpy-MKL to speed up the software.
```
So, you have created a new python virtual environment and activated it.
The name is pnl, and you can change the name to anything you want, and the python  version is specified to 3.11.3.

### 2. Install the pynanolab by pip
After version 3.x, we provide a pip package, you can directly install as general python packages.

If you can't get the package from pip on your system, such as the Apple M1 or other Linux. You can tyr to search and download the wheel file from our [Github release](https://github.com/decacent/PyNanoLab/releases) for your special OS.
```sh
pip install pynanolab 
```
Use the above command, the pynanolab will be installed automaticly. And a entry fille will be created in the **Scripts** folder of the "pnl" virtual environment. In windows is named "pynanolab.exe" and "pynanolab" in Linux and MacOSX.

Then, you can directily conduct the following command to open it in a terminal with pnl virtual environment activated.
```sh
pynanolab
```
If you want to create a shortcut or a desktop entry. Use the following command:
```
pnl-shortcut
```

### 3. Upgrade pynanolab
If you use the pip installtion. You can upgrade the packages manually using the following command:
```
pip install --upgrade pynanolab
```

For binary installation, such as the .exe in windows. If we don't provide a new exe file in the [sourceforge](https://sourceforge.net/projects/pynano/files/). You can manually download the *.whl file for your system from pypi or GitHub. Then, you can unzip the *.whl file use any compressed software (such as 7zip in Windows or unzip in Linux). And you will find the pynanolab folder in the archive. Delete the same "pynanolab" folder in the PATH that you installed the PyNanoLab and replace with the new package in the archive.

## Signal Extraction
- Extract signal automaticall
- Multiple File management
- Raw data denoise and filter   
![image](https://user-images.githubusercontent.com/28666678/165077241-8336bbce-7d7a-476f-a005-f3c2929f678a.png)
## Data Processing
- Data filter and calculate with pandas
- iPython integration
- Manage your data like the excel     
![image](https://user-images.githubusercontent.com/28666678/165077360-9aa423a5-6c74-4255-bcfe-aed67d4256fb.png)
##  Visualization
- Visualize data with matplotlib
- Interactive setup Figure
- Rebuild data and fig from project file.   
![image](https://user-images.githubusercontent.com/28666678/165077379-11e68425-a4c9-462f-8c35-bf2a7c4cbcec.png)
##  Curves Fitting
- Curves fitting with lmfit
- Multiple build-in models
- Interactive fitting   
![image](https://user-images.githubusercontent.com/28666678/165077503-1fc5e17d-8953-49aa-8322-fd1393f8898b.png)
##  Clustering
- Clustering of with scikit-learn
- Interactive parameter setting
- Real-time visualization    
![image](https://user-images.githubusercontent.com/28666678/165077568-f5597b79-bd2f-4ddd-a34a-b4f18f035280.png)
## Nanopore ToolBox
- Custom and Auto signal analysis
- Time-Frequency spectral analysis
- Signal batch processing  
![image](https://user-images.githubusercontent.com/28666678/165077633-a98d7d88-f3ec-4ecc-8787-be1238501ee5.png)


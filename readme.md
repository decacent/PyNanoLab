## PyNanoLab is an all in one GUI software for nanopore data analysis. It is also a free alternatives software for OrignaLab，
### Installition
Briefly， you could download the binary installer we have already builded for your operation system from [Here](https://sourceforge.net/projects/pynano/files/).
#### Source install tutorial
tips: this is only recommended Linux and Mac OS. In windows, you could download the .exe installation package we provided.  
##### 1. Download the source file for you operation system. and unzip it to a folder.  You folder tree looks like:   
  ---|   
      --- pynanolab   
      --- main.py   
      --- requirements.txt   
      --- run.sh  
 Then entrance this folder, the main.py is the entrance file of PyNanoLab.  
##### 2. build the pynanolab runtime environment
    use following command in terminal:         
``` sh  
    conda create -n pnl python=3.10.4 -c conda-forge    
    source activate # only needed in windows system when you use the git-bash for windows.  
    conda activate pnl      
```   
Then, if you want use intel-mkl based numpy to speed up the PyNanoLab:  
`conda install numpy`   
And Then:     
`pip install -r requirements.txt`   
- tips: for some requirement,you should have compiler in your system to build the package.
- in windows: Visual Studio; Linux: GCC ; Mac OS X： Xcode.
##### 3. Run the PyNanoLab: 
 use following command in terminal in the same folder of main.py: 
 ```
 conda activate pnl
 python main.py
 ```
 or just double click the file 'run.sh'.
         
### More and download in [PyNanoLab Site](https://www.pynanolab.com/).
![image](https://user-images.githubusercontent.com/28666678/165077068-2ae07266-1f8f-4f2a-b268-c432c4fea2c9.png)
PyNanoLab contains a variety of tools to complete the data analysis, statistics, curve fitting, and basic machine learning application. Visualization in pynanolab is based on matplotlib. The setup tools is desinged to control and set-up all the details of the figure with a GUI.
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
## Manual Analysis
- Custom signal analysis
- Time-Frequency spectral analysis
- Signal batch processing  
![image](https://user-images.githubusercontent.com/28666678/165077633-a98d7d88-f3ec-4ecc-8787-be1238501ee5.png)


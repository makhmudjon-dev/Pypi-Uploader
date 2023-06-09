# Pypi-uploader
#### Upload your Python libraries to PyPi with a beautiful interface.

<a href="README_RU.md" ><img src="https://emojio.ru/images/twitter-64/1f1f7-1f1fa.png" width="60" height="60"></img></a>
<a href="README.md" ><img src="https://emojio.ru/images/twitter-64/1f1fa-1f1f8.png" width="60" height="60"></img></a>
</br>

This program is written using the <a href="https://pypi.org/project/PySimpleGUI/">PySimpleGUI</a> library.

Just run <a href="main.py">main.py</a> and follow the instructions on the screen.</br>
The program will automatically install the necessary libraries, compile your project into an archive and upload it to Pypi or Test Pypi.</br>
After uploading, program can also clean up all generated files.

#### Important! Selected project folder should contain the ```__init__.py``` file! This is the main file of your library.

#### Folder hierarchy:
```
.../Any_folder_name
     |__Pypi-uploader.py
     |__requirements.txt (optional)
     |__Your_Project_Folder/
         |__ __init__.py
         |__Other_files... 
```

#### If you are using api key:

**Username:** ```__token__``` </br>
**Password:** *The token value, including the ```pypi-``` prefix*

![Image](https://user-images.githubusercontent.com/128493258/236375512-8fac376f-69a3-48e6-9662-1b6bac0d3a08.png)

### Possible mistakes:
<ul>
<li> Login or password is incorrect (or API token if you uploaded through it). </li>
<li> You signed up for PyPi, and you are trying to upload a project to Test Pypi (or vice versa). </li>
<li> A library with this name already exists. So if this is your library - change the version. </li>
</ul>

It is good practice to have your virtual environment for each project. 

This repository has been developed using python 3.11.3
```
python3 -m venv hand_gesture_env
source hand_gesture_env/bin/activate #on MacOS
#hand_gesture_env\Scripts\activate.bat #on Windows
```

Install required packages. If you get an error, you can change the package version to the ones that are currently available on pip. If a package is not necessary, you can also comment it out in requirements.txt.

```
pip install -r requirements.txt
```

Making environment available to jupyter

```
#pip install ipykernel #if ipykernel is not already installed
python -m ipykernel install --user --name=hand_gesture_env
```

To deactivate

````
deactivate

```
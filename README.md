# create-venv-python-2.7

## Requirements
1. Download and Install Python version 2.7.18 at
[Python 2.7.18 Officail Website](https://www.python.org/downloads/release/python-2718/).
2. File will default located at C:\Python27 then change the name of python.exe to python2.exe so you can use python2 as a command in terminal
3. Add PATH to environment variable system > advance system setting > Environment variables > PATH > new  then add the file respiratory in 2nd step

## If you are finish above requirements
4. run this command in terminal:
```
python2 -m pip install virtualenv
```
5. create venv with this command
```
python2 -m virtualenv venv
```
6. activate the venv: .\venv\Scripts\activate.bat (In Powershell)

### Note: If you’re using git bash 
```
cd  /venv/Scripts 
```
then run this command
```
 . activate
```

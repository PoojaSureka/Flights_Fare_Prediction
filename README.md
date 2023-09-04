
## Flight-Fare-Prediction

A Machine Learning Web App that can predict the flight prices. The app is created with the help of ```Flask``` and ```Python.```

## A glimpse of the web app:

https://github.com/PoojaSureka/Flights_Fare_Prediction/assets/117584271/80610f91-d0ca-4ed5-84cf-5731be3a0f9c

## Directory Tree
--> Here are some details of the subdirectories and files that the repository contains. 
```
├───.idea
│   └───inspectionProfiles
├───Flight Price Dataset
├───static
└───templates
```

## Description

* Static Folder contains the favicon as well as the css file which describes the HTML elements of the web app.
* Template folder contains the html file which depicts the format of the web page.
* Flight Price Dataset is the dataset file which is the excel format.
* Flight_Fare_Prediction.ipynb contains all the notebook code, the execution results as well as the codes that has helped in generating the model
  for the web app.
* Procfile includes the code '''web: gunicorn app:app'''which depicts that gunicorn commands are run by the application's containers on the platform. 
  To create a procfile run the following command on command prompt. ``` echo web: gunicorn app:app --preload > Procfile ```
* README.md includes the stucture that provides a detailed description of my GitHub project.
* app.py includes the all the routes and functions to perform the actions of web app. 
  This file is the root of our Flask application which we will run in the command line prompt.
* flight_rf.pkl is the random forest regression model that is the core of my web application.
* Requirements.txt file includes all the libraries that has been used to create the web app. After installing all the required packages,
'''pip freeze > requirements.txt''' command was run on the command prompt to create the requirements.txt file

## Libraries Used
--> This section contains the list of the libraries that have been used to create the web app. 
```
altair==4.2.2
annotated-types==0.5.0
asttokens==2.2.1
attrs==22.2.0
backcall==0.2.0
bcrypt==4.0.1
beautifulsoup4==4.12.2
blinker==1.6.1
cachetools==5.3.0
certifi==2022.12.7
cffi==1.15.1
charset-normalizer==3.1.0
click==8.1.3
click-plugins==1.1.1
cligj==0.7.2
colorama==0.4.6
colorlover==0.3.0
comm==0.1.3
contourpy==1.0.7
cufflinks==0.17.3
cycler==0.11.0
dacite==1.8.1
debugpy==1.6.7
decorator==5.1.1
dnspython==2.3.0
docopt==0.6.2
docx2txt==0.8
email-validator==1.3.1
entrypoints==0.4
et-xmlfile==1.1.0
exceptiongroup==1.1.2
executing==1.2.0
fastjsonschema==2.17.1
Fiona==1.9.4.post1
Flask==2.2.3
Flask-Bcrypt==1.0.1
Flask-Cors==3.0.10
Flask-Login==0.6.2
Flask-Mail==0.9.1
Flask-SQLAlchemy==3.0.3
Flask-WTF==1.1.1
fonttools==4.39.3
geopandas==0.13.2
gitdb==4.0.10
GitPython==3.1.31
greenlet==2.0.2
h11==0.14.0
html5lib==1.1
htmlmin==0.1.12
idna==3.4
ImageHash==4.3.1
importlib-metadata==6.3.0
ipykernel==6.22.0
ipython==8.12.0
ipywidgets==8.0.7
itsdangerous==2.0.1
jedi==0.18.2
Jinja2==3.1.2
joblib==1.1.1
jsonschema==4.17.3
jupyter_client==8.2.0
jupyter_core==5.3.0
jupyterlab-widgets==3.0.8
kiwisolver==1.4.4
lxml==4.9.2
markdown-it-py==2.2.0
MarkupSafe==2.1.2
matplotlib==3.7.1
matplotlib-inline==0.1.6
mdurl==0.1.2
missingno==0.5.2
mlxtend==0.22.0
multimethod==1.9.1
mysql-connector==2.2.9
mysqlclient==2.1.1
nbformat==5.9.0
nest-asyncio==1.5.6
networkx==3.1
nltk==3.8.1
numpy==1.23.5
openpyxl==3.1.2
outcome==1.2.0
packaging==23.1
pandas==1.5.3
pandas-profiling==3.2.0
parso==0.8.3
patsy==0.5.3
phik==0.12.3
pickleshare==0.7.5
Pillow==9.5.0
pipreqs==0.4.13
platformdirs==3.3.0
plotly==5.15.0
prompt-toolkit==3.0.38
protobuf==3.20.3
psutil==5.9.5
pure-eval==0.2.2
pyarrow==11.0.0
pycparser==2.21
pydantic==1.10.11
pydantic_core==2.3.0
pydeck==0.8.1b0
Pygments==2.15.0
PyInputPlus==0.2.12
pymongo==4.4.1
Pympler==1.0.1
pyparsing==3.0.9
pyproj==3.6.0
pyrsistent==0.19.3
PySimpleValidate==0.2.12
PySocks==1.7.1
python-dateutil==2.8.2
pytz==2023.3
pytz-deprecation-shim==0.1.0.post0
PyWavelets==1.4.1
pywin32==306
PyYAML==6.0.1
pyzmq==25.0.2
regex==2023.5.5
requests==2.28.2
rich==13.3.4
scikit-learn==1.2.2
scipy==1.10.1
seaborn==0.12.2
selenium==4.11.2
shapely==2.0.1
six==1.16.0
smmap==5.0.0
sniffio==1.3.0
sortedcontainers==2.4.0
soupsieve==2.4.1
SQLAlchemy==2.0.7
stack-data==0.6.2
statsmodels==0.14.0
stdiomask==0.0.6
streamlit==1.21.0
tangled-up-in-unicode==0.2.0
tenacity==8.2.2
tex==1.8
threadpoolctl==3.1.0
toml==0.10.2
toolz==0.12.0
tornado==6.2
tqdm==4.65.0
traitlets==5.9.0
trio==0.22.2
trio-websocket==0.10.3
typeguard==2.13.3
typing_extensions==4.7.1
tzdata==2023.3
tzlocal==4.3
urllib3==1.26.15
validators==0.20.0
visions==0.7.5
watchdog==3.0.0
wcwidth==0.2.6
webencodings==0.5.1
Werkzeug==2.2.3
widgetsnbextension==4.0.8
wordcloud==1.9.2
wsproto==1.2.0
WTForms==3.0.1
xlrd==2.0.1
yarg==0.1.9
ydata-profiling==4.3.2
zipp==3.15.0

```

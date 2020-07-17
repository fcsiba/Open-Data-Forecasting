# Open-Data-Forecasting
FYP Fall 2019

Using census data provided by LFD, we are predicting the population of Pakistan till the year 2025 on National, Provincial, and District levels.

## Requirements
```bash
python==3.6 [and above]

anaconda==4.8.3
```
## Packages

Use the package manager [conda](https://pip.pypa.io/en/stable/) to install the python libraries.

```bash
conda install -c package-name
```
## Packages Required
```bash
streamlit==0.62.1

pydeck==0.4.0b2

pandas==1.0.5

plotly==4.8.2

altair==4.1.0
```

## How to run the App

- After downloading the repository, create a new environment on Anaconda.

- Launch VS Code through your Anaconda Navigator

- Open the repository folder in your VS Code

- Create a new terminal on your VS Code

- Use conda install -c package-name example: conda install -c plotly plotly

- Once you're done installing all the packages, make sure your python interpreter is set to the environment you've made in step 1

- In your terminal type the following command 
```bash
streamlit run app.py
```
  - A message like this will appear on your terminal:
```bash
You can now view your Streamlit app in your browser. 

Local URL: http://localhost:8501 

Network URL: http://192.168.86.126:8501
```
Click on the local URL to view your application on a browser.


## See Also
[Open Data Forecasting](https://odf-fyp.herokuapp.com/)

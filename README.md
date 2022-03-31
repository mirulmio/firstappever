# firstappever
This is my first attempt to create a new app by myself. It may looks ridiculous and weird but yeah, any helpful comments surely helps me a lot.

Procfile = file for heroku
100% if cloud using linux due to open-source
In procfile, we write setup.sh for heroku to run setup.sh; streamlit run myfirstapp.py means run the python file

setup.sh file is the file that must have to run streamlit in heroku
heroku is empty, that's why setup.sh allows heroku to be what we want
setup.sh provides environment in heroku

runtime.txt shows the version of Python we want to use
some Python version works, some don't
!pip freeze tells you which modules you've installed with pip install and the versions of these modules that you are currently have installed on your computer

requirements.txt means what version of streamlit, numpy and pandas used

in myfirstapp.py, initialise the requirements first (streamlit, pandas, numpy, time)
header,checkbox is the function in streamlit for UI
input widget means interactive widget (checkbox and stuff)
write means write the sentences. if u put triple star means everything within the triple star is an essay.
[hyperlink](website) syntax; unsafe_allow_html means we allow python to access html despite unsafe
sidebar.selectbox means sidebar menu; if you dont have sidebar they will show the option at the main page
time.sleep means the time the bar updating/loading ; time.sleep = 0.1 means from 0 to 1 takes 0.1 seconds

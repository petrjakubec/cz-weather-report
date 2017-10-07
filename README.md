# cz-weather-report
author: Petr Jakubec

This CLI app will give you weather report for entered city. It will work properly only with Czech cities which are listed here: https://www.wunderground.com/weather-forecast/CZ/?hdf=1

### INPUT
```
What czech city do you want the weather for (Brno)? Brno
```
### OUTPUT
```
The temp in Brno, Czech Republic is 12.2 °C and Partly Cloudy
```

For running this CLI Python3 app you need to have requests, bs4, collections modules imported. You can open CLI and just follow this workflow:

### Create own virtual environment to run this:
```
mkdir python_environments
cd python_environments
python -m virtualenv
virtualenv --python=python3 ./weather_py3
cd weather_py3/bin
. activate
```
### Installation of non-standard libraries
```
pip install requests beautifulsoup4
```

### Run this app by
```
cd /path/to/our/program.py
python program.py
```

### Deactivation of virtual environment
```
deactivate venv
```

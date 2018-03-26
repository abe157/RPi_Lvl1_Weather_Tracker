#Source Project is based off of 
https://github.com/HackerHouseYT/Smart-Mirror

# Smart-Mirror
Raspberry powered mirror which can display the news, weather, and time.

## Installation and Updating
### Code
If you have [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) installed, clone the repository.

```
git clone https://github.com/abe157/RPi_Lvl1_Weather_Tracker.git
```

**Alternatively, you can download a zip file containing the project (green button on the repository page)**

Navigate to the folder for the repository

```
cd RPi_Lvl1_Weather_Tracker
```

### Install your dependencies 
make sure you have [pip](https://pip.pypa.io/en/stable/installing/) installed before doing this

```
sudo pip install -r requirements.txt
```

```
sudo apt-get install python-imaging-tk
```

## API Weather Service
### Register
First thing is to create a new [Dark Sky API](darksky.net/dev/account) account where your program will be pulling weather information from 

### Add your api token
Use your favorite editor to edit `WeatherTracker.py` but by default, most systems have `nano` editor. Use your editor to edit the file

```
nano WeatherTracker.py
```

replace `weather_api_token` with the token you got from forecast.io

## Running
To run the application run the following command in this folder

```
python WeatherTracker.py
```


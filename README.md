# Zoom Meeting Bot
### This is meant for educational purposes only and merely an experiment to familiarize myself with python and its web controlling capabilites from the selenium package.
This is a python zoom bot which automates the process of joining a zoom meeting. Script is meant to run at a certain time (zoom meeting start time). Extensibility will be added to exit based on change in class size, time, etc. 

## installation
before running the bot `python3 ./zoom_bot.py` you must have pip installed and then install:

selenium: `pip3 install selenium`

keyboard: `pip3 install keyboard`

And set up PATH for geckodriver executable (Proxy for using W3C WebDriver-compatible clients to interact with Gecko-based browsers, e.g., FireFox)

`sudo ln -s <complete path to geckodriver executable> /usr/local/bin`

The <> above should be the director where you clone this repo with the addition of 'geckodriver' to the end (complete path).


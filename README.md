# Storyful Test Exercise 

This project contains code for below usecases:

- Functional Test:
  -   Verify Location Picker works and searches result based on given filter
  -   Verify user can save story
  -   Verify user can remove saved story
  


##### Prerequisites
- Python 3.7.2 (installed and configured)

```
python -m venv venv
source venv/bin/activate
 pip install -r requirements.txt
```
- ChromeDriver is setup on and added to PATH variable on machine
    How to Setup ChromeDriver [Mac](https://medium.com/@tripleaceme/setting-up-chrome-driver-on-mac-0f32580912c3)  [Windows](https://medium.com/@patrick.yoho11/installing-selenium-and-chromedriver-on-windows-e02202ac2b08).

##### Running the tests
```
robot -d results tests/  
 ```

##### Open Issues/ Observation 
1. Due to Captcha - there is a 20 seconds delay in the test setup, make sure you perform captcha verification manually within 20 seconds 
2. At the moment, Test password is checked in for the trial account for simplicity of the execution however ideally it should be read from environment variable
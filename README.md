# swagbot
Launches a headless web browser to watch videos on swagbucks

## Usage
### Set up chromedriver
copy chromedriver.exe to C:\Windows if on windows

symlink chromium-chromedriver to chromedriver if on linux

### Create config.json
Follow the format in config.json.example
Copy your login cookies (In chrome go to developer tools/application and click on cookies)

### Install dependencies
run
    virtualenv python3 env
    source env/bin/activate (or on windows env/Scripts/activate.bat)
    pip install -r requirements.txt

### Run
    python3 main.py
### Selenium and Python powered automation script

This script is used to automate information update on the job portal "Naukri". Most recruiters may filter users having the most recent updates on their profile.

Use this script to update your Naukri Profile on schedule everyday, this can be completed in seconds.

In order to use this, you need Git, Python 3, Google Chrome and Selenium webdriver for Chrome in your machine.

## Installation

Install [Python 3.10+](https://www.python.org/getit/) and run the below commands

```bash
git clone <repo-url>
cd Naukri
pip install --upgrade pip
python3 -m venv .venv      # create virtual environment for installing dependencies
./.venv/bin/activate.ps1   # source ./.venv/bin/activate  # command for macOS/linux
pip install -r requirements.txt
```

Update ResumePath, Naukri login username, password, mobile number in naukri.py file and then run the script. 
Use .env to configure secrets. 

```bash
NAUKRI_USERNAME=<username_or_email>
PASSWORD=<password>
PHONE=<phone>
ORIGINAL_RESUME_PATH=<original_resume>
MODIFIED_RESUME_PATH=<modified_resume>
```

```bash
python naukri.py
```


## Browsers support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)<br>Chrome |
| --------- |
| last 10 versions

Recent stable chrome versions (windows) (replace in browsers.py)

```python
chrome_ver = [
    '133.0.6943.35','132.0.6834.161','132.0.6834.160','132.0.6834.159',
    '132.0.6834.112','132.0.6834.111','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265','132.0.6834.110','131.0.6778.267',
    '132.0.6834.84','132.0.6834.83','131.0.6778.266','131.0.6778.265',
    '132.0.6834.110','131.0.6778.267','132.0.6834.84','132.0.6834.83',
    '131.0.6778.266','131.0.6778.265',
]
```
Source: https://chromiumdash.appspot.com/releases?platform=Windows 


## Contributors

 - Naveenchandar ([navchandar](https://github.com/navchandar))
 - Jay Bhavsar ([jbhv12](https://github.com/jbhv12))
 - Kowshika ([kowshika-n](https://github.com/kowshika-n))

## Reference Links

[Python 3+](https://www.python.org/downloads/)

[Selenium 3+](http://seleniumhq.org/download/)

[Google Chrome](https://www.google.com/intl/en/chrome/browser/desktop/index.html?standalone=1)

[Chrome Driver](https://chromedriver.chromium.org/downloads)

[How to Use Task Scheduler](https://www.wikihow.com/Use-Task-Scheduler-(in-Vista))


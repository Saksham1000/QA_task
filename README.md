
# Signup page automation

This script automates the end-to-end signup flow of the Authorized Partner web application, including email OTP verification using Mailosaur.

The test is implemented using Python + Selenium WebDriver with the unittest framework.

# Prerequisites

To run the script, ensure the following are installed :

    1) Software reqirements
        - Python: 3.8 or higher
        - Google Chrome: Latest stable version
        - ChromeDriver: Version matching your Chrome browser
    2) Python Libraries
        - selenium
        - mailosaur
        - python-dotenv
Command for installation :

```bash
pip install selenium mailosaur python-dotenv
```

## Environment and setup

Language and framework:
    
    Language: Python
    Test Framework: unittest
    Automation Tool: Selenium WebDriver
    Email Testing: Mailosaur API
WebDriver Configuration

    Browser: Google Chrome
    Driver: ChromeDriver
## Environment Variables

To run the script, you will need to add the following environment variables to your .env file

`MAILOSAUR_API_KEY`

`MAILOSAUR_SERVER_ID`

`MAILOSAUR_SERVER_DOMAIN`


## How to Run the Script

Run the Test

 ```bash
python signup_automate_script.py

 ```
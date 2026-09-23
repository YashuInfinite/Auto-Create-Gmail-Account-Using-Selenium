# Auto-Create-Gmail-Account-Using-Selenium
Python Selenium project demonstrating automated browser form interactions for Gmail signup workflow.

# Auto Create Gmail Accounts

Automate the Gmail account signup workflow using **Python and Selenium WebDriver**.

> ⚠️ **Educational / Reference Project**  
> This repository is intended for learning and understanding Selenium browser automation. Use it only with accounts, websites, and environments where you have permission to automate.

## 📌 Features

- Automates browser-based form interaction using Selenium
- Generates random names from the included name lists
- Demonstrates form filling and dropdown selection
- Demonstrates Selenium WebDriver automation
- Uses a specific Selenium version for compatibility with the original code

## 🛠️ Requirements

- Python 3.x
- Google Chrome
- ChromeDriver compatible with your Chrome version
- Selenium `4.2.1`

## 📥 Installation

Install the required Selenium version:

```bash
pip uninstall selenium
pip install selenium==4.2.1
```

Check the installed version:

```bash
python -c "import selenium; print(selenium.__version__)"
```

## 🚗 ChromeDriver

Download a ChromeDriver version compatible with your installed Chrome browser.

Place the ChromeDriver executable in an appropriate location that your Selenium setup can access.

> ChromeDriver availability and installation methods can change over time, so use the current official Chrome/Selenium documentation when setting up a new environment.

## ⚙️ Configuration

Before running the program, review the configuration values in the Python file.

The original script contains date-related values around **lines 113–119**. Update those values according to your test configuration.

For example:

```python
day = "20"
year = "1994"
```

## ▶️ Running the Program

Open Command Prompt in the project directory and run:

```bash
python g.py
```

You can also run the Python file directly if Python is configured correctly on your system.

## 🔧 Selenium Version

The original code was written around an older Selenium API.

If you use the current Selenium versions, some older commands such as:

```python
driver.find_element_by_id(...)
driver.find_element_by_name(...)
driver.find_element_by_xpath(...)
```

may not work.

The Selenium 4 syntax is:

```python
driver.find_element(By.ID, "element_id")
driver.find_element(By.NAME, "element_name")
driver.find_element(By.XPATH, "xpath")
```

For compatibility with the original project, the tested dependency is:

```bash
pip install selenium==4.2.1
```

Check your version with:

```bash
python -c "import selenium; print(selenium.__version__)"
```

## ⚠️ Important Notice

This project is provided **for educational and reference purposes only**.

Do not use browser automation to:

- Create accounts in bulk
- Circumvent verification or security mechanisms
- Bypass CAPTCHA, OTP, rate limits, or other platform protections
- Violate Google's Terms of Service or other applicable policies
- Perform spam, abuse, or other unauthorized activities

Use Selenium automation only in environments where you have permission to automate.

## 📚 Learning Purpose

The main purpose of this project is to demonstrate concepts such as:

- Python + Selenium
- WebDriver
- Browser automation
- Element selection
- Form interaction
- Dropdown handling
- Keyboard actions
- Random test data
- Basic automation workflows

## ⚖️ Disclaimer

The author provides this project for educational purposes and does not encourage unauthorized automation, abuse, spam, or attempts to bypass platform security.

Users are responsible for ensuring that their use of the code complies with the applicable laws, terms of service, and policies of the websites and services they interact with.

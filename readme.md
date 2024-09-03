# Tinder Bot Automation

This project automates interactions on Tinder using Selenium. The bot can log in through Facebook, handle pop-ups, and swipe left (nope) or right (like) based on the specified function. The code uses Python with Selenium WebDriver for Firefox, and includes error handling for common exceptions.

## Prerequisites

- Python 3.x
- Selenium (`pip install selenium`)
- Firefox WebDriver (`geckodriver`)
- WebDriver Manager for automatic driver installation (`pip install webdriver-manager`)
- `geckodriver` (should be in `PATH`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tinder-bot-automation.git
   cd tinder-bot-automation
   ```
   2. Install required Python packages:
```bash
   pip install -r requirements.txt
   ```
3. Set your Facebook credentials in the script:
```bash
   FB_EMAIL = "your_facebook_email"
FB_PASSWORD = "your_facebook_password"
   ```
## Usage
1. Run the script: 
```bash
   python tinder_bot.py
   ```
2. The bot will: 
- Log in To inder via Facebook.
- Swipe left or right based on the function you uncomment (click_like() or click_nope()).

## Important Notes
- Ensure the Firefox browser is installed on your machine.
- Use responsibly, adhering to Tinder's terms of service.
## Disclaimer
This project is for educational purposes only. Automating interactions on platforms like Tinder may violate their terms of service, so proceed with caution.
## License
License
This project is licensed under the MIT License.
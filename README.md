# Instagram Login Page (Educational Purpose Only)

This is a simple HTML-based Instagram login page designed for educational purposes. It demonstrates how to create a login form and send user input (username, password, and location data) to a Telegram bot using JavaScript.

---

## Features
- **Login Form**: Mimics the Instagram login page.
- **Telegram Bot Integration**: Sends user input (username, password, and location data) to a Telegram bot.
- **Responsive Design**: Works on both desktop and mobile devices.

---

## How to Use

### 1. Create a Telegram Bot
1. Open Telegram and search for the **BotFather**.
2. Start a chat with BotFather and use the `/newbot` command.
3. Follow the instructions to name your bot and get the **bot token**.
4. Save the bot token for later use.

### 2. Get Your User ID
1. Open Telegram and search for the **userinfobot**.
2. Start a chat with the bot, and it will reply with your **user ID**.
3. Save the user ID for later use.

### 3. Update the Script
Replace the following placeholders in the script with your actual bot token and user ID:
- `botToken`: Replace `"1234567890:ABCdefGHIjklMNO_pqrSTUvwXYZ"` with your bot token.
- `chatId`: Replace `"123456789"` with your user ID.

### 4. Run the Script
1. Open the HTML file in a browser.
2. Enter a username and password in the login form.
3. Submit the form, and the data will be sent to your Telegram bot.

---

## Code Explanation

### HTML
- The HTML structure mimics the Instagram login page.
- Includes a form with fields for username and password.

### CSS
- Styling is provided to make the page look like Instagram's login page.
- Responsive design ensures compatibility with different screen sizes.

### JavaScript
- Handles form submission.
- Fetches user location data using the `ipapi.co` API.
- Sends the data to a Telegram bot using the Telegram Bot API.

---

## Disclaimer
This project is for **educational purposes only**. Do not use it for malicious activities. Always ensure you have proper authorization before collecting or sharing user data.

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

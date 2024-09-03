**[Intro]**
"Hey everyone! Today, I'm going to walk you through how to set up a Telegram bot from scratch. We’ll cover everything from getting your Telegram API ID and hash to installing and running the bot on your computer. Let’s get started!"

**[Step 1: Install Node.js]**
"First things first, you need to make sure you have Node.js installed on your computer. If you don't have it installed yet, don’t worry! [download and install Node.js](https://nodejs.org/en/download/package-manager)."

**[Step 2: Get Your Telegram API ID and Hash]**
"Now, let's get our Telegram API ID and hash. These are essential for creating the session for the bot."
1. "Go to [https://my.telegram.org](https://my.telegram.org)"
2. "Log in with your phone number, and enter the code sent to your phone."
3. "Once logged in, click on 'API development tools'."
4. "Create a new application by filling out the form. The required fields are 'App title' and 'Short name'."
5. "Click on 'Create application'."
6. "Copy your API ID and API hash, and paste them into a notepad—we’ll need them later."

**[Step 3: Download and Install the Bot]**
"Next, let’s download and install the bot. For this tutorial, I’ll use an example bot from GitHub."
1. "Visit the GitHub repo of the bot you want to download. For example, [RockyRabbitBot](https://github.com/Freddywhest/RockyRabbitBot) (link in the description)."
2. "You can either download the zip file or use Git to clone it to your computer."
   - "To clone it using Git, type the following commands:"
     ```bash
     git clone https://github.com/FreddyWhest/MajorBot.git
     cd MajorBot
     ```

**[Step 4: Install Dependencies]**
"For Linux and macOS users:"
1. "Navigate to the bot's directory and make the installation script executable:"
   ```bash
   chmod +x check_node.sh
   ./check_node.sh
   ```
   OR
   ```bash
   npm install
   cp .env-example .env
   nano .env # Here you must specify your API_ID and API_HASH, the rest is taken by default
   node index.js
   ```

"For Windows users:"
1. "Double-click on `INSTALL.bat` in the MajorBot directory to install the dependencies."
2. "Then, double-click on `START.bat` to start the bot."

   OR
   ```bash
   npm install
   cp .env-example .env
   # Specify your API_ID and API_HASH, the rest is taken by default
   node index.js
   ```

**[Step 5: Create a Session]**
"Let’s create a session for the bot:"
1. "Open the `.env` file in the bot's directory."
2. "Copy the API ID and hash you got from Telegram, and assign them to `API_ID` and `API_HASH`."
3. "Save the `.env` file."
4. "Open your terminal, navigate to the bot's directory, and run:"
   ```bash
   node index.js
   ```
5. "Choose 'Create session'."
6. "Enter the session name, your phone number, and the code sent to your Telegram."

**[Step 6: Run the Bot]**
"Finally, let's run the bot:"
1. "Open your terminal, navigate to the bot's directory, and run:"
   ```bash
   node index.js
   ```
2. "Choose 'Run bot'. And that's it—your bot is now up and running!"

**[Outro]**
"That’s all for today’s tutorial! If you found this helpful, don’t forget to give it a star!"

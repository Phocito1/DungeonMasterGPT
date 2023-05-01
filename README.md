The following is a fork of Zhoug's original DungeonAI. There are a number of changes, including the use of an API key instead of a session key which simplifies the configuration, but will incur costs on the API.

I also modified the hardcoded variables to include prompts for responses to GENDER / RACE / CLASS to allow the user to properly choose. The prompts are still the same and untouched, but they can be configured.

Requirements:

Node.js: https://nodejs.org/en/download
- Follow the instructions on the website to download and install the latest version, make sure to select install all requirements during the installation

chatgpt:
- Run "npm install chatgpt" in your shell to install

dotenv:
- Run "npm install dotenv" in your shell to install

ChatGPT API Key:
- Retrieve your API key from https://platform.openai.com/account/api-keys after configuring billing.
- Copy example.env and name it just ".env" then input your API key after OPENAI_API_KEY=

To run the code:
- Open your shell (powershell on windows), navigate to the folder where your source code is stored (cd for changing directory) and type: "npm start" to begin!

# Codex, chatGPT app

## What it Does:

This application was built to provide me assistance to quickly achieve programming tasks. [KevinEverywhere](https://github.com/KevinEverywhere/open_ai_codex) helped me put this together. Thanks, Kevin!

# Implementation of a ChatGPT AI Application

This app was based on a video, [Build and Deploy Your Own ChatGPT AI App ...](https://www.youtube.com/watch?v=2FeymQoKvrk). It uses [OpenAI API](https://openai.com/api/). The original source code is from [Adrian Hajdin's GitHub Repo](https://github.com/adrianhajdin/project_openai_codex). 

## Setup

1. If you don’t have Node.js installed, [install it from here](https://nodejs.org/)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd open_ai_codex
   ```

4. Create an account and API key here [OpenAI API](https://openai.com/api/)

5. Create .env file and assign OPENAI_API_KEY to [API key](https://beta.openai.com/account/api-keys)

.env

```
OPENAI_API_KEY=API_KEY
```

6. When you run npm start, the application first installs dependencies and then starts the client and server apps.
   ```
   $ npm start
   ```
7. To see the app running, go to [https://codex-git-main-acquamarina.vercel.app](https://codex-git-main-acquamarina.vercel.app)

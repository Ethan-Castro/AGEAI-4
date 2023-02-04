# OpenAI API DAPP - Python Dapp


## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/)

2. Clone this repository in your terminal
   
   ```bash
   $ git clone https://github.com/Ethan-Castro/AGEAI-4.git
   ```
3. Navigate into the project directory

   ```bash
   $ cd AGEAI-4
   ```
   4. Make a copy of the example environment variables file

   ```bash
   $ cp .env.example .env
   ```

5. Add your [API key](https://beta.openai.com/account/api-keys) to the newly created `.env` file
   
   ```bash
   $ export OPENAI_API_KEY=<insert your API key>

   ```

8. Run the app

```bash
  $ python -m venv venv
  $. venv/bin/activate
  $ pip install -r requirements.txt
  $ flask run

   ```
  
You should now be able to access the app at [http://localhost:5000](http://localhost:5000)! For the full context behind this example app, check out the [tutorial](https://beta.openai.com/docs/quickstart).

FOLLOW THIS FOR CLARITY. REPLACE FILES WITH MINE https://drive.google.com/file/d/1FIvB8pw-1GSyzn_-5mUMqOUu9Ip30GgK/view?usp=sharing

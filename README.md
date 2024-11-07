# Repository Setup

## Prerequisites

Clean Python installed on your local machine (version 3.11+ is recommended)

## Create and Activate Virtual Environment
Open the terminal on the project folder and create a new python environment:

   - On Windows:

     ```sh
     $ python -m venv .venv
     $ .\.venv\Scripts\activate
     ```
   - On macOS/Linux:

     ```sh
     $ python3 -m venv venv
     $ source .venv/bin/activate
     ```

## Install Dependencies
With the virtual environment activated, install the required dependencies:
   
```sh
   $ pip install -r requirements.txt
   ```

## Setup Hugging Face

- Register on Hugging Face with your personal account
- Create a new token (https://huggingface.co/settings/tokens/new?tokenType=fineGrained), and assign all the grants
- Store the token in a safe place (it will be used to authenticate the API requests)
- Go to the model page and accept the terms of use
  - https://huggingface.co/meta-llama/Llama-3.2-1B-Instruct
  - https://huggingface.co/sentence-transformers/all-mpnet-base-v2

Once everything is finalized make a test to check that everything is running:

- https://ui.endpoints.huggingface.co/{user}/endpoints (replace {user} with your username)

### Contacts
- Eleonora Varde (Lead Data Scientist): varde.eleonora@bcg.com
- Fabrizio Senia (Lead Data Scientist): senia.fabrizio@bcg.com
- Marta Ronconi (Data Scientist): ronconi.marta@bcg.com
- Andrea Biscontini (Data Scientist): biscontini.andrea@bcg.com

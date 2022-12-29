# OpenAI Flask Image Generator
This repository gives you introduction about how to use OpenAI API for creating Image Generator. You can find the more information about the API by checking [documentation.](https://beta.openai.com/docs/guides/images/introduction) The Flask based application allows us to describe an image we want and generate it with OpenAI API.

## Setup

1. If you don’t have Python installed, [install it from here](https://www.python.org/downloads/)

2. Clone this repository

3. Navigate into the project directory

   ```bash
   $ cd OpenAI_Flask_Image_Generator
   ```

4. Create a new virtual environment

   ```bash
   $ python -m venv venv
   $ . venv/bin/activate
   ```

5. Install the requirements

   ```bash
   $ pip install -r requirements.txt
   ```
7. Add your [API key](https://beta.openai.com/account/api-keys) to the `.env` file 

8. Run the app

   ```bash
   $ flask run

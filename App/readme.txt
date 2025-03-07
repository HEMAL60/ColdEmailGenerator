1. create virtual environment using 

python -m venv #environmentName

2. to activate the virtual environment 

 venv\Scripts\Activate.ps1

3. now install all the dependencies using 

pip install -r requirements.txt

4. add your api key in .env file in the root folder

then you can load this api key using python-dotenv library and load this api in environment variables

further while pushing all the git files to github you can add your .env file in gitignore file
#### Clone repo
`git clone https://www.github.com/dmells/Buyer_Aug_Sandbox`

#### Install pipenv & dependencies
`cd Buyer_Aug_Sandbox`

`pipenv install`

`pipenv shell`

`pipenv install -e <path to core>`

#### Allow jupyter to find pipenv kernel 

`pipenv --venv`

`python -m ipykernel install --user --name=<output from above (last part)>`

#### Set up environment variables

`nano .env`

To the .env add: 

`GOOGLE_APPLICATION_CREDENTIALS=<path to google creds>`

`STAGING_DB_URL=<staging_db_url>`

#### Load jupyter

`jupyter notebook`




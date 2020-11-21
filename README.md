# omrreader

Clone Repo: https://github.com/kabilan175/omrreader.git

# Then run the follwing to setup environment:

cd omrreader

sudo apt install uvicorn

python3 -m venv env

source env/bin/activate

pip3 install requirements.txt


# Start uvicorn server:

uvicorn main:app --reload  


# Openup your @ http://localhost:8000/

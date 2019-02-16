# prediction-app


Steps to build and run prediction app
```
python3 -m venv ./venv
source ./venv/bin/activate

pip install --upgrade pip

# pip install -r pip-requirements.txt
pip install django pandas matplotlib jupyter tensorflow keras scikit-learn scikit-image

python manage.py makemigrations
python manage.py migrate

python manage.py runserver

# point browser to http://localhost:8000/
```
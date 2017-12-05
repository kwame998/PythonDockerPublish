# PythonDockerPublish

#update all package

pip3 install pipreqs

######create requirements.txt


pipreqs .



#####deprecated

#####pip3 freeze > requirements.txt

docker build -t my-python-app .

#python3.6 manage.py runserver "0.0.0.0:8000"

docker run -d -it --rm --name my-running-app -p 8000:8000  my-python-app


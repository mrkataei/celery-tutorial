pip freeze > requirements.txt
chmod +x ./entrypoint.sh 
http://127.0.0.1:8000/
docker-compose up -d --build
./manage.py startapp taskapp
docker exec-it django /bin/sh

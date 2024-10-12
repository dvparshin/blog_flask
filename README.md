# microblog
## installation

1) clone this repository
```
git clone git@github.com:dvparshin/blog_flask.git
```
2) go to the directory
```
cd blog_flask
```
3) install python virtual env
```
python3 -m venv venv
```
4) install requirements
```
pip install -r requirements.txt
```
5) run the application
```
flask run --debug
```
6) head over to
```
http://127.0.0.1:5000/
```
or
```
http://localhost:5000/
```
# Running postgres db
1) install docker-compose
2) go to the docker directory
```bash
cd docker
```
3) deploy db and pgadmin
```bash
docker-compose up
```

# Create db
1) go to the root of the repository
```bash
cd ..
```
2) run migrate
```bash
flask db upgrade
```

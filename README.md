# Bike_Sharing_Prediction

### Use Link below to open directly in PC
https://bike-new-share.herokuapp.com

### Project DEmo Video

https://user-images.githubusercontent.com/95517533/204075802-6e4d19b4-f8ed-425f-a8d8-a7b88db43503.mp4




### Software and account Requirement.

1. [Github Account](https://github.com/)
2. [Heroku Account](https://dashboard.heroku.com/login)
3. [VS Code IDE](https://code.visualstudio.com/download)
4. [GIT cli](https://git-scm.com/downloads)
5. [Git Documentation](https://git-scm.com/docs/gittutorial)


Create conda environment
```
conda create -p venv python==3.7 -y
```

```
conda activate venv/
```
OR
```
conda activate venv
```

```
pip install -r requirements.txt
```
To Add files to git
```
git add .
```

OR
```
git add <file_name>
```

Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
```
git status
```
To check all version maintaines by git
```
git log
```

To create version/commit all changes by git
```
git commit -m "message"
```

To send version/changes to github
```
git push origin main
```

To check remote url
```
git remove -v
```
 
To setup CI?CD pipeline in heroku we nedd 3 information

1. HEROKU_EMAIL = salmanmohammed2018@gmail.com
2. HEROKU_API_KEY = <>
3. HEROKU_APP_NAME = ml-app-p



BUILD DOCKER IMAGE
```
docker build -t <image_name>:<tagname>
```

To list docker image
```
docker images
```

Run docker images
```
docker run -p 5000:5000 -e PORT=5000 <image_ifd>
```

To check running container in docker
```
docker ps
```

To stop docker container
```
docker stop <container_id>
```

```
python setup.py install 
```


Install ipykernel

```
pip install ipykernel
```

Data Drift:
When your datset stats gets changed we call it it as data drift

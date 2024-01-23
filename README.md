# [**Thyroid Disease Detection**](https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection)


## [**Heroku Link**](https://thyroiddiseasedetect.herokuapp.com/)

## [**AWS Link**](http://ec2-35-78-175-118.ap-northeast-1.compute.amazonaws.com:8080/predict)


### Docker Image
```
FROM python:3.10
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
EXPOSE $PORT
CMD gunicore --workers=4 --bind 0.0.0.0:$PORT aap:app
```     
### Procfile
```
web gunicorn app:app
```

[! [Watch the video] ()] ()

<video src="https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/TDD.mp4" controls="controls" style="max-width: 730px;">
</video>

[![Alt text](https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/static/IMAGE/Screenshot%20(121).png)](https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/TDD.mp4)

<a href="https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/TDD.mp4" target="_blank"><img src="https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/static/IMAGE/Screenshot%20(121).png" 
alt="Watch the video" width="240" height="180" border="10" /></a>


<video width="320" height="240" controls>
<source src="https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/TDD.mp4" type="video/mp4"> 
</video>


### Screenshot

![Capture](https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/static/IMAGE/Screenshot%20(121).png)

![Capture](https://github.com/MohammadWasiq0786/Thyroid-Disease-Detection/blob/main/static/IMAGE/Screenshot%20(122).png)

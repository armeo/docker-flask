# docker-flask example

```
    $ mkvirtaulenv docker-flask
	$ pip install -r requirements.txt
	
	$ docker build -t flask-example
	$ docker run -p 5000:5000 flask-example
	$ docker login
	$ docker tag flask-example armeo/flask-example
	$ ocker push armeo/flask-example
```

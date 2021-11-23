FROM python:3

#specify work directory inside the container
WORKDIR /usr/src/FlaskApp

#copy the local files to the workdir
COPY . .

#--no-cache-dir for disableing cache, smaller image size
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 5000

CMD ["python", "./app.py"]

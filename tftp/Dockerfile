# Dockerfile - this is a comment. Delete me if you want.
FROM python:3.8.0b3-buster
#COPY ./source /app
COPY ./requirements.txt /app/requirements.txt
WORKDIR /app
RUN pip install -r requirements.txt
#ENTRYPOINT ["python", "app.py"]
ENTRYPOINT ["tail","-f","/dev/null"]
#CMD ["app.py"]

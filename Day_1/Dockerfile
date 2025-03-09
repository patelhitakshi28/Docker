# we used python:3.8-alpine version because it's small in size and we can use it quickly as a base  and run it as a container.
FROM python:3.8-alpine 
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
CMD python app.py
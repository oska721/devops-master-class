FROM python:alpine3.10
WORKDIR /app
COPY requirements.txt /app/requirements.txt
#COPY . /app   #moving to step 7
RUN pip install -r requirements.txt
EXPOSE 5000
COPY . /app
#CMD python ./launch.py # if the launch.py doesnt change use ENTRYPOINT
ENTRYPOINT ["python", "./launch.py"]

#COPY requirements.txt /app/requirements.txt
#ENTRYPOINT ["python", "./launch.py"]

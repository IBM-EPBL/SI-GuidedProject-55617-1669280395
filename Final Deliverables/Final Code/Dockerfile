  FROM python:3.10.8
  LABEL maintainer="Dhanush M, dhanush.23cs@licet.ac.in"
  RUN apt-get update
  RUN mkdir /app
  WORKDIR /app
  COPY . /app
  RUN pip install -r requirements.txt
  EXPOSE 5000
  ENTRYPOINT [ "python" ]
  CMD [ "app.py" ]

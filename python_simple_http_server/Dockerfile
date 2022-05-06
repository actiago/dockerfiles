FROM python:3-alpine

RUN mkdir /data
VOLUME /data
ADD files/* /data
EXPOSE 8888

LABEL description="Simple HTTP server"
LABEL version="0.1.0"

WORKDIR /data

CMD ["python", "-m" , "http.server", "8888"]

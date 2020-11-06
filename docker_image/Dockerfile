FROM python:3.8-slim

ADD . /app
WORKDIR /app
RUN pip3 install -r requirements.txt
ENTRYPOINT ["./run_app.sh"]
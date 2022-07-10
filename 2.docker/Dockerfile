FROM python:3.9.13-slim-buster

COPY app.py requirements.txt ./

RUN python -m pip install --user -r requirements.txt && \
    pip3 install flask

WORKDIR ./

EXPOSE 8080

CMD [ "python", "-u", "./app.py" ]

FROM python:alpine

WORKDIR /opt/app
COPY ./youteller-api ./youteller-api
WORKDIR /opt/app/youteller-api

RUN pip3 install -r requirements.txt

# ENV FLASK_APP=/opt/app/youteller-api/server.py
EXPOSE 8000
ENTRYPOINT ["python"]
CMD ["server.py"]
FROM python:3
WORKDIR code
COPY app.py .
#COPY requirements.txt .
#WORKDIR ./code
RUN pip install cherrypy
RUN python -m pip install aws-cdk-lib
EXPOSE 8080
CMD python app.py

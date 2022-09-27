FROM python:3
WORKDIR code
COPY app.py .
#COPY requirements.txt .
#WORKDIR ./code
RUN pip install -r cherrypy
EXPOSE 8080
CMD python app.py

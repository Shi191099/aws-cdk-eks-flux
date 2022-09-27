FROM python:3
WORKDIR /tmp/code
COPY code .
#WORKDIR ./code
RUN pip install -r requirements.txt
EXPOSE 8080
CMD python app.py

FROM python:3
WORKDIR ./code
COPY code ./code
#WORKDIR ./code
RUN pip install -r requirements.txt
EXPOSE 8080
CMD python app.py

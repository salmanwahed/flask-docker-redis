FROM python:3.8-alpine
WORKDIR webapp
ENV FLASK_APP=app.py
ENV FLASK_RUN_HOST=0.0.0.0
COPY requirements.txt /webapp/requirements.txt
RUN pip install -r requirements.txt
COPY app.py /webapp/app.py
EXPOSE 5000
CMD ["flask", "run"]



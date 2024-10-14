FROM python:3.9

WORKDIR /usr/src/app

COPY src/ /usr/src/app

RUN pip install -r requirements.txt

EXPOSE 9080

CMD ["python", "productpage.py","9080"]

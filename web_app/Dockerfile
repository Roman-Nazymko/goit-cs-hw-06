FROM python:3.13-slim

WORKDIR /web_app

COPY . /web_app

RUN pip install --no-cache-dir -r /web_app/requirements.txt

EXPOSE 3000
EXPOSE 6000

CMD ["python", "main.py"]
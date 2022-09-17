FROM python:3.10-slim-buster
WORKDIR /code/
COPY requeriments.txt /code/
COPY outsidelib.pth /usr/local/python3.10/packages
RUN mkdir -p /usr/local/cache_python/packages
RUN pip install --no-cache-dir -r requeriments.txt
COPY . /code/
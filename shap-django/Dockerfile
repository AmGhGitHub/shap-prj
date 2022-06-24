FROM python:3.10


# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set work directory
WORKDIR /code

RUN pip install --upgrade pip

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY . .
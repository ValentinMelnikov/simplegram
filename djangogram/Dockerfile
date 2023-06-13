FROM python:3.9.10
ENV PYTHONUNBUFFERED=1
WORKDIR /code
COPY requirements.txt .

RUN pip install --upgrade pip
RUN pip install --no-cache -r requirements.txt
RUN python -m pip install Pillow


COPY . .
EXPOSE 8000
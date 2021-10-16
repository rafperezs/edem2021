FROM python:3.9.7

WORKDIR /Ejemplo3

COPY requirements.txt req.txt
COPY main.py main.py

RUN pip install -r req.txt

EXPOSE 5000

CMD ["python","main.py"]
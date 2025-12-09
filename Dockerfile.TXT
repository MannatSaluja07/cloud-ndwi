FROM python:3.9-slim

WORKDIR /app

COPY ndwi.py .

RUN pip install numpy

CMD ["python", "ndwi.py"]

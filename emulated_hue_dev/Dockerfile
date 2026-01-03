FROM python:3.11-slim

WORKDIR /src
COPY . /src
RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "-m", "emulated_hue"]

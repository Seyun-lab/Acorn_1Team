FROM python:3.10-slim

ENV PYTHONUNBUFFERED=1
WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

COPY server_D_1110.py .
COPY tank_aim_app_1105.py .

EXPOSE 5000
CMD ["python", "server_D_1110.py"]